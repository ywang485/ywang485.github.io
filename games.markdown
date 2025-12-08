---
layout: single
author_profile: true
title: Games
permalink: /games/
---

<style>
.games-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
  margin: 2rem 0;
}

.game-card {
  border: 1px solid #333;
  border-radius: 8px;
  padding: 1.5rem;
  background: #1a1a1a;
  transition: transform 0.2s ease;
}

.game-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

.game-title {
  font-size: 1rem;
  font-weight: bold;
  margin-bottom: 1rem;
  color: #fff;
  text-decoration: none;
}

.game-title:hover {
  color: #ff6b6b;
  text-decoration: none;
}

.game-gif {
  width: 100%;
  height: 200px;
  background: #333;
  border-radius: 4px;
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #888;
  font-style: italic;
}

.game-description {
  margin-bottom: 1rem;
  line-height: 1.5;
  color: #ccc;
}

.game-link {
  padding: 0.5rem 1rem;
  font-size: 0.9rem;
}

@media (max-width: 768px) {
  .games-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
}
</style>

I make games for fun. Most of my games are short and made for game jams in 48 hours.

They tend to be experimental games more about conveying some message through interaction mechanism, not necessarily fun to play.

<div class="games-grid">
  <div class="game-card">
    <a class="game-title">Hang in There Until Meetings Are Over</a>
    <div class="game-gif"><img src="assets/images/HITUMAO.gif" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;"></div>
    <div class="game-description">
      A game about social anxiety and zoom fatigue <a href="https://junjunlowpoly.itch.io/hanging-in-there-until-meetings-are-over"> [itch]</a> <a href="https://ldjam.com/events/ludum-dare/49/no-collapse-until-meetings-are-over">[Ludum Dare]</a>
    </div>
</div>

  <div class="game-card">
    <a class="game-title">Scientific Research is Gambling with You Life</a>
    <div class="game-gif"><img src="assets/images/srigwyl.webp" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;"></div>
    <div class="game-description">
      A monopoly style game but instead of investing in real-estate with money you invest your life in establishing theories. <a href="https://junjunlowpoly.itch.io/scientific-research-is-gambling-with-you-rlife"> [itch] </a>
    </div>
  </div>

  <div class="game-card">
    <a class="game-title">Clean Food Clean Mind</a>
    <div class="game-gif"><img src="assets/images/cfcm.gif" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;"></div>
    <div class="game-description">
      A weight losing simulator with puzzle fighter like mechanism. Your goal is to finish a workout plan before you consume too much calories. The key is to keep your food and your mind clean! <a href="https://junjunlowpoly.itch.io/cleanfoodcleanmind"> [itch] </a><a href="https://ldjam.com/events/ludum-dare/40/clean-food-clean-mind"> [Ludum Dare] </a>
    </div>
  </div>

  <div class="game-card">
    <a class="game-title">Battery Pack Man</a>
    <div class="game-gif"><img src="assets/images/batterypackman.gif" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;"></div>
    <div class="game-description">
      A small arcade style game where you are the hero who brings solar battery to the field. The goal is to survive.<a href="https://junjunlowpoly.itch.io/batterypackman"> [itch] </a><a href="https://ldjam.com/events/ludum-dare/39/batterypackman"> [Ludum Dare] </a>
    </div>
  </div>

  <div class="game-card">
    <a class="game-title">I didn't do my homwork</a>
    <div class="game-gif"><img src="assets/images/didntdohw.gif" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;"></div>
    <div class="game-description">
      Connect concepts to make excuses for not doing homework. An experiment on narrative planning with Answer Set Programming. <a href="https://junjunlowpoly.itch.io/i-didnt-do-my-homework"> [itch] </a>
    </div>
  </div>

  <div class="game-card">
    <a class="game-title">RNG</a>
    <div class="game-gif"><img src="assets/images/rng.png" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;"></div>
    <div class="game-description">
      In this classical RPG setting, instead of the player, you play as a random number generator in the game and decide what random encounter the player has. You only have very limited options and your goal is to make the (AI) player beats the game before he realizes how repetitive the RPG world is. <a href="https://junjunlowpoly.itch.io/rng"> [itch] </a><a href="https://ldjam.com/events/ludum-dare/38/rng"> [Ludum Dare] </a>
    </div>
  </div>
</div>
