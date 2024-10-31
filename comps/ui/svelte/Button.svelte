<script>
    export let label = "Click Me!";
    export let onClick = () => {};
  
  </script>
  
  <button 
    on:click={onClick} 
    style="padding: 10px; background-color: blue; color: white; border: none; border-radius: 5px;">
    {label}
  </button>
  
  <style>
    button:hover {
      background-color: darkblue;
    }
  </style>
  