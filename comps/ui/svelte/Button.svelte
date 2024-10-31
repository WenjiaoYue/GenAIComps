<script>
    export let label = "Click Me";
    export let onClick = () => {}; 
  </script>
  
  <button on:click={onClick}> {label} </button>
  
  <style>
    button {
      padding: 10px;
      background-color: blue;
      color: white;
      border: none;
      border-radius: 5px;
      transition: background-color 0.3s; 
    }
  
    button:hover {
      background-color: rgb(0, 174, 255); 
    }
  </style>
  