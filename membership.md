---
layout: page
title: Membership
---

<style>
  /* Centers everything */
  .grid-wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    padding: 20px;
  }

  /* Grid layout for the boxes */
  .box-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Flexible columns */
    gap: 30px;
    max-width: 1000px;
    width: 100%;
  }

  /* Styled box */
  .boxed {
    background: #F2F2F2;
    color: black;
    border: 3px solid #535353;
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
  }

  /* Mobile-friendly adjustments */
  @media (max-width: 768px) {
    .box-container {
      grid-template-columns: 1fr; /* Single column */
    }
    .boxed {
      width: 90%;
      margin: auto;
    }
  }
</style>

<!-- Centered grid layout -->
<div class="grid-wrapper">
  <div class="box-container">
    <div class="boxed">
      <h3>Professional Evening with Industry (PEI)</h3>
      <p>The Diversity Organizations of the Jacobs School of Engineering come together every year to hold a unique event for companies to meet with the accomplished students of the Jacobs School of Engineering...</p>
    </div>
    <div class="boxed">
      <h3>National & Regional Conferences</h3>
      <p>STEM @ UC San Diego takes part in annual conferences organized by oSTEM Incorporated and by oSTEM Region F...</p>
    </div>
    <div class="boxed">
      <h3>Qtorship & Committees</h3>
      <p>Qtorship is a program within oSTEM @ UC San Diego that strives to build a network between our members by pairing students...</p>
    </div>
  </div>
</div>
