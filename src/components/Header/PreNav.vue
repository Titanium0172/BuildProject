<script setup lang="ts">

</script>

<template>
    <div class="prenav">
        <div class="prenav-case container">
            <p class="prenav-case__text">
                Use this banner to inform your users of something important.
            </p>
        </div>
    </div>
</template>

<style scoped lang="scss">
.prenav {
    width: 100%;
    height: 56px; // или 100px / auto
    background-image: url("@/assets/images/navbar.jpg");
    background-size: cover; // растягивает на весь блок
    background-position: center; // по центру
    background-repeat: no-repeat;
    display: flex;
    align-items: center;

    &-case {
        //height: 100%;
        display: flex;
        justify-content: center;

        &__text {
            font-family: var(--font-family);
            font-weight: 400;
            font-size: 12px;
            line-height: 200%;
            letter-spacing: 0.02em;
            text-align: center;
            color: #fff;
        }
    }
}
</style>