# freeCodeCamp_magazine
In this course, you'll build a magazine article. You'll learn how to use CSS Grid, including concepts like grid rows and grid columns.

```html
<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
    </body>
</html>
```

```html
    <title>Magazine</title>
    <link
      href="https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap"
      rel="stylesheet"/>
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"/>
    <link rel="stylesheet" href="styles.css"/>
```

```html
    <main>
      <section class="heading"></section>
    </main>
```

```html
      <section class="heading">
        <header class="hero">
          <img
            src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
            alt="freecodecamp logo"
            loading="lazy"
            class="hero-img"
          />
        </header>
      </section>
```

```html
          <h1 class="hero-title">OUR NEW CURRICULUM</h1>
          <p class="hero-subtitle">Our efforts to restructure our curriculum with a more project-based focus</p>
```

```html
          <img
            src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
            alt="freecodecamp logo"
            loading="lazy"
            class="hero-img" width="400"
          />
```

```html
        <div class="author">
          <p class="author-name">By <a href="https://freecodecamp.org" target="_blank">freeCodeCamp</a>
          </p>
          <p class="publish-date">March 7, 2019</p>
        </div>
```

```html
            <a href="https://freecodecamp.org" target="_blank" rel="noreferrer">freeCodeCamp</a>
```

```html
        <div class="social-icons">
          <a href="https://www.facebook.com/freecodecamp"></a>
          <a href="https://twitter.com/freecodecamp"></a>
          <a href="https://instagram.com/freecodecamp"></a>
          <a href="https://www.linkedin.com/school/free-code-camp"></a>
          <a href="https://www.youtube.com/freecodecamp"></a>
        </div>
```

```html
        <div class="social-icons">
          <a href="https://www.facebook.com/freecodecamp/">
            <i class="fab fa-facebook-f"></i>
          </a>
          <a href="https://twitter.com/freecodecamp/">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="https://instagram.com/freecodecamp">
            <i class="fab fa-instagram"></i>
          </a> 
          <a href="https://www.linkedin.com/school/free-code-camp/">
            <i class="fab fa-linkedin-in"></i>
          </a>
          <a href="https://www.youtube.com/freecodecamp">
            <i class="fab fa-youtube"></i>
          </a>
        </div>
```

```html
      <section class="text">
        <p class="first-paragraph">
          Soon the freeCodeCamp curriculum will be 100% project-driven learning. 
          Instead of a series of coding challenges, you'll learn through building projects - step by step. 
          Before we get into the details, let me emphasize: we are not changing the certifications. 
          All 6 certifications will still have the same 5 required projects. 
          We are only changing the optional coding challenges.
        </p>
      </section>
```

```html
        <p>
          After years - years - of pondering these two problems and how to solve them, 
          I slipped, hit my head on the sink, and when I came to I had a revelation! 
          A vision! A picture in my head! A picture of this! 
          This is what makes time travel possible: the flux capacitor!
        </p>
```

```html
        <p>
         It wasn't as dramatic as Doc's revelation in Back to the Future. 
         It just occurred to me while I was going for a run. 
         The revelation: the entire curriculum should be a series of projects. 
         Instead of individual coding challenges, we'll just have projects, each with their own seamless series of tests. 
         Each test gives you just enough information to figure out how to get it to pass. 
         (And you can view hints if that isn't enough.)
        </p>
```

```html
        <blockquote>
          <hr />
          <p class="quote">
            The entire curriculum should be a series of projects
          </p>
          <hr />
        </blockquote>
```

```html
        <p>
          No more walls of explanatory text. No more walls of tests. Just one
          test at a time, as you build up a working project. Over the course of passing thousands of tests, you build up projects and your own understanding of coding fundamentals. There is no transition between lessons and projects, because the lessons themselves are baked into projects. And there's plenty of repetition to help you retain everything because - hey - building projects in real life has plenty of repetition.
        </p>
```

```html
        <p>
          The main design challenge is taking what is currently paragraphs of explanation and instructions and packing them into a single test description text. Each project will involve dozens of tests like this. People will be coding the entire time, rather than switching back and forth from "reading mode" to "coding mode".
        </p>
```

```html
        <p>
          Instead of a series of coding challenges, people will be in their code editor passing one test after another, quickly building up a project. People will get into a real flow state, similar to what they experience when they build the required projects at the end of each certification. They'll get that sense of forward progress right from the beginning. And freeCodeCamp will be a much smoother experience.
        </p>
```

