---
layout: page
title: Venue
permalink: /venue/
---

The workshop will be held at the premises of the University of Primorska, at **InnoRenew CoE** in Izola, Slovenia. 

Known for its sustainable, cutting-edge wooden architecture, the institute provides an inspiring academic setting right by the Adriatic Sea.

<div class="slider-container">
  <div class="slider">
    <div class="slides" id="slides">
      <div class="slide">
        <img src="{{ '/assets/photo1.jpg' | relative_url }}" alt="InnoRenew Building Interior">
        <p class="caption">InnoRenew CoE Interior (photo: Miran Kambič)</p>
      </div>
      <div class="slide">
        <img src="{{ '/assets/photo2.jpg' | relative_url }}" alt="InnoRenew Building Interior">
        <p class="caption">InnoRenew CoE Exterior (photo: Miran Kambič)</p>
      </div>
      <div class="slide">
        <img src="{{ '/assets/photo3.jpg' | relative_url }}" alt="Izola Coastline">
        <p class="caption">Izola (photo: Luka Kotnik, slovenia.info)</p>
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


***

## Accommodations and Travel

### Hotels in Izola
* [Hotel Belvedere (Cliff and Villa)](http://www.belvedere.si/en): Dobrava 1a, 6310 Izola
* [Hotel Haliaetum](https://www.hoteli-bernardin.si/si/namestitve/izola/hotel-haliaetum): Morova ulica 6a, 6310 Izola
* [San Simon Resort](https://www.hoteli-bernardin.si/en/accommodations/san-simon-resort): Izola (multiple locations)
* [Hotel Delfin](https://www.hotel-delfin.si/en/hotel-delfin-2/): Tomažičeva 10, 6310 Izola
* [Hotel Marina](https://hotelmarina.si/en/hotel-3/): Veliki trg 11, 6310 Izola
* [Hotel Keltika](https://www.hotel-izola.si/): Cesta v Jagodje 1, 6310 Izola
* [DeGrassi Boutique Garni Hotel](https://degrassihotel.si/): Drevored 1. maja 9, 6310 Izola

### Airports
* [Trieste Airport](https://triesteairport.it/en/) (TRS) – 55-minute drive from Izola
* [Ljubljana Airport](https://www.fraport-slovenija.si/en/Main/) (LJU) – 1 hour 20-minute drive from Izola
* [Venice Marco Polo Airport](https://www.veniceairport.it/en/) (VCE) – 2-hour drive from Izola
* [Treviso Airport](http://www.trevisoairport.it/en/) (TSF) – 2-hour drive from Izola
* [Zagreb Airport](http://www.zagreb-airport.hr/en) (ZAG) – 2 hour 30-minute drive from Izola

### Shuttle Service
The easiest way to travel to Izola from the airports listed above is to take a shuttle service like [GoOpti transport](https://www.goopti.com/en/transfers). Reservations for transfers can be made directly to your hotel. Prices are significantly lower if the shuttle is booked well in advance (1–2 months).

### Bus or Train
* **Bus:** Travel by [bus](https://www.ap-ljubljana.si/en/) to Izola is possible. Once in Izola, local [public transportation](https://arriva.si/) is available to move around the town.
* **Train:** You can travel by train from most European countries via connections to Koper (Slovenia), Trieste (Italy), or Ljubljana (Slovenia). From these railway stations, a short bus transfer or shuttle is required to reach Izola.