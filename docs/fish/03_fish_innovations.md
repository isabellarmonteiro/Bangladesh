---
layout: default
title: Innovation Highlights
parent:  Fish
nav_order: 6
mathjax: true
---


<style>
/* Custom Table Styling */
.custom-table {
  background-color: rgba(0, 128, 0, 0.2); /* Light green */
  border-collapse: collapse;
  width: 100%;
  margin: 20px 0;
  font-size: 1rem;
}

.custom-table th {
  background-color: rgba(0, 128, 0, 0.4); /* Darker green */
  color: white;
  text-align: left;
  padding: 8px;
}

.custom-table th, .custom-table td {
  border: 1px solid #ddd;
  padding: 8px;
}

.custom-table tr:nth-child(even) {
  background-color: rgba(0, 128, 0, 0.1); /* Alternating row color */
}

.custom-table tr:hover {
  background-color: rgba(0, 128, 0, 0.3); /* Highlight on hover */
}

/* Modal styles */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0, 0, 0, 0.4);
}
.modal-content {
  background-color: #fff;
  margin: 10% auto;
  padding: 20px;
  border: 1px solid #ddd;
  width: 80%;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
}
.close-btn {
  color: #aaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
  cursor: pointer;
}
.close-btn:hover,
.close-btn:focus {
  color: #000;
  text-decoration: none;
}
</style>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fisheries Innovations Table</title>
</head>
<body>

<table class="custom-table">
  <thead>
    <tr>
      <th>Innovation</th>
      <th>Description</th>
      <th>Observable Feature</th>
      <th>Likely to be at scale?</th>
      <th>Source</th>
      <th>Attribution</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>GIFT Tilapia</td>
      <td>Fast-growing male Tilapia</td>
      <td>Household has GIFT-derived tilapias.<br>DNA fingerprinting or seed sourced from hatchery carrying GIFT.</td>
      <td>Yes</td>
      <td>“The 18-fold increase in tilapia production in Bangladesh from 19,320 MT in 2005 to 347,800 MT in 2015 (...) has been attributed in large part to GIFT (Tran et al, 2020)”</td>
      <td>High. Developed by WorldFish</td>
    </tr>
    <tr>
      <td>G3 Rohu Carp</td>
      <td>Fast-growing Rohu Carps (37% faster growth).</td>
      <td>Household has G3 rohu carps.<br>DNA fingerprinting or seed sourced from hatchery carrying G3 rohu.</td>
      <td>Yes</td>
      <td>
        As of 2023, G3 rohu is already available at 
        <a href="#" id="hatcheries-link">30 commercial hatcheries</a>.
      </td>
      <td>High. Developed by WorldFish</td>
    </tr>
  </tbody>
</table>

<!-- Modal -->
<div id="hatcheries-modal" class="modal">
  <div class="modal-content">
    <span class="close-btn">&times;</span>
    <h3>List of 30 Commercial Hatcheries</h3>
    <ul>
      <li>Jamuna Fish Limited, Barisal, Agailjhara, Doshumi, Doshumi, 8801743916696</li>
      <li>Bhola Monosex Tilapia Hatchery, Bhola, Bhola Sadar, Charkhali, 8801718186242</li>
      <li>Mannan Kritrim Mothsya Projonon Kendra, Bogura, Bogura Sadar, Erulia, Bandighi, 8801711123954</li>
      <li>The Arefa Motso Hatchery, Bogura, Bogura Sadar, Erulia, Bandighi, 8801711584019</li>
      <li>BRAC Fish Hatchery, Dinajpur, Birganj, Mohonpur, Miratongi, 8801704121090</li>
      <li>Messrs Hai Hatchery & Fish Farm, Dinajpur, Kaharole, Mukundapur, Hatisha, 8801713723813</li>
      <li>Ma Fatima Fish Hatchery, Jashore, Jashore Sadar, Chanchra, Dalmill, 8801711390513</li>
      <li>Matri Fish Hatchery & Agribased Farm, Jashore, Jashore Sadar, Chanchra, 01711375413</li>
      <li>Rupaly Fish Hatchery, Jashore, Jashore Sadar, Chanchra, 01711398525</li>
      <li>Mukteshary Fish Hatchery, Jashore, Jashore Sadar, Kazipur, 01712561752</li>
      <!-- Add remaining hatcheries similarly -->
    </ul>
  </div>
</div>

