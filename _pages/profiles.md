---
layout: page
permalink: /people/
title: People
description: 
nav: true
nav_order: 6
---
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toggle Talks Section</title>
    <style>
        .container {
            display: flex; /* Flexbox for alignment */
            align-items: flex-start; /* Center items vertically */
        }
        .badge {
        display: block; /* Ensures the heading takes up the full width */
        padding: 10px 20px;
        background-color: #1034a6; /* Solid background color */
        color: black; /* Text color */
        font-weight: bold;
        font-size: 1.5em; /* Adjust font size for heading */
        text-align: right; /* Aligns the text to the right */
        transition: all 0.3s ease; /* Smooth transition */
}
        .badge:hover {
            transform: translateY(-3px); /* Lift effect on hover */
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4); /* Shadow on hover */
        }
        .newbage {
        background-color: #2698ba; /* blue gray background for the badge */
        border-radius: 5px; /* Rounded corners */
        padding: 5px 10px; /* Padding inside the badge */
        font-size: 0.8em; /* Slightly smaller font */
        margin-right: 10px; /* Space between badge and name */
        color: white; /* Set the font color to white */
        font-weight: bold;
        }
        .newbagest {
        background-color: grey; /* Light gray background for the badge */
        border-radius: 5px; /* Rounded corners */
        padding: 5px 10px; /* Padding inside the badge */
        font-size: 0.8em; /* Slightly smaller font */
        margin-right: 10px; /* Space between badge and name */
        color: white; /* Set the font color to white */
        font-weight: bold;
        }
        #talks-content {
            display: block; /* Initially show the content */
            margin-top: 10px; /* Space above the content */
        }
        #student-content {
            display: block; /* Initially show the content */
            margin-top: 10px; /* Space above the content */
        }
        .content {
            line-height: 1.5; /* Space between lines */
        }
    </style>
    <script>
        function toggleTalks() {
            var content = document.getElementById('talks-content');
            content.style.display = (content.style.display === 'block') ? 'none' : 'block';
        }
        function togglestudent() {
            var content = document.getElementById('student-content');
            content.style.display = (content.style.display === 'block') ? 'none' : 'block';
        }
    </script>
</head>
<body>

<div style="text-align: right; color: #e5e5e5;">
    <hr style="margin: 0; margin-top: 0px;"> <!-- Set margins to 0 and add a small top margin -->
    <h2 style="display: inline; margin: 0; color:rgb(34, 27, 97);">Advisors</h2> <!-- Remove margin -->
</div>



<!-- Content to be toggled -->
<div id="talks-content">
    <div class="container">
        <div class="newbage">PhD Advisor</div>
        <div class="content">
            <a href="https://borismordukhovich.com/" style="font-weight: bold;">Prof. Boris Mordukhovich,</a> Distinguished University Professor of Mathematics, Wayne State University<br>
             Dissertation: TBA
        </div>
    </div>
    <div style="margin-top: 20px;"></div> 
    <div class="container">
        <div class="newbage">PhD Advisor</div>
        <div class="content">
            <a href="https://sites.google.com/site/khanhpd182/" style="font-weight: bold;">Prof. Pham Duy Khanh,</a> Associate Professor of Mathematics, Ho Chi Minh University of Education<br>
            PhD Dissertation: TBA<br>
            Undergraduate Research/Thesis: Extremal Principle and Applications
        </div>
    </div>
    <div style="margin-top: 20px;"></div> 
</div>

<div style="margin-top: 40px;"></div> 

<div style="text-align: right;">
    <hr style="margin: 0; margin-top: 0px;">
    <h2 style="display: inline; color:rgb(34, 27, 97); text-align: right;">Students</h2> 
</div>


<!-- Content to be toggled -->
<div id="student-content">
    <div style="margin-top: 20px;"></div>
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
            Ton Gia Phu, Ho Chi Minh City University of Education  (2024/6 - )<br>
            Thesis: Generalized Mean Value Theorems and Applications (co-supervised with Prof. Pham Duy Khanh)
        </div>
    </div> 
    <div style="margin-top: 20px;"></div>
</div>