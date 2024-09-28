---
layout: default
title: Animation
permalink: /hobby/animation/
---

<h1>Animation</h1>

<p>I am an anime enthusiast, enjoying a wide range of genres. Anime brings creativity, emotion, and storytelling that deeply resonates with me. Anime has always been a part of my life.</p>

<p>Here are some of my favorite anime:</p>

<div class="anime-list">
  <div class="anime-item">
    <img src="/hobby_images/anime_1.jpg" alt="冴えないヒロインの育て方 fine" />
    <p>Your Name</p>
  </div>

  <div class="anime-item">
    <img src="/hobby_images/anime_2.jpg" alt="Lupin the 3rd Part IV: The Italian Adventure" />
    <p>A Silent Voice</p>
  </div>

  <div class="anime-item">
    <img src="/hobby_images/anime_3.jpg" alt="ブレンド・S" />
    <p>Attack on Titan</p>
  </div>

  <div class="anime-item">
    <img src="/hobby_images/anime_4.jpg" alt="My Hero Academia" />
    <p>My Hero Academia</p>
  </div>
</div>

<!-- 返回 Hobby 按钮 -->
<div class="back-to-hobby">
  <a href="/hobby" class="button">← Back to Hobby</a>
</div>

<!-- 自定义样式 -->
<style>
  h1 {
    font-size: 1.5em;
    margin-bottom: 20px;
    text-align: left;
  }

  p {
    font-size: 0.9em;
    line-height: 1.4;
    color: #555;
    margin-bottom: 20px;
  }

  .anime-list {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    margin-top: 20px;
  }

  .anime-item {
    text-align: center;
  }

  .anime-item img {
    width: 100%;
    max-width: 200px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .anime-item p {
    font-size: 0.9em;
    margin-top: 10px;
    color: #555;
  }

  /* 返回 Hobby 按钮样式 */
  .back-to-hobby {
    text-align: center;
    margin-top: 40px;
  }

  .back-to-hobby .button {
    display: inline-block;
    padding: 8px 16px;
    font-size: 0.9em;
    color: #333;
    background-color: transparent;
    border: 1px solid #333;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease, color 0.3s ease;
  }

  .back-to-hobby .button:hover {
    background-color: #f0f0f0;
    color: #000;
  }
</style>
