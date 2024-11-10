---
theme: apple-basic

transition: fade-out
layout: intro-image
image: intro.png
title: Intro
titleTemplate: "Presentation - Careers in Computer Science"
favicon: favicon.png
fonts:
  sans: FiraCode Nerd Font Mono
  serif: FiraCode Nerd Font Mono
  mono: FiraCode Nerd Font Mono
  provider: none
  fallbacks: false
---

<style>
  .text-with-shadow {
    color: black; /* Adjust the text color */
    text-shadow: 
      -2px -2px 0 white,
      2px -2px 0 white,
      -2px 2px 0 white,
      2px 2px 0 white;
  }
</style>

<div class="absolute top-10 text-with-shadow">
  <span class="font-700 text-black">
    Group D
  </span>
</div>

<div class="absolute bottom-0 text-black text-with-shadow ">
  <h1>Careers in Computer Science</h1>
  <p>Understanding Your Path</p>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-right
image: career_overview.png
class: text-sm
transition: slide-up
title: Career Overview
---

<div 
v-motion
  :initial="{y:200}"
  :click-1="{y:0}">
<h1>Introduction to Careers Path</h1>
</div>

<br>

<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]" 
  v-click="1"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0, transition: {delay: 100}}"
  >
  <b>
  Career Path and Choosing a Path
  </b>
</div>

<div>
  <ul>
    <li v-click="2">Meaning of Career</li>
    <li v-click="2">Choosing a Path</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="3"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
  >
  <b>
  Overview of The Computer Science Field
  </b>
</div>

<div>
  <ul>
    <li v-click="4">Hardware Based Field</li>
    <li v-click="4">Tech Field</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="5"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
  >
  <b>
  Why Choosing Career in Computer Science Field in Modernized World
  </b>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220322 | Atika Israt Ethila
  </span>
</div>

---
transition: fade-out
title: Intro 2
---

<h1 class="text-center"
v-click="0"
v-motion
  :click-0 = "{y:200}"
  :click-1 = "{y:0}"
>
Factors Influencing Careers in Computer Science Field</h1>
<br><br>

<div class="grid grid-cols-3 text-3.5">
  <div class="">
    <div class="flex flex-row items-center"
    v-click="1"
    v-motion
      :initial="{x:-290}"
      :enter="{x:0, transition: {delay: 200}}"
    >
      <mdi:chart-timeline-variant-shimmer class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Career Opportunities</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li v-click="2">
        Job Demand and Security</li>
        <li
        v-click="2">
        Salary Potential</li>
        <li
        v-click="2">
        Career Growth and Advancement</li>
      </ul>
    </div>
  </div>

  <div class="">
    <div class="flex flex-row items-center"
    v-click="3"
    v-motion
      :initial = "{y:800}"
      :enter = "{y:0}"
    >
      <mdi:head-heart-outline class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Personal Fulfillment</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="4">
        Interest and Passion for Technology</li>
        <li
        v-click="4">Work-Life Balance and Flexibility</li>
        <li
        v-click="4">Impact and Purpose</li>
      </ul>
    </div> 
  </div>

  <div class="">
    <div class="flex flex-row items-center"
    v-click="5"
    v-motion
      :initial = "{x:800}"
      :enter = "{x:0}"
    >
      <mdi:book-open-page-variant class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Skill Development</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="6">
        Education</li>
        <li
        v-click="6">Skill Requirements</li>
        <li
        v-click="6">Networking and Mentorship</li>
      </ul>
    </div>    
  </div>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220322 | Atika Israt Ethila
  </span>
</div>

---
layout: image-right
image: software_overview.png
class: text-sm
transition: slide-up
title: Software
---

<div 
v-motion
  :initial="{y:200}"
  :click-1="{y:0}">
<h1>Overview of Software Development</h1>
</div>

<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="1"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0, transition: {delay: 100}}"
  >
  <b>
  Web Development
  </b>
</div>

<div>
  <ul>
    <li v-click="2">Websites & WebApps</li>
    <li v-click="2">Frontend / Backend / Full Stack</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="3"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
  >
  <b>
  Mobile App Development
  </b>
</div>

<div>
  <ul>
    <li v-click="4">iOS & Android</li>
    <li v-click="4">Cross-platform vs. Native development</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="5"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
  >
  <b>
  Game Development
  </b>
</div>

<div>
  <ul>
    <li v-click="6">Interactive games</li>
    <li v-click="6">Game Engines</li>
  </ul>
</div>


<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220327 | Araf Mahmud
  </span>
