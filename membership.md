---
layout: page
title: Membership
---

<style>
  /* Styling for the boxed content */
  .boxed {
    background: #F2F2F2;
    color: black;
    border: 3px solid #535353;
    width: 456px;
    height: 500px;
    padding: 10px;
    border-radius: 10px;
    text-align: center;
  }

  /* Wrapper to center the grid */
  .grid-wrapper {
    display: flex;
    justify-content: center; /* Centers the grid */
  }

  /* Grid container to arrange boxes */
  .box-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* 2 columns */
    gap: 20px; /* Space between boxes */
    max-width: 1000px; /* Limits width */
  }

  /* Moves the first box to the left */
  .first-box {
    justify-self: start; /* Aligns the first box to the left */
  }
</style>

<!-- Wrapper to ensure the grid is centered -->
<div class="grid-wrapper">
  <div class="box-container">
    <div class="boxed first-box">
      Professional Evening with Industry (PEI) 
    </div>
    <div class="boxed">
      National & Regional Conferences
    </div>
    <div class="boxed">
      General Body Meeting
    </div>
    <div class="boxed">
      Qtorship & Comittees
    </div>
  </div>
</div>
