<template>
    <div class="navbar">
        <div class="navbar-container">
            <NuxtLink to="/">
                Home
            </NuxtLink>

            <NuxtLink to="/events">
                Events
            </NuxtLink>

            <NuxtLink to="/teams">
                Teams
            </NuxtLink>

            <NuxtLink to="/players">
                Players
            </NuxtLink>
        </div>
    </div>
</template>

<style scoped lang="scss">
.navbar{
    margin-bottom: 10px;
    padding: 10px;
    padding-left: 0px;
    width: 100vw;
    background-color: $background;
    box-shadow: 0px 5px 10px $secondary; 
}

.navbar-container{
    margin-bottom: 0px;
    padding: 0px;
    display: flex;
    background-color: $background;
    margin-left: 20vw;
}
.navbar-container * {
    background-color: $background;
    margin-right: 15px;
    border-radius: 5px;
    padding: 10px;
    padding-left: 0px;
    color: $text;
    text-decoration: unset;
    font-size: larger;
}

.activeClass {
    background-color: blue;
}

</style>