</div>

---
transition: fade-out
title: Software 2
---

<h1 class="text-center"
v-click="0"
v-motion
  :click-0="{y:200}"
  :click-1="{y:0}"
>
Skills Needed for Software Development</h1>
<br><br><br>

<div class="grid grid-cols-3 text-3.5">
  <div class="">
    <div class="flex flex-row items-center"
    v-click="1"
    v-motion
      :initial="{x:-290}"
      :enter="{x:0, transition: {delay: 200}}"
    >
      <game-icons-wireframe-globe class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Web Development</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="2">HTML, CSS</li>
        <li
        v-click="2">JavaScript, TypeScript</li>
        <li
        v-click="2">Backend Languages (NodeJS, Python, PHP)</li>
      </ul>
    </div>
  </div>

  <div class="mx-3">
    <div class="flex flex-row items-center"
    v-click="3"
    v-motion
      :initial = "{y:800}"
      :enter = "{y:0}"
    >
      <game-icons:smartphone class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Mobile App Development</b></span>
    </div>
    <br>
    <div class="mx-7">
    <ul>
      <li
      v-click="4">React Native</li>
      <li
      v-click="4">Flutter</li>
      <li
      v-click="4">Xamarin (.NET/C#)</li>
      <li
      v-click="4">Swift (iOS)</li>
    </ul>
    </div>
  </div>

  <div class="mx-7">
    <div class="flex flex-row items-center"
    v-click="5"
    v-motion
      :initial = "{x:800}"
      :enter = "{x:0}"
    >
      <game-icons:console-controller class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Game Development</b></span>
    </div>
    <br>
    <div class="mx-7">
    <ul>
      <li
      v-click="6">Languages: C++, C#, Java, Python</li>
      <li
      v-click="6">Graphics Engines: Unreal Engine, Unity</li>
    </ul>
    </div>
  </div>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220327 | Araf Mahmud
  </span>
</div>

---
layout: image-right
image: data_overview.png
class: text-sm
transition: slide-up
title: Data
---

<div 
v-motion
  :initial="{y:200}"
  :click-1="{y:0}">
<h1>A World of Data Opportunities</h1>
</div>

<br>

<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="1"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0, transition: {delay: 100}}"
>
  <b>
  Data Analyst
  </b>
</div>

<div>
  <ul>
    <li v-click="2">Data Analyzation & Cleaning</li>
    <li v-click="2">SQL & Visualization Tools</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="3"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  Data Engineer
  </b>
</div>

<div>
  <ul>
    <li v-click="4">Data pipeline management</li>
    <li v-click="4">Complex datasets handling</li>
    <li v-click="4">Programming skills</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="5"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  Data Scientist
  </b>
</div>

<div>
  <ul>
    <li v-click="6">Statistics & ML</li>
    <li v-click="6">Predictive Models</li>
  </ul>
</div>


<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220325 | MD. Naeem Hossen
  </span>
</div>

---
transition: fade-out
title: Data 2
---

<h1 class="text-center"
v-click="0"
v-motion
  :click-0="{y:200}"
  :click-1="{y:0}"
> The Power of Statistical Analysis and Data Interpretation</h1>
<br><br>

<div class="grid grid-cols-3 text-3.5">
  <div class="">
    <div class="flex flex-row items-center"
    v-click="1"
    v-motion
      :initial="{x:-290}"
      :enter="{x:0, transition: {delay: 200}}"
    >
      <mdi:chart-line class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Statistical Analysis</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="2">Framework for understanding data.</li>
        <li
        v-click="2">Identifies patterns and trends.</li>
        <li
        v-click="2">Enables data-driven decisions.</li>
      </ul>
    </div>
  </div>

  <div class="">
    <div class="flex flex-row items-center"
    v-click="3"
    v-motion
      :initial="{y: 800}"
      :enter="{y:0}"
    >
      <mdi:chart-arc class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Data Interpretation</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="4">Translates complex data into clear stories.</li>
        <li
        v-click="4">Communicates findings to diverse audiences.</li>
        <li
        v-click="4">Uses visualizations for better understanding.</li>
      </ul>
    </div>
  </div>
  <div class="">
    <div class="flex flex-row items-center"
    v-click="5"
    v-motion
      :initial="{x: 800}"
      :enter="{x:0}"
    >
      <mdi:scale-balance class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Data-Driven Decision &nbsp;Making</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="6">Leverages data insights for informed choices.</li>
        <li
        v-click="6">Optimizes processes and strategies.</li>
        <li
        v-click="6">Boosts performance and competitiveness.</li>    </ul>
    </div>
  </div>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220325 | MD. Naeem Hossen
  </span>
