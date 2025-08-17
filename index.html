<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Parallax Gallery</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    .gallery-track {
      position: fixed;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 0.25rem;
      padding: 0.25rem;
      will-change: transform;
    }

    .card {
      height: 400px;
      overflow: hidden;
    }

    .card .card-image-wrapper {
      height: 135%;
      will-change: transform;
    }

    .card img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    @media (max-width: 800px) {
      .gallery-track {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (max-width: 550px) {
      .gallery-track {
        grid-template-columns: repeat(1, 1fr);
      }
    }
  </style>
</head>
<body>
  <main class="gallery">
    <div class="gallery-track">
      <div class="card">
        <div class="card-image-wrapper">
          <img src="https://images.unsplash.com/photo-1607419726991-5fc7e74cda67?q=80&w=2487&auto=format&fit=crop">
        </div>
      </div>
      <div class="card">
        <div class="card-image-wrapper">
          <img src="https://images.unsplash.com/photo-1601042879364-f3947d3f9c16?q=80&w=2487&auto=format&fit=crop">
        </div>
      </div>
      <div class="card">
        <div class="card-image-wrapper">
          <img src="https://images.unsplash.com/photo-1536098561742-ca998e48cbcc?q=80&w=2272&auto=format&fit=crop">
        </div>
      </div>
      <div class="card">
        <div class="card-image-wrapper">
          <img src="https://images.unsplash.com/photo-1514439827219-9137a0b99245?q=80&w=2487&auto=format&fit=crop">
        </div>
      </div>
      <div class="card">
        <div class="card-image-wrapper">
          <img src="https://images.unsplash.com/photo-1525790935716-36a6c45ad067?q=80&w=2487&auto=format&fit=crop">
        </div>
      </div>
      <!-- add more cards as needed -->
    </div>
  </main>

  <script>
    const gallery = document.querySelector('.gallery');
    const track = document.querySelector('.gallery-track');
    const cards = document.querySelectorAll('.card');
    const easing = 0.05;
    let startY = 0;
    let endY = 0;
    let raf;

    const lerp = (start, end, t) => start * (1 - t) + end * t;

    function updateScroll() {
      startY = lerp(startY, endY, easing);
      gallery.style.height = `${track.clientHeight}px`;
      track.style.transform = `translateY(-${startY}px)`;
      activateParallax();
      raf = requestAnimationFrame(updateScroll);
      if (startY.toFixed(1) === window.scrollY.toFixed(1)) cancelAnimationFrame(raf);
    }

    function startScroll() {
      endY = window.scrollY;
      cancelAnimationFrame(raf);
      raf = requestAnimationFrame(updateScroll);
    }

    function parallax(card) {
      const wrapper = card.querySelector('.card-image-wrapper');
      const diff = card.offsetHeight - wrapper.offsetHeight;
      const { top } = card.getBoundingClientRect();
      const progress = top / window.innerHeight;
      const yPos = diff * progress;
      wrapper.style.transform = `translateY(${yPos}px)`;
    }

    const activateParallax = () => cards.forEach(parallax);

    function init() {
      activateParallax();
      startScroll();
    }

    window.addEventListener('load', updateScroll, false);
    window.addEventListener('scroll', init, false);
    window.addEventListener('resize', updateScroll, false);
  </script>
</body>
</html>
