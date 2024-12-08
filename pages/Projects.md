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
    body {
        background-color: #e0e3dc; /* Light gray background color */
        margin: 0; /* Remove default margins */
        padding: 0; /* Remove default padding */
    }

    /* General container for better alignment and formatting */
    .education-section {
        max-width: 900px;
        margin: 0 auto; /* Center align the section */
        padding: 10px 0; /* Add vertical spacing */
        font-family: 'Avenir Next LT Pro', sans-serif;
    }

    /* Highlight section with no box */
    .highlight {
        max-width: 900px;
        margin: 0 auto 20px;
        padding: 0; /* No padding for clean look */
        font-weight: normal;
        color: rgba(150,170,150,1);
        font-size: 1.2em;
        margin-left: 30px;
        margin-top: 40px;
        margin-bottom: 30px;
    }

    /* Add indentation for the content below the section title */
    .education-content {
        margin-left: 30px; /* Indentation for education content */
    }

    /* Styling for course/project titles */
    .course-title {
        font-weight: bold;
        color: rgba(46, 89, 132,1); /* Royal Blue */
        font-size: 1em; /* Slightly smaller but still noticeable */
        margin-left: 30px; /* Increase space below title */
        margin-bottom: 8px;
    }

    /* Styling for course details (dates) */
    .course-details {
        font-size: .8em; /* Clear and noticeable */
        font-weight: normal;
        color: black; /* Dark gray for better readability */
        margin-bottom: 25px; /* Add space below details */
        margin-left: 30px;
    }

    /* Styling for course descriptions */
    .course-description {
        margin-top: 15px; /* Space between details and description */
        margin-left: 50px;
    }

    .course-description ul {
        margin: 0;
        padding-left: 20px; /* Slight indentation for bullets */
        list-style-type: circle; /* Use circle bullets */
    }

    /* Styling the list bullets (circles) */
    .course-description ul li::marker {
        color: gray; /* Change the bullet color */
        font-weight: bold; /* Make the bullet bold */
    }

    .course-description ul li {
        margin-bottom: 8px; /* Increase spacing between bullet points */
        font-size: 0.9em; /* Readable size */
        color: #555; /* Slightly lighter gray for description text */
        line-height: 1.2; 
    }

    /* Divider styling */
    hr {
        border: 0;
        border-top: 1px solid #ddd;
        margin: 30px 0; /* Add more space between sections */
    }
</style>

<!-- Feature Image -->
<img src="assets/img/pexels/back.jpg" class="feature-img" alt="">

<h1 class="education-title"></h1>

<section class="education-section">
    <div>
        <div class="course-title">Sentiment Analysis using Machine Learning Algorithms</div>
        <div class="course-details"> | 10.2023 – Present | </div>
        <div class="course-description">
            <ul>
                <li>Analyzed text data including Mobile Apps, Twitter, Yelp, and product Reviews.</li>
                <li>Trained and evaluated various deep learning and classical machine learning models.</li>
                <li>Achieved sentiment accuracy of 48% (neutral), 71% (negative), and 81% (positive).</li>
            </ul>
        </div>
    </div>

    <hr>

    <div>
        <div class="course-title">Automatic Detection of Machine-Generated Text</div>
        <div class="course-details"> | 09.2022 – 03.2023 | </div>
        <div class="course-description">
            <ul>
                <li>Analyzed web-scraped data (Reviews, Poems, Tweets, News) in English and Dutch.</li>
                <li>Achieved 97% accuracy in detecting machine-generated text using ensemble learning.</li>
                <li>The top-performing classical model surpassed deep learning models by a significant margin.</li>
            </ul>
        </div>
    </div>

    <hr>

    <div>
        <div class="course-title">Developing an Age-Appropriate Rating System for Podcasts</div>
        <div class="course-details"> | 06.2021 – 12.2021 | </div>
        <div class="course-description">
            <ul>
                <li>Developed a topic modeling system for podcasts, integrating BERTopic and LMMs.</li>
                <li>Model directly identifies topics without post-processing, reducing computation time.</li>
                <li>Developed an age rating system for podcasts based on identified topics and subtopics.</li>
            </ul>
        </div>
    </div>

    <hr>

    <div>
        <div class="course-title">Evaluating GPT Model Performance Using Perplexity</div>
        <div class="course-details"> | 01.2021 – 05.2021 | </div>
        <div class="course-description">
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
        </div>
    </div>
</section>