```html
      <section class="text text-with-images">
        <article class="brief-history"></article>
        <aside class="image-wrapper"></aside>
      </section>
```

```html
        <article class="brief-history">
          <h3 class="list-title">A Brief History</h3>
          <p>Of the Curriculum</p>
          <ul class="lists"></ul>
        </article>
```

```html
          <ul class="lists">
            <li>
              <h4 class="list-subtitle">V1 - 2014</h4>
              <p>We launched freeCodeCamp with a simple list of 15 resources, including Harvard's CS50 and Stanford's Database Class.</p>
            </li>
            <li>
              <h4 class="list-subtitle">V2 - 2015</h4>
              <p>We added interactive algorithm challenges.</p>
            </li>
            <li>
              <h4 class="list-subtitle">V3 - 2015</h4>
              <p>We added our own HTML+CSS challenges (before we'd been relying on General Assembly's Dash course for these).</p>
            </li>
            <li>
              <h4 class="list-subtitle">V4 - 2016</h4>
              <p>We expanded the curriculum to 3 certifications, including Front End, Back End, and Data Visualization. They each had 10 required projects, but only the Front End section had its own challenges. For the other certs, we were still using external resources like Node School.</p>
            </li>
            <li>
              <h4 class="list-subtitle">V5 - 2017</h4>
              <p>We added the back end and data visualization challenges.</p>
            </li>
            <li>
              <h4 class="list-subtitle">V6 - 2018</h4>
              <p>We launched 6 new certifications to replace our old ones. This was the biggest curriculum improvement to date.</p>
            </li>
          </ul>
```

```html
        <aside class="image-wrapper">
          <img>
          <img>
          <blockquote class="image-quote"></blockquote>
          <img>
        </aside>
```

```html
        <aside class="image-wrapper">
          <img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" alt="image of the quote machine project" class="image-1" loading="lazy" width="600" height="400"/>
          <img />
          <blockquote class="image-quote"></blockquote>
          <img />
        </aside>
```

```html
        <aside class="image-wrapper">
          <img
            src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png"
            alt="image of the quote machine project"
            loading="lazy"
            class="image-1"
            width="600"
            height="400"
          />
          <img
            src="https://cdn.freecodecamp.org/testable-projects-fcc/images/calc.png"
            alt="image of a calculator project"
            loading="lazy"
            class="image-2"
            width="400"
            height="400"
          />
          <blockquote class="image-quote"></blockquote>
          <img />
        </aside>
```

```html
          <img
            src="https://cdn.freecodecamp.org/testable-projects-fcc/images/survey-form-background.jpeg"
            alt="four people working on code"
            loading="lazy"
            class="image-3"
            width="600"
            height="400"
          />
```

```html
          <blockquote class="image-quote">
            <hr>
            <p class="quote">The millions of people who are learning to code through freeCodeCamp will have an even better resource to help them learn these fundamentals.</p>
            <hr>
          </blockquote>
```

```css
*,
::before,
::after {
  margin: 0;
  padding: 0;
}
```

```css
html {
  font-size: 62.5%;
  box-sizing: border-box;
}
```

```css
body {
  font-family: Baskervville, serif;
  color: linen;
  background-color: rgb(20, 30, 40);
}
```

```css
h1 {
  font-family: Anton, sans-serif;
}
```

```css
h2, h3, h4, h5, h6 {
  font-family: Raleway, sans-serif;
}
```

```css
a {
  text-decoration: none;
  color: linen;
}
```

```css
main {
  display: grid;
}
```

```css
main {
  display: grid;
  grid-template-columns: 1fr 94rem 1fr;
}
```

```css
main {
  display: grid;
  grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);
}
```

```css
main {
  display: grid;
  grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);
  row-gap: 3rem;
}
```

```css
.heading {
  grid-column: 2 / 3;
}
```

```css
.text {
  grid-column: 2 / 3;
}
```

```css
.heading {
  grid-column: 2 / 3;
  display: grid;
}
```

```css
.heading {
  grid-column: 2 / 3;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
```

```css
.heading {
  grid-column: 2 / 3;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  row-gap: 1.5rem;
}
```

```css
.hero {
  grid-column: 1 / -1;
}
```

