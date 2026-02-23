<script setup lang="ts">
import header from '@/assets/images/header.jpg';
</script>

<template>
    <div class="header-content">
        <div class="header-content__center container">
            <a href="#" class="header-content__center-btn">MEET LEMON</a>
            <h1 class="header-content__center-title">Build a better site for enterprise business.</h1>
            <p class="header-content__center-text">Lemon contains a huge selection of common and useful components and
                layouts that help you build the best site for your business and clients.</p>
        </div>
        <img :src="header" alt="jpg">
    </div>
</template>

<style scoped lang="scss">
.header-content {

    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 40px;
    padding: 80px 0 0 0;
    &__center {
        display: flex;
        flex-direction: column;
        align-items: center;
        &-btn {
            font-family: var(--font-family);
            font-weight: 400;
            font-size: 16px;
            line-height: 150%;
            letter-spacing: 0.04em;
            text-transform: uppercase;
            text-align: center;
            color: #1c2436;
        }

        &-title {
            max-width: 651px;
            width: 100%;
            font-family: var(--second-family);
            font-weight: 400;
            font-size: 67px;
            line-height: 129%;
            letter-spacing: 0.02em;
            text-align: center;
            color: #1c2436;
            padding: 13px 0 30px 0;
        }

        &-text {
            max-width: 766px;
            width: 100%;
            font-family: var(--font-family);
            font-weight: 400;
            font-size: 18px;
            line-height: 178%;
            letter-spacing: 0.02em;
            text-align: center;
            color: #1c2436;
        }

    }
}
</style>