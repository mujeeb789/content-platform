<template>
    <div>
        <header class="text-lg  p-3 shadow-md" >
            
            <ul class="flex justify-between items-center">
                <li> <a href=""> <logo /> </a> </li> 
                <li class="text-2xl"><a href="#">categories</a></li>
                <li><input type="text" class="border-solid border-2 w-[150%] p-4 rounded border-sky-500 p-2" placeholder="search for anything"></li>
                <li><a href="">bhbb</a></li>
                <li><button class="light-button">Log in</button></li>
                <li><button class="dark-button">Sign Up</button></li>
                
            </ul>

        </header>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    button{
        border: 1px solid brown;
        padding: 10px 25px;
        color: brown;
    }
    .light-button:hover{
        background: brown;
        color: white;
    }
    .dark-button{
      background: brown;   
      color: white;
    }
    .dark-button:hover{
        background: white;
        color: brown;
    }
    
   


</style>