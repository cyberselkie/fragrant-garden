---
title: Home
summary: >-
  homepage & gallery
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@shoelace-style/shoelace@2.3.0/dist/themes/light.css" />
<script type="module" src="https://cdn.jsdelivr.net/npm/@shoelace-style/shoelace@2.3.0/dist/shoelace-autoloader.js"></script>
<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>

<sl-carousel class="carousel-thumbnails" navigation loop>
  <sl-carousel-item>
    <img
      alt="A woman with luna moth wings holding a sword."
      src="images/lunamoth2.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A man with long hair, covered in dragonflies."
      src="images/dragonfly.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A woman covered in luna moths."
      src="images/luna moth.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A girl running a chainsaw through a large stuffed bear, with blood and gore spilling out."
      src="images/dccover.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A man with crane wings holding a sword above a glowing pool."
      src="images/crane.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="Six magical girls surrounding the text 'Pretty Force! Battle Transformation'"
      src="images/prettyforce cover.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A painting of a man with feathery ears and a cyberpunk neck and jaw piece."
      src="images/pseudoangel.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A man shooting an angel in the head surrounded by pastel clouds."
      src="images/the shot clouds v2.jpg"
    />
  </sl-carousel-item>

  <sl-carousel-item>
    <img
      alt="A fairy with a sword rendered in a pixelized, green retro screen style."
      src="images/THING2.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="Two women on horseback under the moonlight, one in full armor and drawing a revolver, the other in western wear and drawing a sword."
      src="images/western.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="Horned purple man sitting on a throne in bright light, with black butterflies and crumbling ruins around him."
      src="images/florian.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="Horned purple man in two sketches showing off similar outfits."
      src="images/fashion.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="Red horned man in a watercolor style surrounded by stars."
      src="images/lux.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="A 5 x 5 hexmap."
      src="images/PRETTYFORCE MAP.jpg"
    />
  </sl-carousel-item>

  <sl-carousel-item>
    <img
      alt="woman getting eaten by crows."
      src="images/songbirds 3e cover jpg.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="cowboy on a motorcycle, with a bazooka."
      src="images/cowboy twt.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="cowboy on a motorcycle, with a pistol."
      src="images/cowboy 2 twt.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="dragon woman holding a censer over a background of loose magical papers."
      src="images/mirza.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="necromancer woman, naked, holding a skull."
      src="images/necromancer.jpg"
    />
  </sl-carousel-item>
  <sl-carousel-item>
    <img
      alt="a knight in a red embroidered cloak."
      src="images/knight.jpg"
    />
  </sl-carousel-item>
</sl-carousel>

<div class="thumbnails">
  <div class="thumbnails__scroller">
    <img alt="Thumbnail by 1" class="thumbnails__image active" src="images/lunamoth2.jpg" />
    <img alt="Thumbnail by 3" class="thumbnails__image" src="images/dragonfly.jpg" />
    <img alt="Thumbnail by 4" class="thumbnails__image" src="images/luna moth.jpg" />
    <img alt="Thumbnail by 5" class="thumbnails__image" src="images/dccover.jpg" />
    <img alt="Thumbnail by 6" class="thumbnails__image" src="images/crane.jpg" />
    <img alt="Thumbnail by 7" class="thumbnails__image" src="images/prettyforce cover.jpg" />
    <img alt="Thumbnail by 8" class="thumbnails__image" src="images/pseudoangel.jpg" />
    <img alt="Thumbnail by 10" class="thumbnails__image" src="images/the shot clouds v2.jpg" />
    <img alt="Thumbnail by 12" class="thumbnails__image" src="images/THING2.jpg" />
    <img alt="Thumbnail by 13" class="thumbnails__image" src="images/western.jpg" />
    <img alt="Thumbnail by 14" class="thumbnails__image" src="images/florian.jpg" />
    <img alt="Thumbnail by 15" class="thumbnails__image" src="images/fashion.jpg" />
    <img alt="Thumbnail by 16" class="thumbnails__image" src="images/lux.jpg" />
    <img alt="Thumbnail by 17" class="thumbnails__image" src="images/PRETTYFORCE MAP.jpg" />
    <img alt="Thumbnail by 19" class="thumbnails__image" src="images/songbirds 3e cover jpg.jpg" />
    <img alt="Thumbnail by 20" class="thumbnails__image" src="images/cowboy twt.jpg" />
    <img alt="Thumbnail by 21" class="thumbnails__image" src="images/cowboy 2 twt.jpg" />
    <img alt="Thumbnail by 22" class="thumbnails__image" src="images/mirza.jpg" />
    <img alt="Thumbnail by 23" class="thumbnails__image" src="images/necromancer.jpg" />
    <img alt="Thumbnail by 24" class="thumbnails__image" src="images/knight.jpg" />
  </div>
</div>

<style>
  sl-carousel {
    min-height: 800px;
}

@media only screen and (max-width: 600px) {
    sl-carousel {
    min-height: 600px;
    }
  }
  .carousel-thumbnails {
    --slide-aspect-ratio: 3 / 2;
  }

  .thumbnails {
    display: flex;
    justify-content: center;
  }

  .thumbnails__scroller {
    display: flex;
    gap: var(--sl-spacing-small);
    overflow-x: auto;
    scrollbar-width: none;
    scroll-behavior: smooth;
    scroll-padding: var(--sl-spacing-small);
  }

  .thumbnails__scroller::-webkit-scrollbar {
    display: none;
  }

  .thumbnails__image {
    width: 64px;
    height: 64px;
    object-fit: cover;

    opacity: 0.3;
    will-change: opacity;
    transition: 250ms opacity;

    cursor: pointer;
  }

  .thumbnails__image.active {
    opacity: 1;
  }
</style>

<script>
  {
    const carousel = document.querySelector('.carousel-thumbnails');
    const scroller = document.querySelector('.thumbnails__scroller');
    const thumbnails = document.querySelectorAll('.thumbnails__image');

    scroller.addEventListener('click', e => {
      const target = e.target;

      if (target.matches('.thumbnails__image')) {
        const index = [...thumbnails].indexOf(target);
        carousel.goToSlide(index);
      }
    });

    carousel.addEventListener('sl-slide-change', e => {
      const slideIndex = e.detail.index;

      [...thumbnails].forEach((thumb, i) => {
        thumb.classList.toggle('active', i === slideIndex);
        if (i === slideIndex) {
          thumb.scrollIntoView({
            block: 'nearest'
          });
        }
      });
    });
  }
</script>