```css
.hero {
  grid-column: 1 / -1;
  position: relative;
}
```

```html
          <img
            src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
            alt="freecodecamp logo"
            loading="lazy"
            class="hero-img"
          />
          <h1 class="hero-title">OUR NEW CURRICULUM</h1>
          <p class="hero-subtitle">
            Our efforts to restructure our curriculum with a more project-based
            focus
          </p>
```

```css
img {
  width: 100%;
  object-fit: cover;
}
```

```css
.hero-title {
  text-align: center;
  color: orangered;
  font-size: 8rem;
}
```

```css
.hero-subtitle {
  font-size: 2.4rem;
  color: orangered;
  text-align: center;
}
```

```css
.author {
  font-size: 2rem;
  font-family: Raleway, sans-serif;
}
```

```css
.author-name a:hover {
  background-color: #306203;
}
```

```css
.publish-date {
  color: rgba(255, 255, 255, 0.5);
}
```

```css
.social-icons {
  display: grid;
  font-size: 3rem;
}
```

```css
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-template-columns: repeat(5, 1fr);
}
```

```css
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-auto-flow: column;
}
```

```css
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-auto-columns: 1fr;
  grid-auto-flow: column;
}
```

```css
.social-icons {
  display: grid;
  font-size: 3rem;
  grid-template-columns: repeat(5, 1fr);
  grid-auto-flow: column;
  grid-auto-columns: 1fr;
  align-items: center;
}
```

```css
.text {
  grid-column: 2 / 3;
  font-size: 1.8rem;
  letter-spacing: 0.6px;
}
```

```css
.text {
  grid-column: 2 / 3;
  font-size: 1.8rem;
  letter-spacing: 0.6px;
  column-width: 25rem;
}
```

```css
.text {
  grid-column: 2 / 3;
  font-size: 1.8rem;
  letter-spacing: 0.6px;
  column-width: 25rem;
  text-align: justify;
}
```

```css
.first-paragraph::first-letter {
  font-size: 6rem;
  color: orangered;
}
```

```css
.first-paragraph::first-letter {
  font-size: 6rem;
  color: orangered;
  float: left;
  margin-right: 1rem;
}
```

```css
hr {
  margin: 1.5rem 0;
}
```

```css
hr {
  margin: 1.5rem 0;
  border: 1px solid rgba(120, 120, 120, 0.6);
}
```

```css
.quote {
  color: #00beef;
  font-size: 2.4rem;
  text-align: center;
}
```

```css
.quote {
  color: #00beef;
  font-size: 2.4rem;
  text-align: center;
  font-family: Raleway, sans-serif;
}
```

```css
.quote::before {
  content: '" ';
}

.quote::after {
  content: ' "';
}
```

```css
.text-with-images {
  display: grid;
}
```

```css
.text-with-images {
  display: grid;
  grid-template-columns: 1fr 2fr;
  column-gap: 3rem;
}
```

```css
.text-with-images {
  display: grid;
  grid-template-columns: 1fr 2fr;
  column-gap: 3rem;
  margin-bottom: 3rem;
}
```

```css
.lists {
  list-style-type: none;
}
```

```css
.lists li {
  margin-bottom: 1.5rem;
}
```

```css
.list-title, .list-subtitle {
  color: #00beef;
}
```

```css
.image-wrapper {
  display: grid;
}
```

```css
.image-wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: repeat(3, min-content);
}
```

```css
.image-wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: repeat(3, min-content);
  gap: 2rem;
}
```

```css
.image-wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: repeat(3, min-content);
  gap: 2rem;
  place-items: center;
}
```

```css
.image-1, .image-3 {
  grid-column: 1 / -1;
}
```

```css
@media only screen and (max-width: 720px) {
  .image-wrapper {
    grid-template-columns: 1fr;
  }
}
```

```css
@media only screen and (max-width: 600px) {
  .text-with-images {
    grid-template-columns: 1fr;
  }
}
```

```css
@media only screen and (max-width: 550px) {
  .hero-title {
    font-size: 6rem;
  }
  .hero-subtitle,
  .author,
  .quote,
  .list-title {
    font-size: 1.8rem;
  }
  .social-icons {
    font-size: 2rem;
  }
  .text {
    font-size: 1.6rem;
  }
}
```

```css
@media only screen and (max-width: 420px) {
  .hero-title {
    font-size: 4.5rem;
  }
}
```