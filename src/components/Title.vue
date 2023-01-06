<template>
<h1>Yasser Al Sleiman</h1>
</template>

<style scoped>
h1{
    font-size: 1.5em;
    text-align: center;
    font-family: Georgia, 'Times New Roman', Times, serif;
    background-image: linear-gradient(90deg,#000,#fefefe,#000);
    background-size: 90% 100%;
    background-repeat: no-repeat;
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    padding:1rem;
    text-transform:uppercase;
    animation: shine 6s linear infinite;
}
@keyframes shine{  
    from{
     background-position: -500% 0;   
    }
    to{
       background-position: 500% 0; 
    }
}
</style>