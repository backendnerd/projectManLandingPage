<template>
    <AnnouncementBar></AnnouncementBar>
    <main>
        <NavBar></NavBar>
    </main>
</template>

<script>
import AnnouncementBar from "./components/AnnouncementBar.vue";
import NavBar from "./components/NavBar.vue";
export default {
    name: "App",
    components: { AnnouncementBar, NavBar },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Alexandria:wght@200;300;400;500;600;700;800;900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
/* 
font-family: 'Alexandria', sans-serif;
font-family: 'Poppins', sans-serif;
*/

/* COLORS

#002743 DARK BLUE
#0ACAA7 GREEN SHADE
*/
* {
    margin: 0;
    padding: 0;
    border: 0;
}
body {
    font-family: "Poppins", sans-serif;
}
main {
    max-width: 1100px;
    margin: auto;
}
a:link {
    text-decoration: none;
    color: inherit;
}

a:visited {
    text-decoration: none;
    color: inherit;
}

a:hover {
    text-decoration: none;
    color: inherit;
}

a:active {
    text-decoration: none;
    color: inherit;
}
</style>
