<template>

    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>

</template>

<script>

</script>

<style>

body{
  background-color: #94979a;
  margin-left: 270px;
  margin-right: 270px;
  background-image: url("biner.jpg");
}

nav {
background-color: #0e66a1;
display: flex;
justify-content: center;
padding: 1rem;
border-radius: 7px;
}

nav a {
color: #fff;
font-size: 1.2rem;
text-decoration: none;
margin: 0 1rem;
}

nav a:hover {
text-decoration: underline;
color: rgb(19, 219, 196);
}

/* Styling for the To-Do List */
h2 {
font-size: 2rem;
font-weight: bold;
text-align: center;
margin-top: 2rem;
}

ul {
list-style: none;
margin: 0;
padding: 0;
}

li {
display: flex;
align-items: center;
padding: 1rem;
margin: 0.5rem 0;
background-color: #f5f5f5;
border-radius: 5px;
box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

li:hover {
background-color: #fff;
}

.completed {
text-decoration: line-through;
}

button {
background-color: #3498db;
color: #fff;
border: none;
border-radius: 5px;
padding: 0.5rem 1rem;
margin-left: auto;
cursor: pointer;
}

button:hover {
background-color: #2980b9;
}

form {
display: flex;
margin-top: 1rem;
}

input[type="text"] {
flex: 1;
padding: 0.5rem;
border: 1px solid #ccc;
border-radius: 5px;
}

button[type="submit"] {
background-color: #2ecc71;
color: #fff;
border: none;
border-radius: 5px;
padding: 0.5rem 1rem;
margin-left: 0.5rem;
cursor: pointer;
}

button[type="submit"]:hover {
background-color: #27ae60;
}
</style>