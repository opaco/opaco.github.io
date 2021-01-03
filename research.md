---
layout: default
title: "Research"
permalink: /research/
---
<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
}
</style>
  
# Research


(maybe hide each title in a clickable list)

<button class="collapsible"> Slab simluations of galactic disk 1 </button>
<div class="content">
  <p>
 ## Slab simluations of galactic disk
In principle, it is possible to set up a global simluation of a disk galaxy, including the dense disk and the surrounding medium, and test how different physics models change the resulting galaxy properties. However, this approach is computationally expensive, especially when investigating new physics. Instead, we can use a thin (2x2 kpc area) elongated (40 kpc tall) passing through the galactic disk. I conducted simulations using the magnetohydrodynamic (MHD) code FLASH. The simulations use a two-fluid coupled cosmic ray-MHD model, as shown in [insert paper here].
  </p>
</div>

### Simulations and observational predictions

The connection between a simulation galaxy and actual observed data is an active area of research.


### Cosmic rays, and turbulence

Cosmic rays are high-energy charged particles, primarily single protons and electrons, that are found across the galaxy. They are accelerated in supernova shocks to releavistic energies. Cosmic rays can impart energy and momentum into the gas as well as act as an additional source of pressure. The cosmic ray energy density in the interstellar medium (ISM) is similar to the turbulent and magnetic components of energy, which suggests that they may play a role determining galactic structure. Prior to my work, there were numerous galaxy models, both analytical and computational, that included cosmic rays in increasingly more detail. These models assume that cosmic ray transport is spatially and temporally constant. The turbulent and multiphase ISM can influence how cosmic rays are transported throughout the galaxy. [insert paper here] introduced faster cosmic ray tranport within the cold, neutral medium, because cosmic rays couple less with neutral gas.  Cosmic ray transport is important because faster cosmic rays can escape dense gas more quickly and interact with the rest of the galaxy.

My work [insert link here] implments a model[Lazarian link here]  of cosmic ray tranpsort that varies with the turbulent properies of the ISM.  Within the streaming model of cosmic ray transport, as cosmic rays propagate through the ISM they exicte Alfven waves and these Alfven waves subsequently confine the bulk cosmic ray motion to the Alfven speed. Turbulence dissipates these confining waves (i.e turbulent damping), allowing cosmic rays to move faster relative to the gas. 
[insert image here]

## Influence of galactic stellar radiation field in a galaxy

### Influence of stellar radiation over redshift and halo mass

### Simulations and observational predictions?




## Machine learning and numerics



<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>




