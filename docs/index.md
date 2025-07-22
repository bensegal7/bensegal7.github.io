---
layout: default
title: Ben's Portfolio Homepage
---

<style>
  .container {
    max-width: 800px;
    margin: auto;
    padding: 2rem;
    font-family: 'Segoe UI', sans-serif;
  }
  h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    color: #2c3e50;
  }
  p {
    font-size: 1.1rem;
    color: #555;
  }
  .nav-links {
    margin-top: 2rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.2rem;
  }
  .nav-links a {
    display: block;
    padding: 1rem;
    text-decoration: none;
    color: #2c3e50;
    background: #f5f5f5;
    border-radius: 8px;
    transition: background 0.3s;
    font-weight: 500;
  }
  .nav-links a:hover {
    background: #e0e0e0;
  }
</style>

<div class="container">
  <h1>Welcome to my site.</h1>
  <p>
    My name is Ben! I'm a recent MBA graduate with experience in data analytics and finance.
  </p>
  <p>
    Explore my projects, learn more about my background, or download my resume below.
  </p>

  <div class="nav-links">
    <a href="./projects/"> Projects.</a>
    <a href="./experiences.md"> Experiences.</a>
    <a href="./pictures.md"> Pictures.</a>
    <a href="./projects/BasResume.pdf"> Download my Resume.</a>
  </div>
</div>
