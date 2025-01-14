---
title: Home
---
<div class="md-grid">
  <div class="md-cell md-cell--4">
    <a href="../HVS/Page1.md">
      <div class="md-card">
        <div class="md-card__media md-card__media--16:9">
          <img src="../assets/images/tile1.jpg" alt="HVS Tile" style="max-width: 100%;>
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
  display: flex; /* Use flexbox for horizontal layout */
  flex-wrap: wrap; /* Allow tiles to wrap to the next row if needed */
  justify-content: space-between; /* Add space between tiles */
}

.md-cell {
  flex: 1; /* Allow cells to grow and shrink to fill available space */
  min-width: 300px; /* Set a minimum width for each tile */
  margin-bottom: 20px; /* Add vertical spacing between rows */
}



