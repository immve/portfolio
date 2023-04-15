{% extends "custom.html" %}

{% block content %}
<div class="container">
  <div class="header">
    <div class="header-logo">Your Logo</div>
    <nav class="header-nav">
      <a href="#">Home</a>
      <a href="#">Features</a>
      <a href="#">Pricing</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </div>

  <div class="hero">
    <div class="hero-text">
      <h1>Impressive Title</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vitae lectus ac purus tristique viverra vitae nec tellus.</p>
    </div>
    <div class="hero-image">
      <img src="path/to/your/image.jpg" alt="Hero image">
    </div>
  </div>

  <div class="features">
    <div class="feature">
      <h3>Feature 1</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque auctor odio neque.</p>
    </div>
    <div class="feature">
      <h3>Feature 2</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque auctor odio neque.</p>
    </div>
    <div class="feature">
      <h3>Feature 3</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque auctor odio neque.</p>
    </div>
  </div>
</div>
{% endblock %}
