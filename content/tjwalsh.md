---
title: TJ Walsh
---

{{< rawhtml >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Article Title - Yale Law Journal Style</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="article-title">The Title of the Article</h1>
    <p class="author">by Author Name</p>
  </header>
  <main>
    <section class="content">
      <article>
        <p>This is the introductory paragraph. Here's a citation reference<sup><a href="#fn1" class="footnote-link">1</a></sup> that can be viewed on the right side or clicked to see the full footnote.</p>

        <p>More text continues with other citations<sup><a href="#fn2" class="footnote-link">2</a></sup> and relevant content that makes up the body of the article.</p>
      </article>
      
      <!-- Right Side Footnotes -->
      <aside class="footnotes">
        <div id="fn1" class="footnote-summary">
          <span class="footnote-number">1</span> Short footnote summary for quick reference.
        </div>
        <div id="fn2" class="footnote-summary">
          <span class="footnote-number">2</span> Another short summary for the second footnote.
        </div>
      </aside>
    </section>
  </main>
  
  <!-- Modal for Full Footnote Details -->
  <div id="footnote-modal" class="modal">
    <div class="modal-content">
      <span class="close">&times;</span>
      <p id="full-footnote-text"></p>
    </div>
  </div>
  
  <script src="script.js"></script>
</body>
</html>
{{< /rawhtml >}}

<style>
body {
  font-family: "Georgia", serif;
  margin: 0;
  padding: 0;
  background-color: #f8f8f8;
  color: #333;
  line-height: 1.6;
}

.article-title {
  font-size: 2rem;
  margin: 0;
}

.author {
  font-size: 1rem;
  color: #666;
}

main {
  display: flex;
  justify-content: center;
  padding: 2rem;
}

.content {
  display: flex;
  width: 60rem;
  max-width: 100%;
}

article {
  flex: 3;
  padding-right: 2rem;
}

aside.footnotes {
  flex: 1;
  padding-left: 1rem;
  border-left: 1px solid #ccc;
}

.footnote-link {
  color: #0077cc;
  text-decoration: none;
  cursor: pointer;
}

.footnote-summary {
  font-size: 0.9rem;
  margin-bottom: 1rem;
  color: #555;
}

.footnote-number {
  font-weight: bold;
  color: #333;
}

/* Modal Styling */
.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  padding-top: 10%;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.7);
}

.modal-content {
  background-color: #fefefe;
  margin: auto;
  padding: 2rem;
  border-radius: 5px;
  width: 60%;
  max-width: 40rem;
}

.close {
  color: #aaa;
  float: right;
  font-size: 1.5rem;
  font-weight: bold;
  cursor: pointer;
}

.close:hover {
  color: #333;
}

</style>