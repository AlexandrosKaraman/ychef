<template>
<div>
    <q-card flat bordered class="my-card bg-grey-1">
      <q-card-section>
        <div class="row items-center no-wrap">
          <div class="col">
            <div class="text-h6">Our Planet</div>
            <div class="text-subtitle2">by John Doe</div>
          </div>
        </div>

      </q-card-section>

      <q-card-section class="my-card__main">
        <div class="my-card__item">
          <div class="my-card__image">

            <div><img src="/assets/img/boiledSausage.png" alt=""></div>
          </div>
        </div>
      </q-card-section>

      <q-separator />

      <q-card-actions>
        
        <q-btn flat>Холодильник</q-btn>
        <q-btn flat>Рецепты</q-btn>
        <q-btn flat>О нас</q-btn>
      </q-card-actions>
    </q-card>
</div>

</template>

<script>
export default {
  setup () {
    return {
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
    }
  }
}
</script>

<style lang="scss">
.my-card {
  width: 375px;
  height: 100%;

  &__image {
    height: 56px;
    width: 100%;
    background: url(/assets/img/boiledSausage.png);
  }
}
</style>
