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
    <div class="article-header">
      <h1 class="article-title">Aesthetics for the Public Good: The Fifth Amendment’s Takings Clause and Development Restriction Policies</h1>
      <p class="author">Thomas J. Walsh – The University of Alabama</p>
    </div>
  </header>
  <main>
    <section class="content">
      <article>
        <p>As stated by the Takings Clause of the Fifth Amendment, it is not permissible that “private property be taken for public use, without just compensation”.<sup><a href="#fn1" class="footnote-link">1</a></sup> <sup><a href="#fn2" class="footnote-link">2</a></sup> The Fourteenth Amendment extends these rights from the federal government to the states, establishing that it is likewise impermissible for “any State to deprive any person of life, liberty, or property, without due process of law.”<sup><a href="#fn3" class="footnote-link">3</a></sup> The Takings Clause specifies that one whose property is taken by the government for public use is entitled to just compensation, but it fails to specify further details regarding its implementation or capacities.<sup><a href="#fn4" class="footnote-link">4</a></sup> <sup><a href="#fn5" class="footnote-link">5</a></sup></p>
      </article>
      
      <!-- Right Side Footnotes -->
  <aside class="footnotes">
        <div id="fn1" class="footnote-summary">
          <span class="footnote-number">1</span> Cornell Law School, “Takings,” Legal Information Institute, https://www.law.cornell.edu/wex/takings. Accessed February 15, 2024.
        </div>
        <div id="fn2" class="footnote-summary">
          <span class="footnote-number">2</span> Cornell Law School, “Fifth Amendment,” Legal Information Institute, https://www.law.cornell.edu/constitution/fifth_amendment. Accessed February 15, 2024.
        </div>
        <div id="fn3" class="footnote-summary">
          <span class="footnote-number">3</span> Cornell Law School, “Fourteenth Amendment,” Legal Information Institute, https://www.law.cornell.edu/constitution/amendmentxiv. Accessed February 15, 2024.
        </div>
        <div id="fn4" class="footnote-summary">
          <span class="footnote-number">4</span> US Department of Housing and Urban Development, “Eminent Domain.” Accessed February 15, 2024.
        </div>
        <div id="fn5" class="footnote-summary">
          <span class="footnote-number">5</span> US Department of Justice, “Fifth Amendment Takings Law,” https://www.justice.gov/enrd/natural-resources-sectionfifth-amendment-takings-law#:~:text=Also%20known%20as%20the%20%22Takingsthe%20payment%20of%20just%20compensation. Accessed February 15, 2024.
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

.article-header {
  padding: 0 1rem; /* Adds left and right padding */
  max-width: 60rem;
  margin: 0 auto;
}

.article-title {
  font-size: 1.6rem;
  margin: 0;
}

.author {
  font-size: 0.8rem;
  color: #FFFFFF;
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