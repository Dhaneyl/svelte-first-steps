<script>
    const handleClick = () =>{
        alert('My pussy was touched')
    }
</script>
<button on:click|capture|once={handleClick}>
    Touch my pussy
    </button>
    <style>
        button{
            background-color: aqua;
            color: aliceblue;
            border-color: aqua;
            border-radius: 10px;
        }
        </style>