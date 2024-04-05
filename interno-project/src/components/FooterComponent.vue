<template>
    <footer>
        <div class="footer-card">
            <img src="../../../img/Logo.svg" alt="Logo">
            <p class="footer-desc">It is a long established fact that a reader will be distracted lookings.</p>
            <div class="icons">
                <img class="twitter" src="../../../img/twitter.png" alt="twitter">
                <img src="../../../img/in.png" alt="in">
            </div>
        </div>
        <div class="footer-card">
            <p class="pages">Pages</p>
            <p class="pages-name">Home</p>
            <p class="pages-name">Project</p>
            <p class="pages-name">Blog</p>
        </div>
        <div class="footer-card">
            <p class="contact">Contact</p>
            <p class="contacts">55 East Birchwood Ave. Brooklyn, New York 11201</p>
            <p class="contacts">contact@interno.com</p>
            <p class="contacts">(123) 456 - 7890</p>
        </div>
    </footer>
</template>

<style>
footer {
    display: flex;
    justify-content: space-between;
    margin-top: 96px;
    margin-bottom: 134px;
}
.footer-desc {
    font-family: Jost;
    font-size: 22px;
    font-weight: 400;
    line-height: 33px;
    letter-spacing: 0.01em;
    text-align: left;
    width: 393px;
}
.twitter {
    margin-right: 54px;
    
}
.pages {
    font-family: DM Serif Display;
    font-size: 25px;
    font-weight: 400;
    line-height: 31px;
    letter-spacing: 0em;
    text-align: left;
    color: #292F36;
    margin: 0;
}
.pages-name {
    font-family: Jost;
    font-size: 22px;
    font-weight: 400;
    line-height: 66px;
    letter-spacing: 0.01em;
    text-align: left;
    color: #4D5053;
    margin: 0;
}
.contact {
    font-family: DM Serif Display;
    font-size: 25px;
    font-weight: 400;
    line-height: 31px;
    letter-spacing: 0em;
    text-align: left;
    margin: 0;
    color: #292F36;
}
.contacts {
    font-family: Jost;
    font-size: 22px;
    font-weight: 400;
    line-height: 33px;
    letter-spacing: 0.01em;
    text-align: left;
    color: #4D5053;
    width: 258px;
}
</style>