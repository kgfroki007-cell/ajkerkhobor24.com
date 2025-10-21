<!--
AajkerKhabar24 - Free Bengali News Website Template
Files included below (copy each to separate files when uploading to GitHub):

/ index.html
/ politics.html
/ sports.html
/ entertainment.html
/ tech.html
/ international.html
/ contact.html
/ css/styles.css
/ js/script.js
/ README.md

Instructions: Create a new GitHub repository (public), upload these files preserving folders (css/, js/), then enable GitHub Pages from the main branch. See README.md for steps.
--> 

/* ===== FILE: index.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>আজকের খবর ২৪</title>
  <meta name="description" content="আজকের খবর ২৪ — সর্বশেষ বাংলাদেশ ও আন্তর্জাতিক খবর। রাজনীতি, খেলা, বিনোদন, প্রযুক্তি।">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero container">
      <article class="hero-article">
        <img src="https://source.unsplash.com/1200x600/?news,bangladesh" alt="প্রধান খবর">
        <div class="hero-text">
          <h1>প্রধান শিরোনাম: দেশের বর্ষার মধ্যে জরুরি নির্মাণ প্রকল্প অনুমোদন</h1>
          <p>সংক্ষিপ্ত বিবরণ — সরকারের সাম্প্রতিক সিদ্ধান্ত ও প্রভাব নিয়ে পড়ুন।</p>
          <a class="btn" href="#">বিস্তারিত পড়ুন</a>
        </div>
      </article>

      <aside class="top-quick-news">
        <h3>সর্বশেষ সংবাদ</h3>
        <ul>
          <li><a href="#">রাজধানীতে নতুন যানবাহন নীতি ঘোষনা</a></li>
          <li><a href="#">ক্রিকেটারদের নতুন চুক্তি স্বীকৃত</a></li>
          <li><a href="#">টেক স্টার্টআপ বিনিয়োগ বৃদ্ধি পাচ্ছে</a></li>
          <li><a href="#">আন্তর্জাতিক কূটনৈতিক সফরে উন্নতি</a></li>
        </ul>
      </aside>
    </section>

    <section class="container grid-3 latest-section">
      <div class="card">
        <img src="https://source.unsplash.com/600x400/?politics" alt="রাজনীতি">
        <h4>রাজনীতি: সংসদে বিতর্কিত বাজেট আলোচনা</h4>
        <p>সংক্ষিপ্ত সারসংক্ষেপ — কি হয়েছে এবং পরবর্তী ধাপ?</p>
        <a href="politics.html">আরও</a>
      </div>

      <div class="card">
        <img src="https://source.unsplash.com/600x400/?sports" alt="খেলা">
        <h4>খেলা: সিরিজের গুরুত্বপূর্ণ জয়</h4>
        <p>ক্রিকেটাররা দলকে জয়ে নেতৃত্ব দিয়েছেন — মিরাকেল ম্যাচ।</p>
        <a href="sports.html">আরও</a>
      </div>

      <div class="card">
        <img src="https://source.unsplash.com/600x400/?technology" alt="প্রযুক্তি">
        <h4>প্রযুক্তি: নতুন আপডেট উদ্বোধন</h4>
        <p>দেশি স্টার্টআপ একটি নতুন অ্যাপ লঞ্চ করেছে যা সমস্যার সমাধান করবে।</p>
        <a href="tech.html">আরও</a>
      </div>
    </section>

    <section class="container categories">
      <h2>বিভাগসমূহ</h2>
      <div class="category-grid">
        <a class="cat" href="politics.html">রাজনীতি</a>
        <a class="cat" href="sports.html">খেলা</a>
        <a class="cat" href="entertainment.html">বিনোদন</a>
        <a class="cat" href="tech.html">প্রযুক্তি</a>
        <a class="cat" href="international.html">আন্তর্জাতিক</a>
      </div>
    </section>

    <section class="container opinion">
      <h2>সম্পাদকীয়</h2>
      <article class="opinion-card">
        <h3>দেশের অর্থনীতির এক নজর</h3>
        <p>বিশ্লেষণাত্মক টুকরা — শিক্ষিত মতামত এবং তথ্যভিত্তিক মন্তব্য।</p>
        <a href="#">আরও</a>
      </article>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <h4>আজকের খবর ২৪</h4>
        <p>সর্বশেষ সংবাদ ও বিশ্লেষণ — বিশ্বস্ত এবং নিরপেক্ষ।</p>
      </div>
      <div>
        <h5>প্রধান বিভাগ</h5>
        <ul>
          <li><a href="politics.html">রাজনীতি</a></li>
          <li><a href="sports.html">খেলা</a></li>
          <li><a href="entertainment.html">বিনোদন</a></li>
        </ul>
      </div>
      <div>
        <h5>যোগাযোগ</h5>
        <p>ইমেইল: contact@ajkerkhobor24.example</p>
      </div>
    </div>
    <div class="copyright">© <span id="year"></span> আজকের খবর ২৪ — সব অধিকার সংরক্ষিত</div>
  </footer>

  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: politics.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>রাজনীতি - আজকের খবর ২৪</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle2" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav2">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>রাজনীতি</h1>
    <section class="list">
      <article class="list-item">
        <img src="https://source.unsplash.com/900x600/?parliament" alt="রাজনীতি">
        <div>
          <h3>সংসদে নতুন প্রস্তাব উত্থাপিত</h3>
          <p>বিস্তৃত বর্ণনা — প্রস্তাবের উদ্দেশ্য ও প্রভাব।</p>
          <a href="#">আরও পড়ুন</a>
        </div>
      </article>

      <article class="list-item">
        <img src="https://source.unsplash.com/900x600/?election" alt="নির্বাচন">
        <div>
          <h3>নির্বাচন সংক্রান্ত জরুরি আপডেট</h3>
          <p>নগরীতে নির্বাচন প্রস্তুতি ও প্রার্থীদের কার্যক্রম।</p>
          <a href="#">আরও পড়ুন</a>
        </div>
      </article>
    </section>
  </main>

  <footer class="site-footer simple-footer">
    <div class="container">© <span id="year2"></span> আজকের খবর ২৪</div>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: sports.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>খেলা - আজকের খবর ২৪</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle3" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav3">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>খেলা</h1>
    <section class="list">
      <article class="list-item">
        <img src="https://source.unsplash.com/900x600/?cricket" alt="ক্রিকেট">
        <div>
          <h3>ম্যাচ রিপোর্ট: সেরা পারফরম্যান্স</h3>
          <p>দলের বিশ্লেষণ এবং পরবর্তী ম্যাচ সম্পর্কে তথ্য।</p>
          <a href="#">আরও পড়ুন</a>
        </div>
      </article>
    </section>
  </main>

  <footer class="site-footer simple-footer">
    <div class="container">© <span id="year3"></span> আজকের খবর ২৪</div>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: entertainment.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>বিনোদন - আজকের খবর ২৪</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle4" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav4">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>বিনোদন</h1>
    <section class="list">
      <article class="list-item">
        <img src="https://source.unsplash.com/900x600/?movie,celebrity" alt="বিনোদন">
        <div>
          <h3>নতুন সিনেমা রিভিউ</h3>
          <p>চিত্রনাট্য, অভিনয় এবং দর্শকের প্রতিক্রিয়া নিয়ে বিশ্লেষণ।</p>
          <a href="#">আরও পড়ুন</a>
        </div>
      </article>
    </section>
  </main>

  <footer class="site-footer simple-footer">
    <div class="container">© <span id="year4"></span> আজকের খবর ২৪</div>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: tech.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>প্রযুক্তি - আজকের খবর ২৪</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle5" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav5">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>প্রযুক্তি</h1>
    <section class="list">
      <article class="list-item">
        <img src="https://source.unsplash.com/900x600/?startup,tech" alt="প্রযুক্তি">
        <div>
          <h3>স্টার্টআপ বিনিয়োগ বৃদ্ধি</h3>
          <p>দেশি স্টার্টআপগুলোতে নতুন বিনিয়োগ ও ভবিষ্যৎ পরিকল্পনা।</p>
          <a href="#">আরও পড়ুন</a>
        </div>
      </article>
    </section>
  </main>

  <footer class="site-footer simple-footer">
    <div class="container">© <span id="year5"></span> আজকের খবর ২৪</div>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: international.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>আন্তর্জাতিক - আজকের খবর ২৪</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle6" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav6">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <h1>আন্তর্জাতিক</h1>
    <section class="list">
      <article class="list-item">
        <img src="https://source.unsplash.com/900x600/?world,news" alt="আন্তর্জাতিক">
        <div>
          <h3>আন্তর্জাতিক কূটনীতিতে নতুন সমঝোতা</h3>
          <p>শব্দ্য বিবরণ — দ্বিপাক্ষিক সম্পর্কের উন্নয়ন।</p>
          <a href="#">আরও পড়ুন</a>
        </div>
      </article>
    </section>
  </main>

  <footer class="site-footer simple-footer">
    <div class="container">© <span id="year6"></span> আজকের খবর ২৪</div>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: contact.html ===== */
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>যোগাযোগ - আজকের খবর ২৪</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container nav-container">
      <a class="brand" href="index.html">আজকের খবর ২৪</a>
      <button id="navToggle7" class="nav-toggle" aria-label="মেনু">☰</button>
      <nav class="main-nav" id="mainNav7">
        <a href="index.html">হোম</a>
        <a href="politics.html">রাজনীতি</a>
        <a href="sports.html">খেলা</a>
        <a href="entertainment.html">বিনোদন</a>
        <a href="tech.html">প্রযুক্তি</a>
        <a href="international.html">আন্তর্জাতিক</a>
        <a href="contact.html">যোগাযোগ</a>
      </nav>
    </div>
  </header>

  <main class="container contact-page">
    <h1>যোগাযোগ</h1>
    <p>আপনি আমাদের কাছে সংবাদ পাঠাতে বা যোগাযোগ করতে নিচের ফর্মটি ব্যবহার করতে পারেন — (এই ফর্মটি ডাইনামিক নয়; GitHub Pages-এ কাজ করার জন্য ব্যাকএন্ড প্রয়োজন)</p>
    <form class="contact-form">
      <label>নাম
        <input type="text" placeholder="আপনার নাম">
      </label>
      <label>ইমেইল
        <input type="email" placeholder="your@email.com">
      </label>
      <label>বার্তা
        <textarea placeholder="আপনার বার্তা"></textarea>
      </label>
      <button type="submit" class="btn">পাঠান</button>
    </form>
  </main>

  <footer class="site-footer simple-footer">
    <div class="container">© <span id="year7"></span> আজকের খবর ২৪</div>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>

