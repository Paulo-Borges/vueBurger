<template>
    <p id="footer">MAKE YOUR BURGUER  
        <a href="https://www.linkedin.com/in/paulo-borges-de-almeida-b543b3242/" target="_blank"> &copy; Layng 
        </a> 2022</p>
</template>
 
<script>
export default {
    name:"rodape"
}
</script>

<style scoped>
    #footer {
        height: 200px;
        background-color: #222;
        border-top: 4px solid #111;
        color: #fcba03;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }

    #footer a {
        text-decoration: none;
        margin: 0 5px;
        color: #fcba03;
        transition: .8s;
    }

    #footer a:hover {
        color: #fff;
    }


</style>