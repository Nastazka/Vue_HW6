<template>
    <header>
        <img class="logo-img" src="../../../img/Logo.svg" alt="Logo">
        <div class="head-menu">
            <a class="head-items" href="#">Home</a>
            <p class="head-items">Project</p>
            <a class="head-items" href="#">Blog</a>
        </div>
    </header>
</template>

<style>
header {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-bottom: 57px;
}
.head-menu {
    display: flex;
    width: 235px;
    justify-content: space-between;
}
.head-items {
    font-family: Jost;
    font-size: 20px;
    font-weight: 400;
    line-height: 25px;
    letter-spacing: 0em;
    text-align: center;
    margin-top: 56px;
    text-decoration: none;
    color: #292F36;
}
.head-items:hover {
    color: #5C5C5C;
}
</style>