/* ===== FILE: css/styles.css ===== */
/* Simple responsive style for Bengali news template */
:root{
  --accent:#d62828;
  --dark:#0b1320;
  --muted:#6b7280;
  --bg:#ffffff;
  --maxw:1100px;
}
*{box-sizing:border-box}
body{font-family:'Noto Sans Bengali', system-ui, Arial, sans-serif;margin:0;color:var(--dark);background:var(--bg);line-height:1.5}
.container{max-width:var(--maxw);margin:0 auto;padding:16px}
.site-header{background:#fff;border-bottom:1px solid #eee;position:sticky;top:0;z-index:50}
.nav-container{display:flex;align-items:center;justify-content:space-between}
.brand{font-weight:700;font-size:20px;color:var(--accent);text-decoration:none}
.main-nav{display:flex;gap:12px}
.main-nav a{color:var(--dark);text-decoration:none;padding:10px}
.nav-toggle{display:none;background:none;border:0;font-size:22px}
.hero{display:flex;gap:16px;padding:18px 0}
.hero-article{flex:2;position:relative}
.hero-article img{width:100%;height:auto;border-radius:6px}
.hero-text{position:absolute;left:20px;bottom:20px;background:rgba(0,0,0,0.5);color:#fff;padding:16px;border-radius:6px;max-width:70%}
.top-quick-news{flex:1;background:#f8f8f8;padding:12px;border-radius:6px}
.grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:20px}
.card{background:#fff;border:1px solid #eee;padding:12px;border-radius:6px}
.card img{width:100%;height:180px;object-fit:cover;border-radius:6px}
.card h4{margin:10px 0}
.btn{display:inline-block;margin-top:8px;padding:8px 12px;background:var(--accent);color:#fff;text-decoration:none;border-radius:6px}
.categories{margin-top:28px}
.category-grid{display:flex;flex-wrap:wrap;gap:8px}
.cat{background:#f1f1f1;padding:10px 14px;border-radius:6px;text-decoration:none;color:var(--dark)}
.opinion{margin-top:28px}
.opinion-card{background:#fff;padding:12px;border:1px solid #eee;border-radius:6px}
.site-footer{background:#fafafa;border-top:1px solid #eee;padding:20px 0;margin-top:28px}
.footer-grid{display:flex;gap:24px;justify-content:space-between}
.simple-footer{padding:16px;text-align:center}
.list{display:flex;flex-direction:column;gap:18px;margin-top:12px}
.list-item{display:flex;gap:12px;background:#fff;padding:12px;border-radius:6px;border:1px solid #eee}
.list-item img{width:260px;height:160px;object-fit:cover;border-radius:6px}
.contact-page .contact-form{max-width:700px;display:flex;flex-direction:column;gap:8px}
.contact-form input,.contact-form textarea{padding:10px;border:1px solid #ddd;border-radius:6px;width:100%}
footer .copyright{text-align:center;padding:10px;color:#666}
@media (max-width:900px){.grid-3{grid-template-columns:repeat(2,1fr)}.hero{flex-direction:column}.hero-text{position:static;background:linear-gradient(180deg,rgba(0,0,0,0.55),rgba(0,0,0,0.25));color:#fff;padding:12px;border-radius:6px}}
@media (max-width:700px){.grid-3{grid-template-columns:1fr}.main-nav{display:none;flex-direction:column;background:#fff;position:absolute;right:16px;top:60px;padding:12px;border-radius:6px;box-shadow:0 6px 18px rgba(0,0,0,0.08)}.nav-toggle{display:block}.footer-grid{flex-direction:column}.list-item{flex-direction:column}.list-item img{width:100%;height:200px}}

/* small helpers */
.hidden{display:none}

/* ===== FILE: js/script.js ===== */
// Small script for mobile menu and year
(function(){
  const toggle = document.getElementById('navToggle');
  const nav = document.getElementById('mainNav');
  if(toggle && nav){
    toggle.addEventListener('click', ()=>{
      nav.classList.toggle('visible');
      // simple toggle: change display
      if(nav.style.display==='flex') nav.style.display='none'; else nav.style.display='flex';
      nav.style.flexDirection = 'column';
    });
  }
  // replicate for pages with different toggle IDs
  ['navToggle2','navToggle3','navToggle4','navToggle5','navToggle6','navToggle7'].forEach(id=>{
    const t = document.getElementById(id);
    const n = document.getElementById('mainNav' + id.slice(-1));
    if(t && n){
      t.addEventListener('click', ()=>{
        if(n.style.display==='flex') n.style.display='none'; else n.style.display='flex';
        n.style.flexDirection='column';
      });
    }
  });

  // set year in footer
  const years = [document.getElementById('year'),document.getElementById('year2'),document.getElementById('year3'),document.getElementById('year4'),document.getElementById('year5'),document.getElementById('year6'),document.getElementById('year7')];
  const y = new Date().getFullYear();
  years.forEach(el=>{ if(el) el.textContent = y; });
})();

/* ===== FILE: README.md ===== */
# আজকের খবর ২৪ — Static HTML Template

This is a free, responsive Bengali news website template ready to host on GitHub Pages.

## Files
- `index.html` — home page
- `politics.html`, `sports.html`, `entertainment.html`, `tech.html`, `international.html` — category pages
- `contact.html` — contact page (static form)
- `css/styles.css` — styles
- `js/script.js` — small JS for mobile menu and footer year

## Quick deploy to GitHub Pages
1. Create a new **public** repository on GitHub (e.g., `ajkerkhobor24`).
2. Upload all files and folders (keep `css/` and `js/` folders).
