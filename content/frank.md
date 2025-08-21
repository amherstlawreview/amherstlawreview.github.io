---
title: Adam Frank
---

{{< rawhtml >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Issue 8 Article</title>
</head>
<body>
  <header>
    <div class="article-header">
      <h1 class="article-title">The AI-Authorship Copyright Question: How a Court Case and a Bureaucratic Decision Changed Intellectual Property Law</h1>
      <p class="author">Adam Frank – Columbia University</p>
    </div>
  </header>
  <main>
    <section class="content">
      <article>
        <p>Content coming soon.</p>
      </article>

      <!-- Footnotes -->
      <aside class="footnotes"></aside>
    </section>
  </main>

  <!-- Modal for Footnote Details -->
  <div id="footnote-modal" class="modal" aria-hidden="true" role="dialog" aria-label="Footnote">
    <div class="modal-content">
      <button class="close" aria-label="Close">&times;</button>
      <div id="full-footnote-text"></div>
    </div>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', function () {
      var modal = document.getElementById('footnote-modal');
      var textTarget = document.getElementById('full-footnote-text');
      var closeBtn = modal ? modal.querySelector('.close') : null;

      function openFootnote(id) {
        var fn = document.getElementById(id);
        if (fn && modal && textTarget) {
          textTarget.innerHTML = fn.innerHTML;
          modal.style.display = 'block';
          modal.setAttribute('aria-hidden', 'false');
        }
      }

      document.querySelectorAll('.footnote-link').forEach(function (a) {
        a.addEventListener('click', function (e) {
          e.preventDefault();
          var href = a.getAttribute('href') || '';
          var id = href.replace('#', '');
          openFootnote(id);
        });
      });

      function closeModal() {
        if (modal) {
          modal.style.display = 'none';
          modal.setAttribute('aria-hidden', 'true');
          if (textTarget) textTarget.innerHTML = '';
        }
      }

      if (closeBtn) {
        closeBtn.addEventListener('click', closeModal);
      }

      if (modal) {
        modal.addEventListener('click', function (e) {
          if (e.target === modal) closeModal();
        });
      }

      document.addEventListener('keydown', function (e) {
        if (e.key === 'Escape') closeModal();
      });
    });
  </script>

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
  line-height: 1.5;
}
.article-header { padding: 0 1rem; max-width: 60rem; margin: 0 auto; }
.article-title { font-size: 1.6rem; margin: 0; }
.author { font-size: 0.8rem; color: #FFFFFF; }
main { display: block; padding: 2rem 1rem; }
.content { display: block; width: 60rem; max-width: 100%; margin: 0 auto; }
article { padding-right: 0; }
aside.footnotes { margin-top: 3rem; padding-top: 1rem; border-top: 1px solid #e0e0e0; }
.footnote-link { color: #666; font-size: 0.75rem; text-decoration: none; cursor: pointer; vertical-align: super; line-height: 0; }
.footnote-link:hover { color: #333; }
.footnote-summary { font-size: 0.9rem; margin-bottom: 0.75rem; color: #555; line-height: 1.4; }
.footnote-number { font-size: 0.75rem; font-weight: bold; color: #666; margin-right: 0.4rem; }
.modal { display: none; position: fixed; z-index: 1000; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.6); }
.modal-content { background-color: #fff; margin: 10% auto; padding: 1.25rem 1.5rem; border-radius: 6px; width: 60rem; max-width: calc(100% - 2rem); box-shadow: 0 10px 30px rgba(0,0,0,0.25); }
.close { background: none; border: none; color: #666; font-size: 1.5rem; cursor: pointer; float: right; }
.close:hover { color: #000; }
</style>