</div>

---
layout: image-right
image: cybersecurity_overview.png
class: text-sm
transition: slide-up
title: Cybersecurity
---

<div 
v-motion
  :initial="{y:200}"
  :click-1="{y:0}">
<h1>Cybersecurity</h1>
<h2>A Thriving Career Path</h2>
</div>

<br>
<br>

<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="1"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0, transition: {delay: 100}}"
>
  <b>
  Cybersecurity Analyst
  </b>
</div>

<div>
  <ul>
    <li v-click="2">Risk Mitigation</li>
    <li v-click="2">Threat Response</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="3"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  Penetration Tester
  </b>
</div>

<div>
  <ul>
    <li v-click="4">Simulates attacks</li>
    <li v-click="4">Tests security</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="5"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  Cyberecurity Engineer
  </b>
</div>

<div>
  <ul>
    <li v-click="6">Infrastructure Design</li>
    <li v-click="6">Solutions & Audits</li>
  </ul>
</div>


<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220324 | Abdullah Al Muaz (Aurka)
  </span>
</div>

---
transition: slide-up
title: Cybersecurity 2
---

<h1 class="text-center"
v-click="0"
v-motion
  :click-0="{y:200}"
  :click-1="{y:0}"
>Essential Skills for Cybersecurity</h1>
<br><br><br>

<div class="grid grid-cols-3 text-3.5">
  <div class="">
    <div class="flex flex-row items-center"
    v-click="1"
    v-motion
      :initial="{x:-290}"
      :enter="{x:0, transition: {delay: 200}}"
    >
      <hugeicons:nano-technology class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Technical Skills</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="2">Networking</li>
        <li
        v-click="2">Operating Systems</li>
        <li
        v-click="2">Programming</li>
        <li
        v-click="2">Cryptography</li>
        <li
        v-click="2">Database Security</li>
      </ul>
    </div>
  </div>

  <div class="mx-5">
    <div class="flex flex-row items-center"
    v-click="3"
    v-motion
      :initial="{y:800}"
      :enter="{y:0}"
    >
      <hugeicons:brain-02 class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Soft Skills</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="4">Problem-solving</li>
        <li
        v-click="4">Critical thinking</li>
        <li
        v-click="4">Communication</li>
        <li
        v-click="4">Attention to detail</li>
        <li
        v-click="4">Adaptability</li>
      </ul>
    </div>
  </div>

  <div class="">
    <div class="flex flex-row items-center"
    v-click="5"
    v-motion
      :initial="{y:800}"
      :enter="{y:0}"
    >
      <hugeicons:certificate-01 class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Certifications</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="6">OSCP</li>
        <li
        v-click="6">GIAC</li>
        <li
        v-click="6">CISSP</li>
      </ul>
    </div>
  </div>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220324 | Abdullah Al Muaz (Aurka)
  </span>
</div>

---
layout: image-right
image: emerge.png
class: text-sm
transition: slide-up
title: Emerging Tech
---

<div 
v-motion
  :initial="{y:200}"
  :click-1="{y:0}">
<h1>Emerging Tech Overview</h1>
</div>

<br>

<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="1"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0, transition: {delay: 100}}"
>
  <b>
  Artificial Intelligence
  </b>
</div>

<div>
  <ul>
    <li v-click="2">Natural Language Processing</li>
    <li v-click="2">Computer Vision</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="3"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  Machine Learning
  </b>
</div>

<div>
  <ul>
    <li v-click="4">Supervised/Unsupervised learning</li>
    <li v-click="4">Reinforcement learning</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="5"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  Internet of Things
  </b>
</div>

<div>
  <ul>
    <li v-click="6">Connected devices</li>
    <li v-click="6">Automation and control</li>
  </ul>
</div>


<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220328 | S.M. Jahirul Islam Bayazed
  </span>
</div>

---
transition: slide-up
title: Emerging tech 2
---

<h1 class="text-center"
v-click="0"
v-motion
  :click-0="{y:200}"
  :click-1="{y:0}"
>The Power of Continuous Learning</h1>
<br><br><br>

