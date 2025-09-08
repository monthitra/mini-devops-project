# mini-devops-project
มนต์ธิตรา ชุมภูสืบ 026
<!doctype html>
<html lang="th">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Simple Calculator</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <main class="page">
    <section class="calc-wrap">
      <div class="screen" id="screen">
        <div class="screen-value" id="screenValue">0</div>
        <div class="screen-mini" id="screenMini"></div>
      </div>

      <div class="buttons">
        <button class="btn btn-ac" data-action="all-clear">AC</button>
        <button class="btn" data-action="negate">±</button>
        <button class="btn" data-action="percent">%</button>
        <button class="btn btn-op" data-action="divide">÷</button>

        <button class="btn" data-number="7">7</button>
        <button class="btn" data-number="8">8</button>
        <button class="btn" data-number="9">9</button>
        <button class="btn btn-op" data-action="multiply">×</button>

        <button class="btn" data-number="4">4</button>
        <button class="btn" data-number="5">5</button>
        <button class="btn" data-number="6">6</button>
        <button class="btn btn-op" data-action="subtract">−</button>

        <button class="btn" data-number="1">1</button>
        <button class="btn" data-number="2">2</button>
        <button class="btn" data-number="3">3</button>
        <button class="btn btn-op" data-action="add">+</button>

        <button class="btn btn-zero" data-number="0">0</button>
        <button class="btn" data-action="decimal">.</button>
        <button class="btn btn-equal" data-action="equals">=</button>
      </div>
    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>
