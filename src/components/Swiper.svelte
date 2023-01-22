<script lang="ts">
</script>

<div class="items">
  <div class="item">ITEM 1</div>
  <div class="item">ITEM 2</div>
  <div class="item">ITEM 3</div>
  <div class="item">ITEM 4</div>
  <div class="item">ITEM 5</div>
  <div class="item">ITEM 6</div>
  <div class="item">ITEM 1</div>
  <div class="item">ITEM 2</div>
  <div class="item">ITEM 3</div>
  <div class="item">ITEM 4</div>
  <div class="item">ITEM 5</div>
  <div class="item">ITEM 6</div>
</div>

<style>
  .items {
    background: orange;
    display: flex;
    overflow: auto;
  }
  .item {
    white-space: nowrap;
    min-width: 200px;
    display: grid;
    place-content: center;
    border: 1px solid black;
  }
</style>
