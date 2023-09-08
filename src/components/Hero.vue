<template>
    <div class="hero">
        <div class="hero-info">
            <div class="hero-info-text">
                <h2 class="hero-info__title">
                    Luxury homeware for people who love timeless design quality
                </h2>
                <span class="hero-info__description">Shop the new Spring 2022 collection today</span>
            </div>
            <a href="#" class="hero-info-link">View collection</a>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.hero {
    background: url("https://mobilalaguna.ro/mobilier/wp-content/uploads/2021/10/Set-Dormitor-Gri-Noce-C4.jpg");
    height: 704px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding-right: 80px;
    font-weight: 400;

    &-img {
        min-width: 100%;
    }

    &-info {
        background: #fff;
        max-width: 630px;
        padding: 48px 61px 46px 56px;
        height: 444px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;

        &__title {
            color: #22202E;
            font-size: 32px;
            font-family: "Overused Grotesk", sans-serif;
            line-height: 140%;
            margin: 0 0 20px 0;
        }

        &__description {
            color: #5B5676;
            font-size: 18px;
        }

        &-link {
            color: #2a254b;
            text-decoration: none;

            &:hover {
                text-decoration: underline;
            }
        }
    }
}
</style>
