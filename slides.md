---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://media.istockphoto.com/id/1128252197/photo/close-up-watching.jpg?s=1024x1024&w=is&k=20&c=QQCFKWEujoi-AGoMWiS8sFVJRA_19t_UXQvsw-W1tbc=
# some information about your slides (markdown enabled)
title: workshop 1
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# Focused People
<div></div>
Welcome to Open source Workshop 1
<br>
<br>
<a target="blank" href="#">Link to Repository</a>
<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    "Ready to Shift Your Focus🕐? Press space for next page" <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


<style>
h1 {
  background-color: #90EE90; 
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
a{
  color: white;
}

</style>



---
layout: two-cols
layoutClass: gap-16
transition: slide-up
class: grid place-content-center
hideInToc: true
---


# Table of content
<div></div>

What are the thing we will be covering?

::right::
<Toc v-click minDepth="1" maxDepth="2"></Toc>

<style>
h1 {
  color: #90EE90; 
  
}
</style>


---
transition: slide-up
---

# Beyond Fixing Docs
<div></div>

### What is Open Source ?
The term [open source](https://opensource.com/article/18/2/coining-term-open-source-software) refers to something people can modify and share because its design is publicly accessible.
<br>
<br>
In other word we can say;<br>
Open source is source code that is made freely available for possible modification and redistribution.

It worthy to know the core principle:  **The open source way**
- Collaboration
- Transparency
- Release early and often
- Inclusive meritocracy
- Community

<br>
<br>

<style >
h1,h3 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---

# From the eyes builders
<div></div>
Problem: Slow development sever startup and update time (a major pain point for developers). Traditional bundlers can take a significant amount of time to process all your code and libraries, leading to frustrating delays while working.
<br>
<br>

### The rise of vite: Blazing fast development

- Vite is a revolutionary front-end build tool known for its exceptional speed.
- Its innovative features like hot module replacement (HMR) enables near-instantaneous updates, streamlining development workflows.
- Builders can experiment and iterates at lightning speeds, leading to fast development cycles and increased productivity.

<style >
h1,h3 {
  color: #90EE90; 
  
}
</style>


---
transition: slide-up
---

# Beyond Vite: A broader impact
<div></div>

Vite takes a different approach by leveraging two key technologies.
- esbuild: This is the powerhouse behind vite's speed. This ultra-fast bundler pre-compiles dependecies into optimized bundles, significantly reducing the amount of work needed on every change. 
<br>
<br>

- Hot Module Replacement: vite utilizes a more effiecient HMR implementation that update only the changed modules instead of reloading the entire page. This keeps your development environment snappy and responsive. 

***Faster than a speeding bundler***: curious to know what makes vite tick like a clockwork caffeine machine? The source code is wide open! Peek inside and witness the revolutionary tech (esbuild and HMR) that keeps your development lightening fast.
<style >
h1,h3 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---
# Do you know you can configure your own eslint?
<div></div>
**ACTIVITY**
Let dive deep.

<style >
h1 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---

# A deep dive into Chakra UI
<div></div>

**The problem : Building UIs in React**
<br>

Existing component libraries can be:
- complex and difficult to learn
- inflexible for customization

**Introducing Chakra UI**
A react UI component focused on:
- Ease of use
- Flexibility
- Modern design 

**Chakra UI solutions**
- simple and accessible components
- responsive design
- Easy customization with a well- documented API

<style >
h1 {
  color: #90EE90; 
  
}
</style>


---

# The big question
<div></div>
What will shape the future of open source?
Open source has revolutionized software development, fostering collaboration and innovation. But the landscape is constantly evolving.

### Here's your chance to be a visionary!
-	Emerging Trends: What are the hot new technologies or methodologies that could significantly impact open-source development? How can we leverage them to build even more powerful and impactful projects?
<br>

- Sustainability and Funding: Open-source projects often rely on the dedication of volunteers. How can we ensure the long-term sustainability of these projects? Are there new funding models or support structures we should explore?
<br>

- Open Source for Good: Open source goes beyond just code. How can we harness the power of open source to tackle global challenges and create positive change in the world?

This workshop is more than just learning a specific tool; it's about shaping the future of open-source development itself.Share your thoughts, ideas, and concerns. Together, we can ensure open source continues to thrive and create a better future for everyone!

<style >
h1 {
  color: #90EE90; 
  
}
</style>

---
transition: slide-up
---

# Open Source: Powering Collaboration and Innovation
<div></div>
Open source software (OSS) offers a wealth of benefits for both users and developers. Here are some key advantages:
<br>

-	Cost-Effective: Often free to use and modify, saving on licensing fees and promoting affordability.
<br>

-	Enhanced Security: With open code, a larger community can identify and fix vulnerabilities, leading to more secure software.
<br>

-	Flexibility & Customization: The ability to modify the source code allows users to tailor software to their specific needs.
<br>

-	Strong Community Support: Open source projects often have active communities providing help, tutorials, and ongoing development.
<br>

-	Faster Innovation: Collaboration from a global pool of developers can accelerate bug fixes and the addition of new features.
<br>

-	Future-Proof: Not locked into a single vendor, open source offers greater control and avoids potential software obsolescence.

<style >
h1 {
  color: #90EE90; 
  
}
</style>

---
transition: slide-up
---
# You are the next big hit! 
<div></div>

A wise man once told me *DO NOT UNDERESTIMATE THE POWER  OF OPEN SOURCE* rather take advantage of it!!!
<br>
<br>
I hope i have been able to ginger your dev mode, see you on the other side of open source.

<style >
h1 {
  color: #90EE90; 
  
}
</style>

---
transition: slide-up

---
# Appreciation
<div></div>
Thank you for the opportunity Mr setemi.

<style >
h1 {
  color: #90EE90; 
  
}
</style>
---
