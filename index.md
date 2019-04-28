---
title: "SPF Projects"
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: engine.jpg
excerpt: "blah"
intro: 
  - excerpt: 'SPF projects below.'
feature_row:
  - image_path: bayes.jpg
    image_caption: "Bayesian"
    alt: "Aerobayes"
    title: "Bayesian spatial models from engine sensor measurements"
    excerpt: "Understanding aeroengine aerothermodynamics by generating spatial fields of temperature and pressure based on sensor measurements."
    btn_label: "Learn more"
    btn_class: "btn--primary"
    url: "/bayesian-spatial-models-from-engine-sensor-measurements.html"
  - image_path: dr.jpg
    alt: "Subspace-based dimension reduction"
    title: "Dimension reduction in blade aerodynamics"
    excerpt: "Finding lower-dimensional representations of high-dimensional design spaces for the aerodynamic design and manufacturing of aeroengine blades."
    url: "/dimension-reduction-in-blade-aerodynamics.html"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: polynomials.jpg
    title: "Polynomial approximations for machine learning"
    excerpt: "Leveraging polynomial approximations via least squares, compressive sensing and numerical integration rules for learning."
    btn_label: "Explore project"
    btn_class: "btn--primary"
    url: https://www.effective-quadratures.org
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include paginator.html %}
