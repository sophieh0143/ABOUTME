---
layout: base
title: I'm Sophie Haas
hide: true
---

Hi! My name is Sophie Haas

### Development Environment

> Coding starts with tools, explore these tools and procedures with a click.

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="https://github.com/Open-Coding-Society/student">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
    </a>
    <a href="https://open-coding-society.github.io/student">
        <img src="https://img.shields.io/badge/GitHub%20Pages-327FC7?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages">
    </a>
    <a href="https://kasm.nighthawkcodingsociety.com/">
        <img src="https://img.shields.io/badge/KASM-0078D4?style=for-the-badge&logo=kasm&logoColor=white" alt="KASM">
    </a>
    <a href="https://vscode.dev/">
        <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode">
    </a>
</div>

<br>

### Class Progress

> Here is my progress through coding, click to see these online

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="{{site.baseurl}}/snake" style="text-decoration: none;">
        <div style="background-color: #00FF00; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold;">
            Snake Game
        </div>
    </a>
    <a href="{{site.baseurl}}/turtle" style="text-decoration: none;">
        <div style="background-color: #FF0000; color: white; padding: 10px 20px; border-radius: 5px; font-weight: bold;">
            Turtle
        </div>
    </a>
</div>

<br>

<!-- Contact Section -->
### Get in Touch

> Feel free to reach out if you'd like to collaborate or learn more about our work.

<p style="color: #2A7DB1;">Open Coding Society: <a href="https://opencodingsociety.com" style="color: #2A7DB1; text-decoration: underline;">Socials</a></p>

---
layout: post
title: All About Me!
permalink: /about/
comments: true
---

# 𝓐𝓵𝓵 𝓐𝓫𝓸𝓾𝓽 𝓜𝓮!

<comment>
Images are found using google browser
</comment>

<style>
    /* Style looks pretty compact, 
       - grid-container and grid-item are referenced the code 
    */
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Dynamic columns */
        gap: 10px;
    }
    .grid-item {
        text-align: center;
    }
    .grid-item img {
        width: 100%;
        height: 100px; /* Fixed height for uniformity */
        object-fit: contain; /* Ensure the image fits within the fixed height */
    }
    .grid-item p {
        margin: 5px 0; /* Add some margin for spacing */
    }

    .image-gallery {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 10px;
        }

    .image-gallery img {
        max-height: 150px;
        object-fit: cover;
        border-radius: 5px;
    }
</style>

<!-- This grid_container class is used by CSS styling and the id is used by JavaScript connection -->
<div class="grid-container" id="grid_container">
    <!-- content will be added here by JavaScript -->
</div>

<script>
    // 1. Make a connection to the HTML container defined in the HTML div
    var container = document.getElementById("grid_container"); // This container connects to the HTML div

    // 2. Define a JavaScript object for our http source and our data rows for the Living in the World grid
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var living_in_the_world = [
        {"flag": "0/01/Flag_of_California.svg", "greeting": "Hey", "description": "California - forever"},
        {"flag": "b/b9/Flag_of_Oregon.svg", "greeting": "Hi", "description": "Oregon - 9 years"},
        {"flag": "b/be/Flag_of_England.svg", "greeting": "Alright mate", "description": "England - 2 years"},
        {"flag": "e/ef/Flag_of_Hawaii.svg", "greeting": "Aloha", "description": "Hawaii - 2 years"},
    ];

    // 3a. Consider how to update style count for size of container
    // The grid-template-columns has been defined as dynamic with auto-fill and minmax

    // 3b. Build grid items inside of our container for each row of data
    for (const location of living_in_the_world) {
        // Create a "div" with "class grid-item" for each row
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";  // This class name connects the gridItem to the CSS style elements
        // Add "img" HTML tag for the flag
        var img = document.createElement("img");
        img.src = http_source + location.flag; // concatenate the source and flag
        img.alt = location.flag + " Flag"; // add alt text for accessibility

        // Add "p" HTML tag for the description
        var description = document.createElement("p");
        description.textContent = location.description; // extract the description

        // Add "p" HTML tag for the greeting
        var greeting = document.createElement("p");
        greeting.textContent = location.greeting;  // extract the greeting

        // Append img and p HTML tags to the grid item DIV
        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);

        // Append the grid item DIV to the container DIV
        container.appendChild(gridItem);
    }
</script>

### ~ Fun Facts About Me! ~

- 💙 My favorite color is blue!
- 🧁 I am very good at baking, because I know I will eat anything and everything I make.
- 😋 My favorite food is pasta!
- 🔥 I love spicy food!
- 👟 My shoe size is 7 in womens
- I LOVE CATS!!!

#### 🎂🎉My Birthday!🎉🎂
- October 22, 2010! (I'm a Libra) ♎ 

### These are some of my favorite animals.
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Cat03.jpg" alt="Cute Cat" style="height:120px; border-radius:8px; margin:10px 0;" />
<img src="https://preview.redd.it/this-cute-tuxedo-cat-v0-0ouqgkg7n5xd1.jpeg?width=640&crop=smart&auto=webp&s=04cb960dfc4d477065a4098e3b847b9d98fe6104" alt="Cute Tuxedo Cat" style="height:120px; border-radius:8px; margin:10px 0;" />
<img src="https://breeds.okstate.edu/poultry/site-files/images/call_duck.jpg" alt="Call Duck" style="height:120px; border-radius:8px; margin:10px 0;" />

### Countries I'm From!
<img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Flag_of_France.svg" alt="French Flag" style="height:50px; vertical-align:middle; margin-right:10px;" />
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5c/Flag_of_Greece.svg" alt="Greek Flag" style="height:50px; vertical-align:middle; margin-right:10px;" />
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Flag_of_Sweden.svg" alt="Swedish Flag" style="height:50px; vertical-align:middle; margin-right:10px;" />
<img src="https://upload.wikimedia.org/wikipedia/commons/b/ba/Flag_of_Germany.svg" alt="German Flag" style="height:50px; vertical-align:middle; margin-right:10px;" />
<img src="https://upload.wikimedia.org/wikipedia/commons/0/03/Flag_of_Italy.svg" alt="Italian Flag" style="height:50px; vertical-align:middle; margin-right:10px;" />
<img src="https://upload.wikimedia.org/wikipedia/commons/a/ae/Flag_of_the_United_Kingdom.svg" alt="British Flag" style="height:50px; vertical-align:middle; margin-right:10px;" />


Gallery of Pics, scroll to the right for more ...
</comment>
<div class="image-gallery">
 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Movable Character Demo</title>
  <style>
    #player {
      position: fixed;
      left: 50px;
      top: 100px;
      font-size: 2.5em;
      z-index: 9999;
      pointer-events: none;
      user-select: none;
    }
  </style>
</head>
<body>
  <h2>Move the Character!</h2>
  <p>
    This is some text on your page. The character can move over it.<br>
    Use <b>WASD</b> or <b>Arrow Keys</b> to move the character.
  </p>
  <div id="player">🐱</div>
  <script>
    const player = document.getElementById('player');
    let x = 50, y = 100;
    const step = 20;

    function movePlayer(dx, dy) {
      x += dx;
      y += dy;
      player.style.left = x + 'px';
      player.style.top = y + 'px';
    }

    document.addEventListener('keydown', (e) => {
      switch(e.key) {
        case 'ArrowUp': case 'w': case 'W': movePlayer(0, -step); break;
        case 'ArrowDown': case 's': case 'S': movePlayer(0, step); break;
        case 'ArrowLeft': case 'a': case 'A': movePlayer(-step,
