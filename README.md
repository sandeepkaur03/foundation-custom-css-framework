# Introduction

We selected Foundation as our project topic. We created a custom css framework based on Foundation. It is a CSS framework that is easy to use and provides a consistent design.

add the line below to your project to use this custom framework.
<link rel="stylesheet" href="dist/css/foundation.css">

Examples:

<button class="button">Primary Button</button>
<button class="button secondary">Secondary Button</button>
<button class="button success">Success Button</button>

<input type="text" class="input" placeholder="Input field">

<div class="row">
  <div class="column small-12 medium-6 large-4">Column</div>
  <div class="column small-12 medium-6 large-4">Column</div>
  <div class="column small-12 medium-6 large-4">Column</div>
</div>

<table class="table">
  <thead>
    <tr>
      <th>Header</th>
      <th>Header</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data</td>
      <td>Data</td>
    </tr>
  </tbody>
</table>

<div class="card">
  <h3>Card Title</h3>
  <p>Card content goes here.</p>
</div>

Customize the framework by modifying the variables in src/scss/settings/_variables.scss.
