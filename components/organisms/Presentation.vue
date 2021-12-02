<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti aut
      vitae at aspernatur reprehenderit odio eaque quos placeat similique
      mollitia alias quisquam veniam, dolor laudantium non dolores, accusamus
      ipsa nostrum.
    </p>
    <img src="@/assets/img/presentation.svg" alt="Apresentação do iBook" />
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
