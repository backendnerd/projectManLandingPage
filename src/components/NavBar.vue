<template>
    <nav>
        <div class="logo">
            <p>LOGO</p>
        </div>
        <ul class="navList">
            <li class="navItem" v-for="item in navList" :key="item">
                <a :href="item.toLocaleLowerCase()">
                    {{ item }}
                </a>
            </li>
        </ul>
        <div class="buttons">
            <button class="btn">Sign In</button>
            <button class="btn-outline">Demo Login</button>
        </div>
    </nav>
</template>
<script>
export default {
    data() {
        return {
            navList: ["Features", "Demo", "Developer", "Portflio"],
        };
    },
};
</script>

<style scoped>
nav {
    color: #002743;
    padding: 0.66rem 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.navList {
    list-style: none;
    display: flex;
    font-size: 1rem;
}
.navItem,
.navItem a {
    padding: 0.5rem;
}

.logo {
    font-family: "Alexandria", sans-serif;
    font-weight: 700;
    font-size: 1.5rem;
}

button {
    font-family: "Alexandria", sans-serif;
    color: #002743;
    background-color: white;
    padding: 0.75rem 1.25rem;
    font-size: 14px;
    font-weight: 600;
}
.btn:hover {
    border: 1px #002743 solid;
    transition: 300ms;
}
.btn-outline {
    transition: 300ms;
    border: 1px #002743 solid;
}
.btn-outline:hover {
    border: 1px #002743 solid;
    background-color: #002743;
    color: white;
    transition: 300ms;
}
.btn {
    text-decoration: underline;
    transition: 300ms;
    margin-right: 1rem;
    border: 1px solid transparent;
}
</style>
