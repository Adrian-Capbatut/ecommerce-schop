<template>
    <header>
        <div class="header-top">
            <div class="header-top-search">
                <img src="/svg/header-search.svg" alt="search" />
            </div>
            <a href="#" class="header-logo">Beta</a>
            <div class="header-top-right">
                <div class="header-top-right__cart">
                    <a href="#">
                        <img src="/svg/header-cart.svg" alt="cart" />
                    </a>
                </div>
                <div class="header-top-right__user">
                    <a href="#">
                        <img src="/svg/header-user.svg" alt="user" />
                    </a>
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
.header {
    height: 132px;
    background: #fff;

    &-top {
        display: flex;
        justify-content: space-between;

        &-right {
            display: flex;
            align-items: center;

            &__cart {
                margin-right: 16px;
            }
        }
    }

    &-logo {
        color: #22202e;
        font-size: 24px;
        text-decoration: none;
        font-family: "Overused Grotesk", sans-serif;

        &:hover {
            text-decoration: underline;
        }
    }
}
</style>
