<!--This is the top of the website,the header,-->
<header>
    Header
</header>


<script>
    let greeting = $state ("Hello"); //The greeting starts off as "Hello"//
</script>

<div>
    <h1>{greeting}</h1>
    <h2>What do you want to write</h2>
 <!-- The writing the user inputs showson the H1-->   
    <input type = “text” bind:value={greeting}>
</div>

<!--This is the bottom part of the website,the footer-->

<footer>
    Footer
</footer>

<style>

/* The body is configured to show all elements in the center in a column */

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}


/* The div is configured to show all elements in the center in a column */
div {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
    
}
 /* Both the header and the footer are as wide as the website and the text is aligned to be centered*/
header, footer {
    width: 100vw;
    background-color: #630a0a;
    color: white;
    padding-top: 50px;
    padding-bottom:50px;
    font-size: 30px;
    font-weight: bold;
    text-align: center;
}

footer{
    position: fixed;
    left: 0;
    bottom: 0;
}



h1 {
    font-size: 40px;
    font-weight: bold;
    color: #630a0a;
    margin-top: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

h2 {
    font-size: 28px;
    font-weight: bold;
    color: #333;
    margin-top: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

input {
    font-size: 18px;
    padding: 8px;
    width: 250px;
    border: 2px solid #630a0a;
    border-radius: 5px;
    text-align: center;

}





</style>
    
    