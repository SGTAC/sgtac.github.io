---
layout: page
title: Venue
permalink: /venue/
---

The workshop will be held at the premises of **InnoRenew CoE** in Izola, Slovenia. 

Known for its sustainable, cutting-edge wooden architecture, the institute provides an inspiring academic setting right by the Mediterranean sea.

<div class="slider-container">
  <div class="slider">
    <div class="slides" id="slides">
      <div class="slide">
        <img src="{{ '/assets/photo1.jpg' | relative_url }}" alt="InnoRenew Building Interior">
      </div>
      <div class="slide">
        <img src="{{ '/assets/photo2.jpg' | relative_url }}" alt="InnoRenew Building Interior">
      </div>
      <div class="slide">
        <img src="{{ '/assets/photo3.jpg' | relative_url }}" alt="Izola Coastline">
      </div>
    </div>
  </div>
  
  <button class="prev-btn" onclick="moveSlide(-1)">&#10094;</button>
  <button class="next-btn" onclick="moveSlide(1)">&#10095;</button>
</div>

<style>
  .slider-container {
    position: relative;
    max-width: 100%;
    margin: 2rem auto;
    overflow: hidden;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  }
  .slider {
    display: flex;
  }
  .slides {
    display: flex;
    transition: transform 0.5s ease-in-out;
    width: 100%;
  }
  .slide {
    min-width: 100%;
    position: relative;
  }
  .slide img {
    width: 100%;
    height: auto;
    display: block;
    object-fit: cover;
    max-height: 450px;
  }
  .caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    padding: 10px;
    text-align: center;
    font-size: 0.9rem;
  }
  .prev-btn, .next-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: rgba(0, 0, 0, 0.5);
    color: white;
    border: none;
    padding: 12px;
    cursor: pointer;
    font-size: 18px;
    border-radius: 50%;
    width: 45px;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.3s;
  }
  .prev-btn:hover, .next-btn:hover {
    background: rgba(0, 0, 0, 0.8);
  }
  .prev-btn { left: 15px; }
  .next-btn { right: 15px; }
</style>

<script>
  let currentIndex = 0;
  function moveSlide(direction) {
    const slidesContainer = document.getElementById('slides');
    const totalSlides = slidesContainer.children.length;
    currentIndex = (currentIndex + direction + totalSlides) % totalSlides;
    slidesContainer.style.transform = `translateX(-${currentIndex * 100}%)`;
  }
</script>

***

* 🌐 **Website:** [InnoRenew CoE](https://innorenew.eu/)
* 📍 **Location:** [View on Google Maps](https://maps.app.goo.gl/gYHERJwVQPb1ByRy6)