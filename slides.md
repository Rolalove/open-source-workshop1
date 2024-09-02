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

<div class='flex justify-between mt-10'>
<div> <div class='flex'><img class='image' src="/src/assets/anthonyfu.png" alt="Anthony fu image"/> 
<ul class='ml-3'>
<li>Slidev</li>
<li>Vitest</li>
<li>Type Challenge</li>
</ul> </div>
<a href ='https://github.com/antfu' target='blank'>Anthony Fu </a>
</div>

<div> <div class='flex'><img class='image' src="/src/assets/kentc.png" alt="Kent C. Dodds image"/> 
<ul class='ml-3'>
<li> testing-library/react-testing-library </li>
<li> downshift-js/downshift </li>
<li> babel-plugin-macros </li>
</ul> </div>
<a href ='https://github.com/kentcdodds' target='blank'>Kent C. Dodds</a>
</div>
<div>  <div class='flex'> <img class='image' src="/src/assets/sorhus.png" alt="Sindre Sorhus image"/>
<ul class='ml-3'>
<li> awesome </li>
<li> KeyboardShortcuts </li>
<li> Actions </li>
</ul> </div>
<a href ='https://github.com/sindresorhus' target='blank'>Sindre Sorhus</a>
</div>
</div>


<div class='flex mt-12 justify-between'>

<div> <div class='flex'> <img class='image' src="/src/assets/prosper.png" alt=" Prosper otemuyiwaimage"/>
<ul class='ml-3'>
<li>awesome-nextjs </li>
<li>awesome-opensource-apps </li>
</ul> </div>
<a href ='https://github.com/unicodeveloper' target='blank'>Prosper otemuyiwa </a></div>
<div> <div class='flex'><img class='image' src="/src/assets/tanner.png" alt="Tanner linsley image"/>
<ul class='ml-3'>
<li>TanStack Router</li>
<li>TanStack Table</li>
<li>TanStack Query</li>
</ul> </div>
<a href ='https://github.com/tanstack' target='blank'>Tanner linsley</a></div>
<div> <div class='flex'> <img class='image' src="/src/assets/segunadebayo.png" alt="Segun adebayo image"/>
<ul class='ml-3'>
<li> chakra-ui/chakra-ui </li>
<li>chakra-ui/panda </li>
<li>chakra-ui/zag </li>
</ul> </div>
<a href ='https://github.com/segunadebayo' target='blank'>Segun Adebayo</a>
</div>

</div>

<style >
h1,h3 {
  color: #90EE90; 
  
}
.image{
  border-radius: 50%;
  width:100px;
  height:100px;
}
a{
  margin-top: 5rem;
}
</style>
---
transition: slide-up
---
# The Evolution of Build Tools: From Webpack to Vite
<div></div>

Problem: Slow development sever startup and update time.
<br>
<br>
A major pain point for developers has been the slow performance of traditional bundlers, particularly Webpack. These tools can take a significant amount of time to process all your code and libraries, leading to frustrating delays while working.

### The Webpack Era: Powerful but Slow
- Webpack has been a popular and powerful bundler for years.
- It offers extensive configuration options and supports complex build processes.
- However, as projects grow larger, Webpack's performance often deteriorates.
- Developers face long initial build times and slow hot module replacement (HMR).
- These delays interrupt the development flow and reduce productivity.



<style >
h1,h3 {
  color: #90EE90; 
  
}

</style>


---
transition: slide-up
---

### The rise of vite: Blazing fast development

- Vite is a revolutionary front-end build tool known for its exceptional speed.
- It leverages native ES modules in the browser, eliminating the need for bundling during development.
- Its innovative features like hot module replacement (HMR) enables near-instantaneous updates, streamlining development workflows.
- Builders can experiment and iterates at lightning speeds, leading to fast development cycles and increased productivity.

### Key Advantages of Vite over Webpack

- Instant server start: Vite doesn't bundle your entire application on startup.
- Lightning-fast HMR: Updates are reflected almost immediately in the browser.
- Out-of-the-box TypeScript support: No need for additional loaders or plugins.
- Optimized builds: Vite uses Rollup for production builds, resulting in smaller bundle sizes.
- Simpler configuration: Less boilerplate and easier setup compared to Webpack.

By addressing the pain points of Webpack and other traditional bundlers, Vite has quickly become a preferred choice for many developers looking to optimize their development experience and boost productivity.

<style >
h1,h3 {
  color: #90EE90; 
  
}
</style>

---
transition: slide-up
---

# Vite's Powerful Plugin Ecosystem
<div></div>
One of Vite's strengths is its robust and flexible plugin system, which allows developers to extend and customize their build process efficiently.