<script>
  // Get modal elements
  const modal = document.getElementById("hatcheries-modal");
  const link = document.getElementById("hatcheries-link");
  const closeBtn = document.querySelector(".close-btn");

  // Show modal on link click
  link.addEventListener("click", function(event) {
    event.preventDefault();
    modal.style.display = "block";
  });

  // Hide modal on close button click
  closeBtn.addEventListener("click", function() {
    modal.style.display = "none";
  });

  // Hide modal on outside click
  window.addEventListener("click", function(event) {
    if (event.target === modal) {
      modal.style.display = "none";
    }
  });
</script>

</body>
</html>




<table class="custom-table" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr>
      <th>Innovation</th>
      <th>Description</th>
      <th>Observable Feature</th>
      <th>Likely to be at scale?</th>
      <th>Source</th>
      <th>Attribution</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SIS in Polyculture with Carps</td>
      <td>Mola are grown in homestead ponds used for carp production</td>
      <td>Household is growing carp and SIS in the same pond.<br>Some accompanying carp-SIS polyculture technologies are likely to also be present.</td>
      <td>Yes</td>
      <td>BIHS 2018<br>26% of ponds were said to be growing carps alongside small fish</td>
      <td>Low. SIS-Carp polyculture was first explored in Bangladesh in 2003 in a collaboration between the Department of Fisheries (DoF) and DANIDA. More recently, BAU has been developing</td>
    </tr>
    <tr>
      <td>Specific Pathogen-Free (SPF) shrimp seed</td>
      <td>Shrimp post-larvae free from WSSV and other viruses</td>
      <td>Negative PCR-tests<br>Post-larvae procured from one of the 24 hatcheries that provide WSS-free seed</td>
      <td>Yes</td>
      <td>Between 2013 and 2015, project distributed 1 billion post-larvae free from WSSV and other viruses<br><a href="https://worldfishcenter.org/pages/shrimp-bd/">worldfishcenter.org</a></td>
      <td>-</td>
    </tr>
    <tr>
      <td>Co-management of fisheries</td>
      <td>Community-based fishery management (CBM) developed by Worldfish during the two phases of ECOFISH</td>
      <td>Presence of fish guards to enforce rules,<br>Food incentives to communities during fishing bans<br>Presence of Alternative income-generating activities (AIGAs) (e.g., seaweed farming in Cox’s Bazar)<br>Co-management groups at village, upazila, and district levels.</td>
      <td>Yes?</td>
      <td>NA</td>
      <td>High. This model was developed by Worldfish through ECOFISH, a USAID-funded project</td>
    </tr>
  </tbody>
</table>


<table class="custom-table" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr>
      <th>Innovation</th>
      <th>Description</th>
      <th>Observable Feature</th>
      <th>Policy Influence?</th>
      <th>Source</th>
      <th>Attribution</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Mesh size adjustment</td>
      <td>The government accepted the recommendation for an allowable mesh size of 6.5 cm for Hilsa gillnets.</td>
      <td>Adoption of mesh size standards.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Brood Hilsa ban</td>
      <td>The government extended the brood Hilsa ban from 11 to 22 days, based on Worldfish recommendations.</td>
      <td>Lengthened ban period during breeding season.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Marine Protected Area</td>
      <td>The creation of the Nijhum Dwip Marine Reserve was successfully advocated as a new MPA.</td>
      <td>Declaration of Nijhum Dwip as an MPA.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Hilsa sanctuary expansion</td>
      <td>Establishment of a sixth Hilsa sanctuary, as recommended by Worldfish</td>
      <td>Recognition of the sixth Hilsa sanctuary.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Regulatory adjustments</td>
      <td>Contributions to fine-tuning MoFL regulations for the 2019 Marine Fishing Ban, including timing.</td>
      <td>Regulatory changes in fishing ban period.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Hilsa Fisheries Management Action Plan</td>
      <td>Assistance in revising the HFMAP to enhance its effectiveness.</td>
      <td>Updated HFMAP with new strategies.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>Marine Fisheries Act (2018)</td>
      <td>Supported the development of the Marine Fisheries Act for sustainable fisheries management.</td>
      <td>Passage of the Marine Fisheries Act (2018).</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>National Fish Health Management Strategy</td>
      <td>Played a key role in designing the NFHMSB to improve fish health practices.</td>
      <td>Launch of the National Fish Health Management Strategy.</td>
      <td>Yes</td>
      <td>WorldFish</td>
      <td>Medium</td>
    </tr>
  </tbody>
</table>
