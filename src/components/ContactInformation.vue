<template>
    <!-- <div class="mail">
        <p>linus.hjeltman@hotmail.com</p>
    </div> -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <div class="contact">
        <a href="https://github.com/linushjeltman">
            <p> <i class="fab fa-github-square"></i> linushjeltman </p>
        </a>
        <a href="tel:0705181455">
            <p> <i class="fas fa-phone-square"></i> 070 518 14 55 </p>
        </a>
        <a href="mailto:linus.hjeltman@hotmail.com">
            <p> <i class="fas fa-envelope-square"></i> linus.hjeltman@hotmail.com</p>
        </a>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.mail {
    font-size: 15px;
}

a:link,
a:visited {
    color: white;
    text-decoration: none;
}

a:hover,
a:active {
    color: rgba(255, 255, 255, 0.753);
}

.contact {
    text-align: left;
    font-size: 30px;
    position: absolute;
    bottom: 0;
}

@media only screen and (max-width: 400px) {
    .contact {
        font-size: 20px;
    }
}
</style>