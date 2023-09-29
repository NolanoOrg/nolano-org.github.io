---
title: Product and Services 
layout: product
description: Product and Services
---

## <span style="color:#6f0e62">TURBO: Inference Engine for Foundation Models</span>

<!-- Image -->
<div style="text-align: center;">
    <img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Feacd0282-373b-4440-be3a-8e4901ada954_1044x630.png" alt="Join Beta" width="450" height="450">
</div>
Large Language Models have become an integral component of modern software systems. In the world of language models, speed and efficiency are critical. For applications ranging from chatbots like ChatGPT to code/content generation tools like Jasper.ai and GitHub Copilot, the time it takes to generate a response can make all the difference.

At Nolano, we understand this and are thrilled to introduce Nolano’s Turbo LLM Engine – our answer to turbocharging inference for Large Language Models (LLMs).

<div style="text-align: center;">

  <a href="https://nolanoorg.substack.com/p/introducing-the-turbo-llm-inference" class="button">Read More on Turbo LLM Engine</a> 
</div>
<br>

## <span style="color:#6f0e62">Compact: Compression Engine for Foundation Models</span>

Coming Soon.

<div style="text-align: center;">

  <a href="/contact" class="button">Contact Us for Beta</a> 
<div>


<h3 style="text-align: center;">Open Source libraries for running Foundation Models locally</h3>

<div class="strip">
  <div class="container pt-3 pb-6 pb-md-10">

    <div class="row justify-content-start">
    <!-- write something about the features of our extension -->

      {% assign limit = site.home.limit_services | default: 2 %}
      {% for service in site.services limit: limit %}
      
      <div class="col-12 col-md-6 mb-2">
        <div class="service service-summary">
          <div class="service-content">
            <h2 class="service-title">
              {% if service.external_url %}
                <a href="{{ service.external_url }}">{{ service.title }}</a>
              {% else %}
              {% endif %}
              <a href="{{ service.url | relative_url }}">{{ service.title }}</a>
            </h2>
            
           <p>{{ service.content | markdownify | strip_html | truncate: 350 }}
           </p>
            <!-- Add video using canva for each content -->           
          </div>

          
        </div>
        <div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
        padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
        border-radius: 8px; will-change: transform;">
        <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
          src= "{{service.video}}" allowfullscreen="allowfullscreen" allow="fullscreen">
        </iframe>
        </div>     
      </div>

      
      {% endfor %}
      <br>

      <!-- <div style="position: relative; width: 70%; height: 0; padding-top: 39.2500%;
      padding-bottom: 0; box-shadow: 0 8px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden; margin-left: 13%;
      border-radius: 8px; will-change: transform; text-align: center;">
       <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0 0em;"
         src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZqke1NcY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
       </iframe>
     </div>      -->

    </div>
  </div>
</div>
