---
title: Nouvelles
menu: main
---

<style>
/* === Styles généraux === */
body { font-family: sans-serif; background:#f9f9f9; color:#050505; margin:0; padding:0; }
h1,h2 { color:#1447E6; margin-bottom:0.5rem; }

/* === Carousel === */
.carousel-container { overflow:hidden; width:100%; margin:1rem 0; position:relative; }
.carousel-track { display:flex; transition:transform 0.5s ease-in-out; }
.carousel-item { flex:0 0 100%; box-sizing:border-box; background:#fff; border-radius:10px; box-shadow:0 2px 6px rgba(0,0,0,0.2); padding:1rem; text-align:center; }
.carousel-item img { width:100%; height:250px; object-fit:cover; border-radius:10px; }
.btn-more { display:inline-block; margin-top:0.5rem; padding:0.5rem 1rem; background:#1447E6; color:#fff; border-radius:5px; text-decoration:none; }
.btn-more:hover { background:#0f3660; }

/* === Liste des 10 infos === */
.news-list { display:flex; flex-direction:column; gap:1rem; margin-top:2rem; }
.news-card { display:flex; flex-direction:row; gap:1rem; background:#fff; border-radius:10px; overflow:hidden; box-shadow:0 2px 6px rgba(0,0,0,0.2); }
.news-card img { width:40%; object-fit:cover; }
.news-card-content { padding:1rem; }
.news-card-content h4 { margin:0.5rem 0; font-size:1rem; }
.news-card-content p { font-size:0.875rem; margin:0.25rem 0; }

@media(max-width:768px){
  .news-card { flex-direction:column; }
  .news-card img { width:100%; height:200px; }
}
</style>

# Toutes les publications

## 🏆 Les 5 dernières nouvelles (Carousel)

<div class="carousel-container">
  <div class="carousel-track">
    <div class="carousel-item" id="news1">
      <img src="https://picsum.photos/id/1050/600/400" alt="Nouvelle 1">
      <h3>IA optimise chaîne logistique</h3>
      <p>Algorithme prédit demandes globales.</p>
      <a href="#news-list1" class="btn-more">Voir détails</a>
    </div>
    <div class="carousel-item" id="news2">
      <img src="https://picsum.photos/id/1051/600/400" alt="Nouvelle 2">
      <h3>Puces 2 nm révolutionnaires dévoilées</h3>
      <p>Métaux avancés pour semi‑conducteurs.</p>
      <a href="#news-list2" class="btn-more">Voir détails</a>
    </div>
    <div class="carousel-item" id="news3">
      <img src="https://picsum.photos/id/1052/600/400" alt="Nouvelle 3">
      <h3>Quantum computing franchit cap 1000 q‑bits</h3>
      <p>Nouvelle architecture permet stabilité.</p>
      <a href="#news-list3" class="btn-more">Voir détails</a>
    </div>
    <div class="carousel-item" id="news4">
      <img src="https://picsum.photos/id/1053/600/400" alt="Nouvelle 4">
      <h3>Edge AI embarquée dans objets IoT</h3>
      <p>Systèmes autonomes sans cloud.</p>
      <a href="#news-list4" class="btn-more">Voir détails</a>
    </div>
    <div class="carousel-item" id="news5">
      <img src="https://picsum.photos/id/1054/600/400" alt="Nouvelle 5">
      <h3>Cyber‑sécurité proactive par IA</h3>
      <p>Menaces détectées avant intrusions.</p>
      <a href="#news-list5" class="btn-more">Voir détails</a>
    </div>
  </div>
</div>

## 📰 Autres nouvelles récentes (10 infos)

<div class="news-list">
  <div class="news-card" id="news-list1">
    <img src="https://picsum.photos/id/1060/400/250" alt="Info 1">
    <div class="news-card-content">
      <h4>Info 1 – 5G avancée déployée</h4>
      <p>Réseaux ultra‑rapides pour télécommunications mondiales.</p>
    </div>
  </div>
  <div class="news-card" id="news-list2">
    <img src="https://picsum.photos/id/1061/400/250" alt="Info 2">
    <div class="news-card-content">
      <h4>Info 2 – Batteries état solide</h4>
      <p>Autonomie double pour véhicules électriques.</p>
    </div>
  </div>
  <div class="news-card" id="news-list3">
    <img src="https://picsum.photos/id/1062/400/250" alt="Info 3">
    <div class="news-card-content">
      <h4>Info 3 – Réalité augmentée mobile</h4>
      <p>Interface naturelle pour applications quotidiennes.</p>
    </div>
  </div>
  <div class="news-card" id="news-list4">
    <img src="https://picsum.photos/id/1063/400/250" alt="Info 4">
    <div class="news-card-content">
      <h4>Info 4 – Robots collaboratifs légers</h4>
      <p>Usines 4.0 adoptent machines intelligentes compactes.</p>
    </div>
  </div>
  <div class="news-card" id="news-list5">
    <img src="https://picsum.photos/id/1064/400/250" alt="Info 5">
    <div class="news-card-content">
      <h4>Info 5 – Stockage hydrogène moléculaire</h4>
      <p>Capacité énergétique révolutionne transports.</p>
    </div>
  </div>
  <div class="news-card" id="news-list6">
    <img src="https://picsum.photos/id/1065/400/250" alt="Info 6">
    <div class="news-card-content">
      <h4>Info 6 – Satellites low‑cost constellation</h4>
      <p>Internet mondial accessible partout.</p>
    </div>
  </div>
  <div class="news-card" id="news-list7">
    <img src="https://picsum.photos/id/1066/400/250" alt="Info 7">
    <div class="news-card-content">
      <h4>Info 7 – IA éthique régulée globalement</h4>
      <p>Normes internationales pour algorithmes.</p>
    </div>
  </div>
  <div class="news-card" id="news-list8">
    <img src="https://picsum.photos/id/1067/400/250" alt="Info 8">
    <div class="news-card-content">
      <h4>Info 8 – Transistors 1‑nm annoncés</h4>
      <p>Fabrication ultra‑miniature devient tangible.</p>
    </div>
  </div>
  <div class="news-card" id="news-list9">
    <img src="https://picsum.photos/id/1068/400/250" alt="Info 9">
    <div class="news-card-content">
      <h4>Info 9 – Cloud quantique hybride</h4>
      <p>Combinaison informatique classique et quantique.</p>
    </div>
  </div>
  <div class="news-card" id="news-list10">
    <img src="https://picsum.photos/id/1069/400/250" alt="Info 10">
    <div class="news-card-content">
      <h4>Info 10 – Interfaces cerveau‑machine rapides</h4>
      <p>Connexion directe esprit‑ordinateur en essai.</p>
    </div>
  </div>
</div>

<script>
// Carousel automatique
const track = document.querySelector('.carousel-track');
let index = 0;
const total = track.children.length;

function nextSlide() {
  index = (index + 1) % total;
  track.style.transform = `translateX(-${index * 100}%)`;
}

setInterval(nextSlide, 4000);
</script>
