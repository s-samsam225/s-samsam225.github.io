---
layout: page
title: Sponsorship
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

  /* Grid container to arrange boxes */
  .box-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* 2 columns */
    gap: 20px; /* Space between boxes */
    max-width: 1000px; /* Limits width */
    margin: 0 auto; /* Centers grid container */
  }

  /* Moves the first box to the left */
  .first-box {
    justify-self: start; /* Aligns the first box to the left */
  }
</style>

<!-- Box Grid Container -->
<div class="box-container">
  <div class="boxed first-box">
    Company Panel
  </div>
  <div class="boxed">
    Workshop
  </div>
  <div class="boxed">
    General Body Meeting
  </div>
  <div class="boxed">
    Professional Evening with Industry (PEI)
  </div>
</div>
