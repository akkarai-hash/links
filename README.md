<!DOCTYPE html>
<html lang="en">
<head>
 
</head>
<body>

<header>
  <h1>Welcome to My Multi-Niche Site</h1>
</header>

<nav>
  <a href="#beauty">Beauty</a>
  <a href="#health">Health</a>
  <a href="#kitchen">Kitchen</a>
</nav>

<section id="beauty">
  <h2>Beauty Picks</h2>
  <div id="beauty-products">
    <p>🌸 Top Lip Balm – Moisturizing and long-lasting</p>
    <a class="button" href="https://amzn.to/your-lipbalm-link" target="_blank">Buy on Amazon</a>
  </div>
  <button class="show-more" onclick="addBeauty()">Show More</button>
</section>

<section id="health">
  <h2>Health & Wellness</h2>
  <div id="health-products">
    <p>💊 Immunity Booster Supplement – Daily support</p>
    <a class="button" href="https://amzn.to/your-supplement-link" target="_blank">Shop Now</a>
  </div>
  <button class="show-more" onclick="addHealth()">Show More</button>
</section>

<section id="kitchen">
  <h2>Kitchen Essentials</h2>
  <div id="kitchen-products">
    <p>🍳 Non-stick Pan – Easy cooking, easy cleaning</p>
    <a class="button" href="https://amzn.to/your-pan-link" target="_blank">Buy Now</a>
  </div>
  <button class="show-more" onclick="addKitchen()">Show More</button>
</section>

<script>
  function addBeauty() {
    const newProduct = `
      <p>💄 Waterproof Kajal – Smudge-proof all day</p>
      <a class="button" href="https://amzn.to/kajal-link" target="_blank">Buy Kajal</a>
    `;
    document.getElementById("beauty-products").innerHTML += newProduct;
  }

  function addHealth() {
    const newProduct = `
      <p>🥤 Protein Powder – Energy and strength daily</p>
      <a class="button" href="https://amzn.to/protein-link" target="_blank">Buy Protein</a>
    `;
    document.getElementById("health-products").innerHTML += newProduct;
  }

  function addKitchen() {
    const newProduct = `
      <p>☕ Electric Kettle – Fast boiling in minutes</p>
      <a class="button" href="https://amzn.to/kettle-link" target="_blank">Buy Kettle</a>
    `;
    document.getElementById("kitchen-products").innerHTML += newProduct;
  }
</script>

</body>
</html>
