<template>

    <div class="main">
        <p>Malenia Miqulla'nın Kılıcı...<br>
            Radogan ve Kraliçe Marikanın ikiz çoçuklarından biri olan Malenia, kardeşi gibi hastalıklı doğmuştu. İçinde

            korkunç bir zehir barındırmaktaydı, ama onun son derece kutsal olması
            Greater Will'in mirası için uygun bir aday yapıyordu.
        </p>
    </div>
</template>

<style scoped>
.main {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 90%;
    height: 100%;
}



.main p {
    font-size: 2em;
    text-indent: 50px;
    text-align: justify;
    letter-spacing: 3px;
}

@media (max-width:854px) {
    .main p {
        font-size: 1.2em;

    }
}
</style>