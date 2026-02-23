<script setup lang="ts">

</script>

<template>
    <div class="navbar">
        <div class="navbar-box container">
            <ul class="navbar-box__list">
                <li><a href="#" class="navbar-box__list-link">Overview</a></li>
                <li><a href="#" class="navbar-box__list-link">Pages</a></li>
                <li><a href="#" class="navbar-box__list-link">Services</a></li>
                <li><a href="#" class="navbar-box__list-link">Contact</a></li>
            </ul>


            <a href="#" class="navbar-box__btn">Purchase Now</a>
        </div>


        <hr class="navbar-line">
    </div>
</template>

<style scoped lang="scss">

.navbar {

    width: 100%;
    height: 90px;
    display: flex;
    flex-direction: column;
    justify-content: center;

    &-box {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 100%;

        &__list {
            display: flex;
            gap: 40px;

            &-link {
                font-family: var(--font-family);
                font-weight: 400;
                font-size: 13px;
                line-height: 185%;
                letter-spacing: 0.02em;
                color: #000;
            }
        }

        &__btn {
            padding: 9px 25px; // размер как на скрине
            border: 2px solid #e6e8f0; // светлая рамка
            background-color: transparent;
            font-family: var(--font-family);
            font-weight: 400;
            font-size: 20px; // крупнее, как на картинке
            line-height: 1.2;
            letter-spacing: 0.02em;
            color: #1c2436;
            text-decoration: none;
            transition: all 500ms;
        }
        .navbar-box__btn:hover {
            background-color: #1c2436;
            color: #fff;
            border-color: #1c2436;
        }

    }

    &-line {
        width: 100%;
        border: none;
        border-top: 1px solid #e5e5e5;
    }
}

</style>
