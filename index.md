---
layout: home
title: "Home"
---

I defended my Phd thesis entitled "Nonparametric inference for convolution models" supervised by Jan Johannes and Fabienne Comte on the 4th December 2025.

I am interested in nonparametric inference, inference for inverse problems, adaptive testing and quadratic functional estimation for multiplicative convolution and estimation of convoluted densities.

<div class="row g-5 mb-5">
  <div>
    <h3 class="fw-bold border-bottom pb-3 mb-5">Contact</h3>
    {% for contact in site.data.settings.contacts %}
    <div class="row g-5 mb-5">
      <div class="col-md-6">
        <h4>{{ contact.name }}</h4>
        {{ contact.department }}</p>
        <p>{{ contact.institution }} | {{ contact.institution_address }}</p>
        <p>Phone: {{ contact.phone }}</p>
        <p>Email: {{ contact.email }}</p>
        <p>Office: {{ contact.office }}</p>
      </div>
      <div class="col-md-6">
        
      </div>
    </div>
    {% endfor %}
  </div>
</div>
