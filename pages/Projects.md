--- 
layout: page
title : Projects
permalink: /Projects/
subtitle: "" 
feature-img: "assets/img/pexels/computer.jpeg"
position: 5
tags: [Page]
---

<style>
  .education-title {
    font-family: sans-serif; /* Font family */
    font-size: 1em;
    color: white;
    font-weight: bold;
  }

  body {
    margin: 0;
    padding: 0px;
    background-color: #cdd2ca; /* Fallback background color */
  }

  .feature-img {
    display: block;
    margin: 0 auto; /* Center the image */
    max-width: 40%; /* Prevent it from exceeding the width of the page */
    height: auto; /* Maintain aspect ratio */
  }

  h1 {
    font-family: Cambria, serif;
    color: white;
    text-align: left;
    margin-bottom: 20px;
  }

  section {
    margin: 0px auto; /* Center the section content */
    padding: 5px;
    max-width: 1100px; /* Set a maximum width for better readability */
  }

  h2 {
    font-family: Cambria, serif;
    font-size: .8em;
    color:#4B9C9C;
    margin-top: 20px;
  }

  ul {
    list-style-type: disc;
    padding-left: 40px;
    margin: 10px 0;
  }

  li {
    margin-bottom: 10px;
    line-height: 1.6;
    font-size: 0.9em;
    font-family: Cambria, serif;
    color: #555;
  }

  ul ul {
    list-style-type: circle;
    margin-left: 20px;
  }
</style>

<!-- Feature Image -->
<img src="assets/img/pexels/back.jpg" class="feature-img" alt="">

<h1 class="education-title"></h1>

<section>
  <h2>Sentiment Analysis using Machine Learning Algorithms</h2>
  <ul>
    <li>Analyzed text data including Mobile Apps, Twitter, Yelp, and product Reviews.</li>
    <li>Trained and evaluated various deep learning and classical machine learning models.</li>
    <li>Achieved sentiment accuracy of 48% (neutral), 71% (negative), and 81% (positive).</li>
  </ul>

  <h2 style="margin-top: 40px;">Automatic Detection of Machine-Generated Text</h2>
  <ul>
    <li>Analyzed web-scraped data (Reviews, Poems, Tweets, News) in English and Dutch.</li>
    <li>Achieved 97% accuracy in detecting machine-generated text using ensemble learning.</li>
    <li>The top-performing classical model surpassed deep learning models by a significant margin.</li>
  </ul>

  <h2 style="margin-top: 40px;">Developing an Age-Appropriate Rating System for Podcasts</h2>
  <ul>
    <li>Developed a topic modeling system for podcasts, integrating BERTopic and LMMs.</li>
    <li>Model directly identifies topics without post-processing, reducing computation time.</li>
    <li>Developed an age rating system for podcasts based on identified topics and subtopics.</li>
  </ul>

  <h2 style="margin-top: 40px;">Evaluating GPT Model Performance Using Perplexity</h2>
  <ul>
    <li>Used a GPT model with GPT2Tokenizer, trained on Christopher Marlowe’s books.</li>
    <li>Evaluated on: TinyShakespeare, a science fiction dataset, and a nonsensical dataset.</li>
    <li>Results of Perplexity scores:
      <ul>
        <li>252 (TinyShakespeare)</li>
        <li>339 (science fiction)</li>
        <li>221,642.7 (nonsense)</li>
      </ul>
    </li>
    <li>Conclusion: Performs well on familiar text, struggles with new genres, fails on nonsense.</li>
  </ul>
</section>
