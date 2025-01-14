---
title: Home
---
<div class="md-grid">
  <div class="md-cell md-cell--4">
    <a href="../HVS/Page1.md">
      <div class="md-card">
        <div class="md-card__media md-card__media--16:9">
          <img src="../assets/images/tile1.jpg" alt="HVS Tile">
        </div>
        <div class="md-card__content">
          <h2 class="md-card__title">HVS</h2>
          <p class="md-card__description">This tile belongs to HVS</p>
        </div>
      </div>
    </a>
  </div>

  <div class="md-cell md-cell--4">
    <a href="page2.md">
      <div class="md-card">
        <div class="md-card__media md-card__media--16:9">
          <img src="images/tile2.jpg" alt="Tile 2 Image">
        </div>
        <div class="md-card__content">
          <h2 class="md-card__title">Tile 2 Title</h2>
          <p class="md-card__description">Tile 2 Description</p>
        </div>
      </div>
    </a>
  </div>
</div>

<style>
.md-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px; /* Adjust spacing between tiles as needed */
}

.md-card {
  padding: 20px;
  border: 1px solid #ddd; /* Adjust border thickness and color */
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Add subtle shadow */
  text-align: center; /* Center content within the card */
}

.md-card__media img {
  width: 100%;
  height: auto;
  object-fit: cover; /* Maintain aspect ratio and crop if needed */
}

.md-card__content {
  margin-top: 10px; /* Add spacing between image and text */
}

.md-card__title {
  font-size: 1.2rem; /* Adjust title font size */
  margin-bottom: 5px; /* Add spacing between title and description */
}

.md-card__description {
  font-size: 0.9rem; /* Adjust description font size */
  color: #666; /* Adjust description text color */
}

/* Optional: Add hover effects for a more interactive look */
.md-card:hover {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  transform: translateY(-2px); /* Add slight hover animation */
}
</style>



<div class="md-cell md-cell--4">
    <a href="page1.md">
      <div class="md-card">
        <div class="md-card__media md-card__media--16:9">
          <img src="images/tile1.jpg" alt="Tile 1 Image">
        </div>
        <div class="md-card__primary">
          <h2 class="md-card__title">Tile 1 Title</h2>
        </div>
        <div class="md-card__secondary">
          <p>Tile 1 Description</p>
        </div>
      </div>
    </a>
  </div>

<div class="md-cell md-cell--4">
    <a href="page1.md">
      <div class="md-card">
        <div class="md-card__media md-card__media--16:9">
          <img src="images/tile1.jpg" alt="Tile 1 Image">
        </div>
        <div class="md-card__primary">
          <h2 class="md-card__title">Tile 1 Title</h2>
        </div>
        <div class="md-card__secondary">
          <p>Tile 1 Description</p>
        </div>
      </div>
    </a>
  </div>

<!--
  <div class="md-cell md-cell--4">
    <a href="page2.md"> 
      <div class="md-card"> 
        </div> 
      </a> 
  </div> 
-->

  </div> 
</div>
