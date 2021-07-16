<template>
<div>
    <q-card flat bordered class="my-card bg-grey-1">
      <q-card-section>
        <div class="my-card__title">

            <div class="text-h6">Холодильник</div>
              <button>Добавить</button>
              <button>Удалить</button>
         </div>

      </q-card-section>

      <q-card-section class="my-card__main">
        <div class="my-card__item">
          <div class="my-card__image">
            <div class="my-card__item-title">Колбаса варёная </div>

            <div class="my-card__info">
              <span class="my-card__info-item">
              <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 0 24 24" width="20px" fill="#FFFFFF"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M11 7h2v2h-2zm0 4h2v6h-2zm1-9C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"/></svg>
              470 калл
              </span>
              <span class="my-card__info-item">
              <svg xmlns="http://www.w3.org/2000/svg" height="20px" viewBox="0 0 24 24" width="24px" fill="#FFFFFF"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M11 7h2v2h-2zm0 4h2v6h-2zm1-9C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"/></svg>
              470 калл
              </span>
              <span class="my-card__info-item">
              <svg xmlns="http://www.w3.org/2000/svg" height="20px" viewBox="0 0 24 24" width="24px" fill="#FFFFFF"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M11 7h2v2h-2zm0 4h2v6h-2zm1-9C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z"/></svg>
              470 калл
              </span>
            </div>
              <span class="my-card__plus-minus">
              <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 24 24" height="24px" viewBox="0 0 24 24" width="24px" fill="#FFFFFF"><g><rect fill="none" height="24" width="24"/></g><g><g><path d="M19,13h-6v6h-2v-6H5v-2h6V5h2v6h6V13z"/></g></g></svg>
              <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 0 24 24" width="24px" fill="#FFFFFF"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M19 13H5v-2h14v2z"/></svg>

            </span>
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
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',

      
    }
  }
}
</script>

<style lang="scss">
.my-card {
  width: 375px;
  height: 100%;

  &__title {
    display: flex;
    gap: 35px;
  }

  &__item-title {
    color: #ffff;
    font-size: 18px;
  } 

  &__image {
    height: 56px;
    width: 100%;
    background: url(~assets/img/boiledSausage.png);
  }

  &__info-item {

        width: 50px;
    font-size: 12px;
    color: white;
  }
}
</style>
