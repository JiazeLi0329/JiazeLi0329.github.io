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
    <p>冴えないヒロインの育て方 fine</p>
  </div>

  <div class="anime-item">
    <img src="/hobby_images/anime_2.jpg" alt="Lupin the 3rd Part IV: The Italian Adventure" />
    <p>Lupin the 3rd Part IV: The Italian Adventure</p>
  </div>

  <div class="anime-item">
    <img src="/hobby_images/anime_3.jpg" alt="ブレンド・S" />
    <p>ブレンド・S</p>
  </div>

  <div class="anime-item">
    <img src="/hobby_images/anime_4.jpg" alt="異世界食堂２" />
    <p>異世界食堂２</p>
  </div>
</div>

<h2>My Favorite Character: 加藤惠</h2>
<p>One of my all-time favorite anime characters is 加藤惠 from the series “冴えない彼女の育てかた (Saekano: How to Raise a Boring Girlfriend).” Her calm, reserved nature and her unexpected charm make her stand out as one of the best characters in anime for me.</p>

<!-- 加藤惠的九张图片展示 -->
<div class="katou-gallery">
  <div class="katou-item">
    <img src="/hobby_images/katou_1.jpg" alt="Katou Megumi 1" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_2.jpg" alt="Katou Megumi 2" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_3.jpg" alt="Katou Megumi 3" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_4.jpg" alt="Katou Megumi 4" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_5.jpg" alt="Katou Megumi 5" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_6.jpg" alt="Katou Megumi 6" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_7.jpg" alt="Katou Megumi 7" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_8.jpg" alt="Katou Megumi 8" />
  </div>
  <div class="katou-item">
    <img src="/hobby_images/katou_9.jpg" alt="Katou Megumi 9" />
  </div>
</div>

<!-- 返回 Hobby 按钮 -->
<div class="back-to-hobby">
  <a href="/hobby" class="button">← Back to Hobby</a>
</div>

<!-- 自定义样式 -->
<style>
  h1, h2 {
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

  .anime-list, .katou-gallery {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Anime 两列布局 */
    gap: 20px;
    margin-top: 20px;
  }

  /* 保证图片大小一致 */
  .anime-item img, .katou-item img {
    width: 100%;
    max-width: 200px;
    height: 300px; /* 统一高度 */
    object-fit: cover; /* 保持图片比例 */
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .anime-item p {
    font-size: 0.9em;
    margin-top: 10px;
    color: #555;
  }

  .katou-gallery {
    grid-template-columns: repeat(3, 1fr); /* 加藤惠图片三列布局 */
    gap: 10px; /* 更小的图片间距 */
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

