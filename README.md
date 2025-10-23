
<html lang="hy">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Հայաստան — Շուտ, Պարզ, Նպատակային</title>
  <meta name="description" content="Հետաքրքիր փաստեր, տեսարժան վայրեր և օգտակար տեղեկատվություն Հայաստան երկրի և մշակույթի մասին։" />

  <!-- Սպասելիք արագության համար ամեն ինչ inline -->
  <style>
    :root{
      --bg:#fbfbfb; --card:#ffffff; --accent:#c70000; --muted:#6b6b6b;
      --radius:12px; --maxw:1000px;
    }
    html,body{height:100%}
    body{
      margin:0; -family:system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background:linear-gradient(180deg,#fff,#fbfbfb);
      color:#111; -webkit-font-smoothing:antialiased;
      line-height:1.45; display:flex; justify-content:center;
      padding:24px;
    }
    .wrap{width:100%;max-width:var(--maxw); background:transparent}
    header{
      display:flex; align-items:center; justify-content:space-between;
      gap:16px; margin-bottom:20px;
    }
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:52px;height:52px;border-radius:10px;
      background:linear-gradient(135deg,#e53935,#ff8a65);
      display:flex;align-items:center;justify-content:center;
      color:white;font-weight:700;font-size:20px;box-shadow:0 6px 18px rgba(0,0,0,0.08)
    }

nav{display:flex;gap:12px;flex-wrap:wrap}
    nav a{color:var(--muted);text-decoration:none;padding:8px 10px;border-radius:8px;font-weight:600}
    nav a.active, nav a:hover{background:#fff;border:1px solid #eee;color:var(--accent)}
    .hero{
      background:linear-gradient(180deg, rgba(199,0,0,0.06), transparent);
      border-radius:var(--radius); padding:18px; margin-bottom:18px;
      display:flex;gap:18px;align-items:center;flex-wrap:wrap;
    }
    .hero .left{flex:1;min-width:220px}
    .hero h1{margin:0 0 8px 0;font-size:20px}
    .hero p{margin:0;color:var(--muted)}
    .cta{margin-top:12px;display:flex;gap:10px}
    .btn{background:var(--accent);color:white;padding:8px 12px;border-radius:10px;text-decoration:none;font-weight:700}
    .btn.alt{background:transparent;color:var(--accent);border:1px solid #f2dede}

    /* Grid */
    .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
    @media (max-width:760px){ .grid{grid-template-columns:1fr} nav{display:none} header{align-items:flex-start} }

    .card{background:var(--card);border-radius:12px;padding:14px;box-shadow:0 6px 18px rgba(10,10,10,0.03)}
    .facts{display:flex;gap:10px;flex-wrap:wrap}
    .fact{flex:1;min-width:120px;padding:10px;background:linear-gradient(180deg,#fff,#fff);border-radius:10px;text-align:center}
    .fact b{display:block;font-size:20px;color:var(--accent)}

.attractions{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
    @media (max-width:960px){ .attractions{grid-template-columns:repeat(2,1fr)} }
    @media (max-width:560px){ .attractions{grid-template-columns:1fr} }

    .place{padding:12px;border-radius:10px;background:#fff;border:1px solid #f3f3f3}
    .place h3{margin:0 0 6px 0;font-size:16px}
    .place p{margin:0;font-size:13px;color:var(--muted)}

    /* timeline */
    .timeline{display:flex;flex-direction:column;gap:8px}
    .time-item{padding:10px;border-radius:8px;background:#fff;border-left:4px solid #eee}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px;padding:12px}

    /* small utilities */
    .search{display:flex;gap:8px;align-items:center}
    input[type="search"]{padding:8px 10px;border-radius:10px;border:1px solid #e8e8e8;min-width:180px}
    .map{width:100%;height:320px;border-radius:10px;overflow:hidden;border:1px solid #eee}
    .tags{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
    .tag{background:#fff;padding:6px 8px;border-radius:8px;border:1px solid #f0f0f0;font-size:13px}
  </style>
</head>
<body>
  <div class="wrap" role="main">
    <header>
      <div class="brand" aria-hidden="false">
        <div class="logo">ՀԱ</div>
        <div>
          <div style="font-weight:800">Հայաստան</div>
          <div style="font-size:12px;color:var(--muted)">Պարզ եւ արագ տեղեկատու</div>
        </div>
      </div>


  <nav aria-label="Գլխավոր մենյու">
        <a href="#about" class="active">Մասին</a>
        <a href="#facts">Փաստեր</a>
        <a href="#places">Տեսարժան վայրեր</a>
        <a href="#map">Քարտեզ</a>
        <a href="#contact">Կապ</a>
      </nav>
    </header>

    <section class="hero card" id="about">
      <div class="left">
        <h1>Բարի գալուստ Հայաստան 🇦🇲</h1>
        <p>Այս կայքը արագ, պարզ և մինիմալ ձևով ներկայացնում է օգտակար տեղեկություններ Հայաստանի մասին՝ պատմություն, արագ փաստեր ու խորհուրդներ։</p>
        <div class="cta">
          <a class="btn" href="#places">Տեսարժան վայրեր</a>
          <a class="btn alt" href="#facts">Ավելին</a>
        </div>
      </div>
      <div style="min-width:200px;max-width:280px">
        <div class="card" style="text-align:center">
          <div style="font-weight:700">Հետաքրքիր փաստ</div>
          <div style="color:var(--muted);font-size:13px;margin-top:6px">Հայաստանն առաջին երկիրն է որն ընդունել է քրիստոնեությունն որպես պետական կրոն: </div>
        </div>
      </div>
    </section>

    <div class="grid">
      <div>
        <div class="card" id="facts" aria-labelledby="facts-title">
          <h2 id="facts-title">Արագ փաստեր</h2>
          <div class="facts" style="margin-top:10px">
            <div class="fact"><b>Հայաստան
              </b><div style="font-size:13px;color:var(--muted)">29 743 կմ² </div></div>
            <div class="fact"><b>3,000+</b><div style="font-size:13px;color:var(--muted)">Հնագիտական հուշարձաններ</div></div>
            <div class="fact"><b>4090 մ</b><div style="font-size:13px;color:var(--muted)"> Արագած լեռ</div></div>
          </div>


<hr style="margin:12px 0;border:none;border-top:1px solid #f0f0f0">

          <div>
            <strong>Հայաստանի մասին</strong>
            <div style="margin-top:6px;color:var(--muted)"><ul>⦁Մայրաքաղաք-Երևան</ul>
      <ul>⦁Բնակչություն-2 930 450 մարդ (2017)</ul> 
              <ul>⦁Հիմն-Մեր Հայրենիք</ul>
              <ul>⦁Լեզու-Հայերեն</ul>
              <ul>⦁Արժույթ-Հայկական դրամ</ul>
            </div>
          </div>
        </div>

        
            
       <div class="card" style="margin-top:12px">
          <h2>Պատմական տեսք</h2>
          <div class="timeline" style="margin-top:8px">
            <div class="time-item"><strong>Ք.ա. 9-րդ դ.</strong> — Վանի թագավորության կազմավորումը</div>
            <div class="time-item"><strong>301 թ.</strong> — Քրիստոնեությունը ընդունվեց որպես պետական կրոն</div>
            <div class="time-item"><strong>1918</strong> — Առաջին Հայաստանի Հանրապետություն</div>
          </div>
        </div>
      </div>

      <div>
        <div class="card" id="places">
          <h2>Տեսարժան վայրեր</h2>
          <div style="color:var(--muted);font-size:13px;margin-top:6px"></div>

          <div style="margin-top:12px" class="tags" aria-hidden="false">
            <div class="tag">Երևան</div>
            <div class="tag">Գեղարդ</div>
            <div class="tag">Խոր Վիրապ</div>
            <div class="tag">Սևան</div>
          </div>





<div class="attractions" style="margin-top:12px" id="cards">
            <div class="place">
              <h3>Մատենադարան / Երևան</h3>
              <p>Մեծագույն գրախոսական և ձեռագրերի պահոց Երևանում — մշակութային զառիվեր կենտրոն:</p>
            </div>

            <div class="place">
              <h3>Գեղարդ</h3>
              <p>Միջնադարից եկած քարաշեն վանական համալիր՝ հորինվածք և անդամական ճարտարապետությամբ:</p>
            </div>

            <div class="place">
              <h3>Խոր Վիրապ</h3>
              <p>ճարտարապետական հուշարձան, 3-րդ դարի վանք-ամրոց Մեծ Հայքի Այրարատ նահանգի Ոստան Հայոց գավառում:</p>
            </div>

            <div class="place">
              <h3>Սևանա լիճ</h3>
              <p>Մեծ ու գեղեցիկ լիճ՝ հանգստի և էկո-տնտեսության կենտրոն:</p>
            </div>

            <div class="place">
              <h3>Տաճարները (e.g., Եկեղեցիներ)</h3>
              <p>Հազարավոր եկեղեցիներ ու հուշարձաններ ամբողջ երկրով:</p>
            </div>

           <div class="place">
              <h3>Սյունիք / Խոսքի երկրամաս</h3>
              <p>Խորհրդավոր բնապատկերներ, կիրճեր և պատմական վայրեր:</p>
            </div>
          </div>
        </div>



<div class="card" id="map" style="argin-top:12px">
          <h2>Քարտեզ (Երևան կենտրոն)</h2>
          <div class="map" style="margin-top:8px">
            <!-- OpenStreetMap embed centered on Yerevan. Լիցենզիա՝ OSM -->
            <iframe
              src="https://www.openstreetmap.org/export/embed.html?bbox=44.337%2C40.131%2C44.669%2C40.235&layer=mapnik&marker=40.183%2C44.503"
              style="border:0;width:100%;height:100%" loading="lazy" title="Yerevan map"></iframe>
          </div>
          <div style="margin-top:8px;font-size:13px;color:var(--muted)">
            
          </div>
        </div>

        <div class="card" id="contact" style="margin-top:12px">
          <h2>Կապ</h2>
          <p style="color:var(--muted)">Սիրով կօգնեմ ավելացնել ավելի շատ հոդվածներ և լուսանկարներ։</p>
          <div style="margin-top:8px">
            <small style="color:var(--muted)"></small>
            <ul style="margin:8px 0 0 18px;color:var(--muted)">
              

            </ul>
          </div>
        </div>
      </div>
    </div>



<footer>
      © <span id="year"></span> Հայաստան — Փոքր, արագ և պարզ կայք։ Անհրաժեշտ փոփոխություններ ուղարկիր ու կթարմացնեմ։ ❤️
    </footer>
  </div>

  <script>
    // Basic interactivity: smooth scroll, search filter, year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth nav
    document.querySelectorAll('aref^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        const href=a.getAttribute('href');
        if(href.length>1){
          e.preventDefault();

         document.querySelector(href).scrollIntoView({behavior:'smooth',block:'start'});
          document.querySelectorAll('nav a').forEach(x=>x.classList.remove('active'));
          a.classList.add('active');
        }
      });
    });

    // Simple search: filters .place elements by query
    const cards = Array.from(document.querySelectorAll('.place'));
    document.getElementById('searchBtn').addEventListener('click', runSearch);
    document.getElementById('query').addEventListener('keydown', e=>{ if(e.key === 'Enter') runSearch(); });

    function runSearch(){
      const q = document.getElementById('query').value.trim().toLowerCase();
      if(!q){
        cards.forEach(c=>c.style.display='block');
        return;
      }
      cards.forEach(card=>{
        const text = card.textContent.toLowerCase();
        card.style.display = text.includes(q) ? 'block' : 'none';
      });
    }

    // Lightweight accessibility: focus outlines
    document.addEventListener('keydown', e=>{
      if(e.key==='Tab') document.body.classList.add('show-focus');
    });
  </script>
</body>
</html>