### Key Features of Vite's Plugin Ecosystem
-  Simplicity: Vite plugins are typically more straightforward to write and use compared to Webpack loaders and plugins.
- Rollup Compatibility: Many Rollup plugins work out-of-the-box with Vite, expanding the available ecosystem.
- Performance: Plugins in Vite are designed to maintain the tool's speed advantage.
- Hot Module Replacement (HMR) Integration: Plugins can easily tap into Vite's HMR system for instant updates.
### Popular Vite Plugins
- @vitejs/plugin-react: Provides React Fast Refresh support.
- @vitejs/plugin-vue: Enables Vue 3 single-file component support.
- @sveltejs/vite-plugin-svelte: Adds Svelte support to Vite.

<style >
h1,h3 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---

- vite-plugin-pwa: Generates service worker for Progressive Web Apps.
- vite-plugin-windicss: Integrates the WindiCSS framework with Vite.

### Creating Custom Plugins
Vite's plugin API allows developers to create custom plugins tailored to their specific needs. This can include:

- Custom file transformations
- Handling of non-standard file types
- Integration of development servers or tools
- Modification of the build process

### Plugin Ecosystem vs Webpack
While Webpack has a vast ecosystem of loaders and plugins, Vite's plugin system offers several advantages:

- Simpler API: Vite plugins are often easier to develop and maintain.
- Faster execution: Aligned with Vite's performance-first approach.
- Better developer experience: Plugins integrate seamlessly with Vite's instant server start and HMR capabilities.


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
 The growing plugin ecosystem, combined with Vite's speed and simplicity, makes it an attractive option for developers looking to optimize their build tooling and workflow.

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

### How many ui library is built openly?
<div></div>
<br>


<div class="flex items-center mb-6"><div> <img src='/src/assets/materialui.png'/> </div> Material-UI (MUI): A popular React UI framework based on Google's Material Design.</div>
<div class="flex items-center mb-6"><div> <img src='/src/assets/chakraui.png'/> </div> Chakra UI: A simple, modular and accessible component library for React applications.</div>
<div class="flex items-center mb-6"><div> <img width="60px" height="40px" src='/src/assets/antdesign.png'/> </div>Ant Design: A design system for enterprise-level products, widely used with React.</div>
<div class="flex items-center mb-6 "><div> <img src='/src/assets/bootstrap.png'/> </div> Bootstrap: One of the most well-known open-source CSS frameworks.</div>
<div class="flex items-center "><div> <img src='/src/assets/materialui.png'/> </div> Tailwind CSS: A utility-first CSS framework gaining significant popularity.</div>


<style >
h1,h3 {
  color: #90EE90; 
  
}
</style>

---
transition: slide-up
---

# A deep dive into Chakra UI
<div></div>

**The problem : Building UIs in any framework**
<br>

### Getting Started
Chakra UI is a popular component library for React applications. Here's how to get started:

Install Chakra UI and its peer dependencies:

```
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
```

Wrap your application with the ChakraProvider:

```
import { ChakraProvider } from '@chakra-ui/react'
function App() {
  return (
    <ChakraProvider>
      <YourApp />
    </ChakraProvider>
  )
}
```
<style scoped>
h1,h3 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---

# Start using Chakra UI components:
<div></div>

```
import { Box, Button } from '@chakra-ui/react'

function Example() {
  return (
    <Box>
      <Button colorScheme="blue">Click me</Button>
    </Box>
  )
}
```

### Extensibility
Chakra UI is highly extensible:

- Custom themes: Customize colors, fonts, and more.
- Component styling: Use the sx prop or style props for quick modifications.
- Custom components: Easily create new components based on Chakra primitives.
<style scoped>
h1,h3 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---

### Beyond React
While Chakra UI is primarily for React, there are community-driven ports for other frameworks:

- Vue: Chakra UI Vue
- Svelte: Svelte Chakra UI
- Next.js(App)
- Next.js(Pages)
- Gatsby


These ports aim to bring Chakra's design system and component library to other popular frameworks.

### Chakra UI with Panda CSS and UnoCSS
Chakra UI can be used alongside other CSS solutions:

- Panda CSS: A CSS-in-JS solution that complements Chakra UI well. Use Panda for custom styles and animations while leveraging Chakra's component library.

<style >
h3 {
  color: #90EE90; 
  
}
</style>
---
transition: slide-up
---

- UnoCSS: An atomic CSS engine. While there's some overlap with Chakra's utility props, UnoCSS can be used for additional utility classes not covered by Chakra.
<br><br>
### Example combining Chakra UI and UnoCSS:
```
import { Box } from '@chakra-ui/react'

function Example() {
  return (
    <Box className="uno-custom-class" borderWidth="1px" p={4}>
      Chakra UI box with UnoCSS class
    </Box>
  )
}
```
Remember to configure your build process to work with both Chakra UI and your chosen CSS solution.
Existing component libraries can be:
- complex and difficult to learn
- inflexible for customization

<style scoped>
h3 {
  color: #90EE90; 
  
}
</style>

---
transition: slide-up
---

### Chakra UI
A  UI component focused on:
- Ease of use
- Flexibility
- Modern design 
<br>
<br>
### Chakra UI solutions
- simple and accessible components
- responsive design
- Easy customization with a well- documented API

<style scoped >
h3 {
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
