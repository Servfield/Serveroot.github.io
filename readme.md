
<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>我的导航</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,'Helvetica Neue',sans-serif;
         margin:0;background:#f7f7f7;color:#222}
    header{padding:2rem;background:#111;color:#fff}
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));
          gap:1rem;padding:1rem}
    .card{background:#fff;border-radius:8px;padding:1rem;box-shadow:0 2px 8px rgba(0,0,0,.06)}
    .card a{color:#0b5fff;text-decoration:none;font-weight:600}
    .desc{font-size:.9rem;color:#666;margin-top:.25rem}
  </style>
</head>
<body>
  <header><h1>我的常用导航</h1><p>OutlookMail</p></header>
  <main class="grid">
    <div class="card">
      https://github.comGitHub</a>
      <div class="desc">代码托管与协作平台</div>
    </div>
    <div class="card">
      https://gohugo.ioHugo</a>
      <div class="desc">超快的静态网站生成器</div>
    </div>
    <!-- 继续添加你的链接卡片 -->
  </main>
</body>
</html>
