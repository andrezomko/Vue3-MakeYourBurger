<template lang="">
    <footer id="footer">
        <p>Make Your Burguer &copy; 2022</p> 
    </footer>
</template>


<script>
export default {
    name: 'theFooter'
    
}
</script>

<style scoped>

footer{
    height: 200px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #fcba03;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
}
footer p{
    font-size: 3rem;
}
@media (max-width: 327px){
    #footer{
        width:340px;
    }
    footer p{
        font-size: 1.4rem;
    }
}
    
</style>