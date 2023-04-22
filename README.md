<!-- Credits to Devicon (https://devicon.dev/) for icons used throughout! -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">

<!-- Custom "Hello, World!" Banner (Made with Canva) -->

![Hello, World! Banner](hello-world-banner-v2.png)

<!-- "Base"/HTML-related Stack: VS Code, Git, HTML, Markdown, JSON, Bash -->
<div align="center">
  <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg">
  &nbsp; &nbsp;

  <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg">
  &nbsp; &nbsp;

  <img width="57px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain-wordmark.svg">
  &nbsp; &nbsp;

  <img width="52px" src="https://raw.githubusercontent.com/blogtheristo/blogtheristo/main/icon/json.png">
  &nbsp; &nbsp;

  <img width="59px" color="white" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Antu_text-x-markdown.svg/1024px-Antu_text-x-markdown.svg.png">
  &nbsp; &nbsp;

  <img width="53px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-plain.svg">
  &nbsp; &nbsp;
</div>
<br>

```html
<h2>About Me</h2>
<ul>
  <li class="bio">Enjoys building and breaking in equal measure</li>
  <li class="tech-stack">Always learning, but prefers personal projects</li>
  <li class="learning-queue">TypeScript, Vue 3, Python, Flask, MongoDB</li>
  <li class="death-to-pineapples">Despises pineapple on pizza</li>
  <!-- <li class="self-ref-humour">Feels obliged to include an About Me</li> -->
</ul>
```

<!-- "Styling"/CSS-related Stack: Draw.io, CSS, Sass, Vuetify -->
<div align="center">
  <img width="48px" src="https://www3.technologyevaluation.com/getattachment/830bde8d-2d8d-56ff-a20e-a3ad40f6139b/logo.png?source=tw2&ext=.png">
  &nbsp; &nbsp;

  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain-wordmark.svg">
  &nbsp; &nbsp;

  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg">
  &nbsp; &nbsp;

  <img width="52px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuetify/vuetify-original.svg">
  &nbsp; &nbsp;
</div>
<br>

```css
* {
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  padding: 0;
  margin: 0;
}

h2 {
  font-size: 32px;
  font-weight: bold;
}

.tech-stack {
  display: flex !important;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap-reverse;
}

.learning-queue {
  list-style: disc;
}

.death-to-pineapples {
  color: yellow;
  padding: 10px;
  border: 2px groove orange !important;
  border-radius: 5px;
}
```

<!-- "Programming"/JavaScript-related Stack: C++, C#, Python, JavaScript -->
<div align="center">
  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-plain.svg">
  &nbsp; &nbsp;

  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-plain.svg">
  &nbsp; &nbsp;

  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg">
  &nbsp; &nbsp;

  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg">
  &nbsp; &nbsp;

  <img width="55px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
  &nbsp; &nbsp;
</div>
<br>

```js
const sections = [
  '.bio',
  '.tech-stack',
  '.learning-queue',
  '.death-to-pineapples',
];

sections.forEach(section => {
  const sectionElement = document.querySelector(section);
  sectionElement.addEventListener('mouseover', () => {
    sectionElement.style.backgroundColor = getBackgroundColour(section);
  });
});

function getBackgroundColour(section) {
  switch (section) {
    case '.bio':
      return 'green';
    case '.tech-stack':
      return 'darkblue';
    case '.learning-queue':
      return 'purple';
    case '.death-to-pineapples':
      return 'black';
  }
}
```

<!-- Miscellaneous Stack: ??? -->
<div align="center">

</div>
<br>

<!-- Custom Contact Info Banner (Made with Canva) -->
<img src="contact-info-design.png" alt="Contact Info Banner">

<!-- CSS code explaining more specifics, adding "flavour" and "styling" to simple and bland HTML stuff from top
style classes from above html!!! -->
<!-- JavaScript to explain functionality (projects, future improvements, learning)-->
<!-- Chaos engineering, custom gifs, open source contributer, professional yak shaver, cloud tech  -->
<!-- 1. About me (HTML)
1. Tech stack (CSS)
2. Learning Queue (JavaScript?)
3. Contact info (github activity overview design?) -->
