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
      <h1>Company Panel</h1>
      <h4>IN-PERSON/HYBRID: $350</h4>
       <h4>VIRTUAL: $250</h4>
      <p>Host a virtual, in person, or hybrid panel to talk to our membership about your company’s mission and values, career opportunities, and commitment to diversity and inclusion.  (Three spaces per panel open)</p>
    </div>
    <div class="boxed">
      <h1>Workshop</h1>
      <h4>IN-PERSON/HYBRID: $350</h4>
       <h4>VIRTUAL: $250</h4>
      <p>Outside of our general body meetings, your company can also offer additional workshops of your choice. Past topics have included a resume building/review workshops and the interviewing process.</p>
    </div>
    <div class="boxed">
     <h1>General Body Meeting</h1>
      <h4>IN-PERSON/HYBRID: $500</h4>
       <h4>VIRTUAL: $350</h4>
      <p>Our general body meetings relay organization updates to our members and run for 1 .5 hours. Past meeting topics have included research presentations, information on internship and full-time opportunities, tech talks, and more. (One per quarter available)</p>
    </div>
    <div class="boxed">
      <h1>Professional Evening with Industry (PEI)</h1>
      <h4>TBD</h4>
      <p>Interact with undergraduate students of the Jacobs School of Engineering in this annual, in- person recruiting event, Professional Evening with Industry. Partnered with four other Diversity Organizations, PEI builds a bridge between all three sectors: the student, the professional, and the community.</p>
    </div>
  </div>
</div>
