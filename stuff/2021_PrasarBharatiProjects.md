<!--
<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-AMS_HTML-full"></script>

**Estimated Enrollment:** 40
-->

# AUTOMATIC SPEECH RECOGNITION FOR SPEECH SUBTITLING
# <span style= 'color:red'>For Prasar Bharati</span>
<img src="{{ "/assets/img/asr_image.png" | absolute_url }}" alt="bay" class="post-pic"/>
<br />

## Table of Contents
1. [Introduction](# Introduction)
2. [Methodology](# Methodolgy)
    * [Data Preparation](# data-preparation)
    * [Modelling](# modelling)
    * [Evaluation](# evaluation)
    * [ASR with background sounds](# ASR-with-background-sounds)

### INTRODUCTION
Prasar Bharati is India's largest broadcasting agency, broadcasting audio and video content via All India Radio and Doordarshan. It has a humungous wealth of audio and video content. In this age of digitization and AI, machine learning technologies have opened up vast opportunities. A proper content analysis can help in efficient search, recommendation, accessibility, translation and so on. In this project, we propose to develop and deploy automatic speech recognition (ASR) technologies for Prasar Bharati's multimedia content.

The ASR outputs can serve greatly in content recommendation. Recommendation services make use of text to find programs related to the viewer's choices or watch history, and recommend those programs that viewers shall like.

The text so obtained could be translated with Automatic Machine Translation systems. India is a country of different languages and Prasar Bharati broadcasts to different states with different languages. ASR can enable translated subtitles for enhanced viewability.

Another application of these technologies would be in media monitoring by continuously listening to news or social media on internet. Whenever there is any conversation about a particular topic or brand, it can be retrieved automatically and brought into notice of concerned persons.

## SCOPE OF WORK
We propose to implement an automatic speech recognition (ASR) system for certain languages. It will convert speech audio into a textual form. 
Specifically, it will be a conversational large vocabulary continuous speech recognition (LVCSR) system in its final form. The project will have 3 main components, namely, 

1.	***Data preparation***
2.	***Training of acoustic and language models***
3.	***Evaluation*** 

A fourth stage may be added, if required, i.e., deployment for the end use case.