<div class="grid grid-cols-3 text-3.5">
  <div class="">
    <div class="flex flex-row items-center"
    v-click="1"
    v-motion
      :initial="{x:-290}"
      :enter="{x:0, transition: {delay: 200}}"
    >
      <mdi:trending-up class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Industry Trends</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="2">Follow Tech News</li>
        <li
        v-click="2">Attend Events</li>
        <li
        v-click="2">Join Communities</li>
      </ul>
    </div>
  </div>

  <div class="mx-5">
    <div class="flex flex-row items-center"
    v-click="3"
    v-motion
      :initial="{y:800}"
      :enter="{y:0}"
    >
      <fa6-solid:money-bill-trend-up class="text-3xl"/>
      <span class="text-4"><b>&nbsp;In-Demand Skills</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="4">Learn Programming</li>
        <li
        v-click="4">Master Data Analysis</li>
        <li
        v-click="4">Gain Cloud Expertise</li>
      </ul>
    </div>
  </div>

  <div class="">
    <div class="flex flex-row items-center"
    v-click="5"
    v-motion
      :initial="{y:800}"
      :enter="{y:0}"
    >
      <hugeicons:elearning-exchange class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Lifelong Learning</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="6">Online Courses</li>
        <li
        v-click="6">Hackathons</li>
        <li
        v-click="6">MExperimentation</li>
      </ul>
    </div>
  </div>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220328 | S.M. Jahirul Islam Bayazed
  </span>
</div>

---
layout: image-right
image: strategy.png
class: text-sm
transition: slide-up
title: Strategy
---

<div 
v-motion
  :initial="{y:200}"
  :click-1="{y:0}">
<h1>Fueling Your Career</h1>
<h2>with Experience and Knowledge</h2>
</div>

<br>

<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="1"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0, transition: {delay: 100}}"
>
  <b>
  The Power of Internships
  </b>
</div>

<div>
  <ul>
    <li v-click="2">Real-world experience</li>
    <li v-click="2">Networking opportunities.</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="3"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  The Value of Certifications
  </b>
</div>

<div>
  <ul>
    <li v-click="4">Career advancement</li>
    <li v-click="4">Industry recognition</li>
  </ul>
</div>


<div class="text-md pt-2 uppercase tracking-widest font-500 -ml-[0.05em]"
  v-click="5"
  v-motion
    :initial="{x:-80}"
    :enter="{x:0}"
>
  <b>
  The Lifelong Pursuit of Learning
  </b>
</div>

<div>
  <ul>
    <li v-click="6">Stay updated</li>
    <li v-click="6">Skill development</li>
  </ul>
</div>


<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220329 | Shahreer Islam Sayem
  </span>
</div>

---
transition: fade-out
title: Strategy 2
---

<h1 class="text-center"
v-click="0"
v-motion
  :click-0="{y:200}"
  :click-1="{y:0}"
>Building Your Professional Network and Seeking Mentorship</h1>
<br><br>

<div class="grid grid-cols-3 text-3.5">
  <div class="">
    <div class="flex flex-row items-center"
    v-click="1"
    v-motion
      :initial="{x:-290}"
      :enter="{x:0, transition: {delay: 200}}"
    >
      <fluent:people-community-12-filled class="text-3xl"/>
      <span class="text-4"><b>&nbsp;The Importance of &nbsp;Networking</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="2">Expand connections</li>
        <li
        v-click="2">Advice and guidance</li>
        <li
        v-click="2">Collaborate</li>
      </ul>
    </div>
  </div>

  <div class="mx-5">
    <div class="flex flex-row items-center"
    v-click="3"
    v-motion
      :initial="{y:800}"
      :enter="{y:0}"
    >
      <hugeicons:mentor class="text-3xl"/>
      <span class="text-4"><b>&nbsp;The Benefits of &nbsp;Mentorship</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="4">Career guidance</li>
        <li
        v-click="4">Skill development</li>
        <li
        v-click="4">Support and encouragement</li>
      </ul>
    </div>
  </div>

  <div class="">
    <div class="flex flex-row items-center"
    v-click="5"
    v-motion
      :initial="{y:800}"
      :enter="{y:0}"
    >
      <mdi:lightbulb class="text-3xl"/>
      <span class="text-4"><b>&nbsp;Leveraging &nbsp;Opportunitiess</b></span>
    </div>
    <br>
    <div class="mx-7">
      <ul>
        <li
        v-click="6">Professional organizations</li>
        <li
        v-click="6">Online platforms</li>
        <li
        v-click="6">Mentorship programs</li>
      </ul>
    </div>
  </div>
</div>

<div class="absolute bottom-5 right-10">
  <span class="text-xs font-400">
    220329 | Shahreer Islam Sayem
  </span>
</div>

---
layout: center
---

# Explore ● Invest ● Connect
