<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sophie & Joshua – Hochzeitslocations</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
:root{
  --bg:#f4f3ef;
  --card:#ffffff;
  --sage:#8fa79b;
  --rose:#d7b4a0;
  --gold:#c6a86d;
  --text:#1f2933;
  --muted:#6b7280;
  --radius:28px;
  --shadow:0 35px 90px rgba(0,0,0,.10);
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family:'Inter',sans-serif;
  background:
    radial-gradient(1000px 400px at 10% -10%, #e7ded7, transparent),
    radial-gradient(1000px 400px at 90% 10%, #dde7e1, transparent),
    var(--bg);
  color:var(--text);
}

/* HERO */
.hero{
  max-width:1100px;
  margin:90px auto 60px;
  padding:0 20px;
  text-align:center;
}

.hero img{
  width:100%;
  max-width:520px;
  border-radius:36px;
  box-shadow:var(--shadow);
}

.hero h1{
  font-family:'Playfair Display',serif;
  font-size:clamp(42px,6vw,66px);
  margin:30px 0 12px;
}

.hero p{
  color:var(--muted);
  font-size:18px;
}

/* LAYOUT */
main{
  max-width:1150px;
  margin:auto;
  padding:0 20px 140px;
}

.section{
  margin-bottom:90px;
}

.section-title{
  font-family:'Playfair Display',serif;
  font-size:36px;
  margin-bottom:30px;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:28px;
}

.card{
  background:var(--card);
  border-radius:var(--radius);
  padding:30px;
  box-shadow:var(--shadow);
}

.label{
  font-size:12px;
  letter-spacing:.25em;
  color:var(--sage);
  text-transform:uppercase;
}

.value{
  font-size:19px;
  font-weight:600;
  margin-top:8px;
}

/* ACCORDION */
.accordion{
  background:#fafafa;
  border-radius:26px;
  margin-bottom:24px;
  overflow:hidden;
}

.accordion-header{
  padding:24px 28px;
  cursor:pointer;
  display:flex;
  justify-content:space-between;
  align-items:center;
  font-size:20px;
  font-weight:600;
}

.icon{
  font-size:28px;
  transition:transform .35s ease;
}

.accordion.active .icon{
  transform:rotate(45deg);
}

.accordion-content{
  max-height:0;
  overflow:hidden;
  padding:0 28px;
  transition:max-height .6s ease, padding .4s ease;
}

.accordion.active .accordion-content{
  max-height:1600px;
  padding:0 28px 32px;
}

h3{
  margin-top:26px;
  font-size:21px;
}

ul{
  margin:12px 0 0 20px;
  color:var(--muted);
  line-height:1.75;
}

.pro{color:#2f855a;font-weight:500}
.contra{color:#b83232;font-weight:500}

/* TABLE */
table{
  width:100%;
  border-collapse:collapse;
}

th{
  text-align:left;
  font-size:12px;
  letter-spacing:.25em;
  color:var(--sage);
  padding-bottom:14px;
}

td{
  padding:18px 6px;
  border-bottom:1px solid #eee;
}

.price{
  font-weight:700;
}

/* FOOTER */
footer{
  text-align:center;
  color:var(--muted);
  font-size:13px;
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <img src="https://drive.google.com/thumbnail?id=1k6MO-4vjc0JcZpQ1yoY-D4UIYYNwvyKf&sz=w1200" alt="Sophie und Joshua">
  <h1>Sophie & Joshua</h1>
  <p>Unsere Hochzeitslocations – eine Übersicht für Familie & Freunde</p>
</section>

<main>

<!-- ECKDATEN -->
<section class="section">
  <h2 class="section-title">Allgemeine Eckdaten</h2>
  <div class="cards">
    <div class="card">
      <div class="label">Brautpaar</div>
      <div class="value">Sophie & Joshua</div>
    </div>
    <div class="card">
      <div class="label">Gästeanzahl</div>
      <div class="value">ca. 90–100 Personen</div>
    </div>
    <div class="card">
      <div class="label">Feierdauer</div>
      <div class="value">9 Stunden + Verlängerung möglich</div>
    </div>
  </div>
</section>

<!-- LOCATIONS -->
<section class="section">
  <h2 class="section-title">Unsere Locations</h2>

  <!-- EICHENSTOLZ -->
  <div class="accordion">
    <div class="accordion-header">
      🌿 Eichenstolz
      <span class="icon">＋</span>
    </div>
    <div class="accordion-content">
      <h3>Eckdaten</h3>
      <ul>
        <li>50–200 Personen</li>
        <li>Moderner Industriestil in historischen Gemäuern</li>
        <li>Großzügiger Außenbereich & Speicher für Party</li>
        <li>Ungestörtes Feiern bis in die frühen Morgenstunden</li>
      </ul>

      <h3>Besonderheiten</h3>
      <ul>
        <li>Sommerspecial: Empfang & Dinner unter der Lindenallee</li>
        <li>Flexible Schlechtwetter-Alternative indoor</li>
        <li>Viele Hotels in direkter Umgebung</li>
      </ul>

      <h3>Pro & Contra</h3>
      <ul>
        <li class="pro">✔ Samstag ohne Übernachtungspflicht</li>
        <li class="pro">✔ Einzigartiges Outdoor-Dinner</li>
        <li class="pro">✔ Sehr transparente Pauschalpreise</li>
        <li class="contra">✖ Keine Übernachtung direkt an der Location</li>
        <li class="contra">✖ Outdoor wetterabhängig</li>
      </ul>
    </div>
  </div>

  <!-- LAUTENBACH -->
  <div class="accordion">
    <div class="accordion-header">
      🏰 Schlossgut Lautenbach
      <span class="icon">＋</span>
    </div>
    <div class="accordion-content">
      <h3>Eckdaten</h3>
      <ul>
        <li>Orangerie im Schlosspark</li>
        <li>Bis 100 Personen am Samstag</li>
        <li>After-Hour-Club für Party</li>
        <li>Feiern & Übernachten an einem Ort</li>
      </ul>

      <h3>Besonderheiten</h3>
      <ul>
        <li>Übernachtung im Schloss (Fr/Sa verpflichtend)</li>
        <li>Getting Ready im Schloss möglich</li>
        <li>Sehr romantisches, elegantes Gesamtsetting</li>
      </ul>

      <h3>Pro & Contra</h3>
      <ul>
        <li class="pro">✔ Komplettes Hochzeitswochenende möglich</li>
        <li class="pro">✔ Sehr stilvolle & romantische Atmosphäre</li>
        <li class="pro">✔ Gäste direkt vor Ort untergebracht</li>
        <li class="contra">✖ Deutlich höhere Kosten am Samstag</li>
        <li class="contra">✖ Übernachtung verpflichtend</li>
      </ul>
    </div>
  </div>
</section>

<!-- KOSTEN -->
<section class="section">
  <h2 class="section-title">Kostenvergleich (inkl. 2 Stunden Verlängerung)</h2>
  <div class="card">
    <table>
      <tr>
        <th>Location</th><th>Tag</th><th>Personen</th>
        <th>Buffet</th><th>Buffet +2h</th>
        <th>Menü</th><th>Menü +2h</th>
      </tr>
      <tr>
        <td>Eichenstolz</td><td>Samstag</td><td>bis 100</td>
        <td class="price">23.000 €</td>
        <td class="price">24.700 €</td>
        <td class="price">24.500 €</td>
        <td class="price">26.200 €</td>
      </tr>
      <tr>
        <td>Lautenbach</td><td>Freitag</td><td>90</td>
        <td class="price">22.900 €</td>
        <td class="price">24.600 €</td>
        <td class="price">24.250 €</td>
        <td class="price">25.950 €</td>
      </tr>
      <tr>
        <td>Lautenbach</td><td>Samstag</td><td>bis 100</td>
        <td class="price">26.250 €</td>
        <td class="price">27.950 €</td>
        <td class="price">27.750 €</td>
        <td class="price">29.450 €</td>
      </tr>
    </table>
  </div>
</section>

<footer>
  Sophie & Joshua · Hochzeitsplanung · Übersicht für Familie 🤍
</footer>

</main>

<script>
document.querySelectorAll('.accordion-header').forEach(header=>{
  header.addEventListener('click',()=>{
    header.parentElement.classList.toggle('active');
  });
});
</script>

</body>
</html>
