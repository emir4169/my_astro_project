<script lang="ts">
    export let clicks: number = 0;
  
    function add() {
      clicks += 1;
    }
  
    function subtract() {
      clicks -= 1;
    }
  </script>
  
  <div class="counter">
    <button on:click={subtract}>-</button>
    <pre>{ clicks }</pre>
    <button on:click={add}>+</button>
  </div>