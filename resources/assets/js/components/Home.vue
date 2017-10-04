<template lang="html">
  <nav class="panel column is-offset-2 is-8">
  <p class="panel-heading">
    Vuejs Phonebook
    <button class="button is-primary is-outlined ">
        Add new
    </button>
  </p>
  <div class="panel-block">
    <p class="control has-icons-left">
      <input class="input is-small" type="text" placeholder="search">
      <span class="icon is-small is-left">
        <i class="fa fa-search"></i>
      </span>
    </p>
  </div>


  <a class="panel-block">
    <span class="column is-9">
      marksheet
    </span>
    <span class="column panel-icon is-1">
      <i class="has-text-danger fa fa-trash" aria-hidden="true"></i>
    </span>
    <span class="column panel-icon is-1">
      <i class="has-text-info fa fa-edit" aria-hidden="true"></i>
    </span>
    <span class="column panel-icon is-1">
      <i class="has-text-primary fa fa-eye" aria-hidden="true"></i>
    </span>
  </a>


</nav>

</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
