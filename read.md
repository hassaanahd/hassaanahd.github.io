---
layout: page
title: Reading List
permalink: /read/
---

<link href="https://fonts.googleapis.com/css2?family=Source+Serif+4:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">

<style>
.rl{--sans:-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;--serif:"Source Serif 4",Georgia,serif;font-family:var(--sans)}
.rl h2{font-family:var(--sans);font-size:24px;font-weight:400;letter-spacing:-.01em;border-bottom:1px solid #444;padding-bottom:6px;margin:44px 0 18px;display:flex;justify-content:space-between;align-items:baseline}
.rl h2 small{font-size:13px;color:#9a9a9a}
.rl .now{display:grid;grid-template-columns:150px 1fr;gap:26px;align-items:center;border:1px solid #333;border-radius:12px;padding:22px}
.rl .status{display:inline-flex;align-items:center;gap:7px;font-size:12px;color:#EF9F27;border:1px solid #5a3a10;border-radius:20px;padding:2px 10px}
.rl .status:before{content:"";width:7px;height:7px;border-radius:50%;background:#EF9F27;animation:rlp 1.8s ease-in-out infinite}
@keyframes rlp{50%{opacity:.25}}
.rl .now h3{font-family:var(--serif);font-size:28px;font-weight:600;color:#fff;margin:10px 0 0;line-height:1.2}
.rl .now .by{font-family:var(--serif);font-style:italic;color:#9a9a9a;font-size:17px}
.rl .prog{display:flex;gap:4px;margin:18px 0 6px}
.rl .prog span{flex:1;height:6px;border-radius:3px;background:#333}
.rl .prog .d{background:#EF9F27}
.rl .prog .c{background:linear-gradient(90deg,#EF9F27 50%,#333 50%)}
.rl .sm{font-size:13px;color:#9a9a9a}
.rl .shelf{display:grid;grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:22px 18px}
.rl .book{display:flex;flex-direction:column;gap:8px}
.rl .cover{position:relative;aspect-ratio:2/3;border-radius:3px 8px 8px 3px;padding:16px 12px 14px 20px;display:flex;flex-direction:column;justify-content:space-between;overflow:hidden;transition:transform .2s ease}
.rl .cover:hover{transform:translateY(-4px) rotate(-1deg)}
.rl .cover:before{content:"";position:absolute;left:0;top:0;bottom:0;width:8px;background:rgba(0,0,0,.35)}
.rl .cover:after{content:"";position:absolute;left:8px;top:0;bottom:0;width:1px;background:rgba(255,255,255,.15)}
.rl .cover .ti{font-family:var(--serif);font-size:17px;font-weight:600;line-height:1.2}
.rl .cover .au{font-size:10px;letter-spacing:.12em;text-transform:uppercase;opacity:.8}
.rl .cover .no{position:absolute;right:10px;top:10px;font-family:var(--serif);font-size:13px;opacity:.6}
.rl .cap{font-size:13px;color:#9a9a9a;line-height:1.35}
.rl .cap b{display:block;color:#e8e8e8;font-weight:500;font-size:14px}
.rl .dune{background:#3a2a10;color:#FAC775}
.rl .dost{background:#1b2b45;color:#B5D4F4}
.rl .homer{background:#0f3a2e;color:#9FE1CB}
.rl .plath{background:#4b1528;color:#F4C0D1}
.rl .kafka{background:#2c2c2a;color:#D3D1C7}
.rl .cover img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;z-index:1;opacity:0;transition:opacity .4s ease}
.rl .cover.has-img img{opacity:1}
.rl .cover:before,.rl .cover:after{z-index:2}
.rl .credit{margin-top:28px;font-size:12px;color:#777}
.rl .credit a{color:#9a9a9a}
@media (max-width:560px){.rl .now{grid-template-columns:110px 1fr;gap:18px;padding:16px}.rl .now h3{font-size:22px}.rl .shelf{grid-template-columns:repeat(2,1fr)}}
</style>

<div class="rl">

<div class="now">
<div class="cover dune" data-q="heretics of dune herbert" data-cover="https://covers.openlibrary.org/b/id/14797595-M.jpg"><span class="no">V</span><span class="ti">Heretics of Dune</span><span class="au">Frank Herbert</span></div>
<div>
<span class="status">Currently reading</span>
<h3>Heretics of Dune</h3>
<div class="by">Frank Herbert</div>
<div class="prog"><span class="d"></span><span class="d"></span><span class="d"></span><span class="d"></span><span class="c"></span><span></span></div>
<div class="sm">Book 5 of 6 in the Dune Chronicles</div>
</div>
</div>

<h2>Finished <small>10 books</small></h2>

<div class="shelf">

<div class="book"><div class="cover dune" data-q="dune frank herbert" data-cover="https://covers.openlibrary.org/b/id/12819203-M.jpg"><span class="no">I</span><span class="ti">Dune</span><span class="au">Frank Herbert</span></div><div class="cap"><b>Dune</b>Frank Herbert</div></div>

<div class="book"><div class="cover dune" data-q="dune messiah herbert" data-cover="https://covers.openlibrary.org/b/id/14816227-M.jpg"><span class="no">II</span><span class="ti">Dune Messiah</span><span class="au">Frank Herbert</span></div><div class="cap"><b>Dune Messiah</b>Frank Herbert</div></div>

<div class="book"><div class="cover dune" data-q="children of dune herbert" data-cover="https://covers.openlibrary.org/b/id/14613340-M.jpg"><span class="no">III</span><span class="ti">Children of Dune</span><span class="au">Frank Herbert</span></div><div class="cap"><b>Children of Dune</b>Frank Herbert</div></div>

<div class="book"><div class="cover dune" data-q="god emperor of dune herbert" data-cover="https://covers.openlibrary.org/b/id/14787645-M.jpg"><span class="no">IV</span><span class="ti">God Emperor of Dune</span><span class="au">Frank Herbert</span></div><div class="cap"><b>God Emperor of Dune</b>Frank Herbert</div></div>

<div class="book"><div class="cover dost" data-q="white nights dostoevsky" data-cover="https://covers.openlibrary.org/b/id/14598226-M.jpg"><span class="ti">White Nights</span><span class="au">Fyodor Dostoevsky</span></div><div class="cap"><b>White Nights</b>Fyodor Dostoevsky</div></div>

<div class="book"><div class="cover dost" data-q="the meek one dostoevsky" data-cover="https://covers.openlibrary.org/b/id/15266345-M.jpg"><span class="ti">The Meek One</span><span class="au">Fyodor Dostoevsky</span></div><div class="cap"><b>The Meek One</b>Fyodor Dostoevsky</div></div>

<div class="book"><div class="cover homer" data-q="iliad emily wilson" data-cover="https://covers.openlibrary.org/b/id/14546467-M.jpg"><span class="ti">The Iliad</span><span class="au">Homer</span></div><div class="cap"><b>The Iliad</b>Homer · tr. Emily Wilson</div></div>

<div class="book"><div class="cover homer" data-q="odyssey emily wilson" data-cover="https://covers.openlibrary.org/b/id/8100018-M.jpg"><span class="ti">The Odyssey</span><span class="au">Homer</span></div><div class="cap"><b>The Odyssey</b>Homer · tr. Emily Wilson</div></div>

<div class="book"><div class="cover plath" data-q="the bell jar plath" data-cover="https://covers.openlibrary.org/b/id/15165706-M.jpg"><span class="ti">The Bell Jar</span><span class="au">Sylvia Plath</span></div><div class="cap"><b>The Bell Jar</b>Sylvia Plath</div></div>

<div class="book"><div class="cover kafka" data-q="metamorphosis kafka" data-cover="https://covers.openlibrary.org/b/id/6394194-M.jpg"><span class="ti">The Metamorphosis</span><span class="au">Franz Kafka</span></div><div class="cap"><b>The Metamorphosis</b>Franz Kafka</div></div>

</div>

<p class="credit">Covers from <a href="https://openlibrary.org">Open Library</a>.</p>

</div>

<script>
(function(){
  var KEY='rl-covers-v1',cache={};
  try{cache=JSON.parse(localStorage.getItem(KEY))||{}}catch(e){}
  function save(){try{localStorage.setItem(KEY,JSON.stringify(cache))}catch(e){}}
  function show(el,src){
    var img=new Image();img.alt='';
    img.onload=function(){if(img.naturalWidth>10){el.appendChild(img);requestAnimationFrame(function(){el.classList.add('has-img')})}};
    img.src=src;
  }
  document.querySelectorAll('.rl .cover[data-q]').forEach(function(el){
    var q=el.getAttribute('data-q');
    if(el.getAttribute('data-cover')){show(el,el.getAttribute('data-cover'));return}
    if(cache[q]){show(el,cache[q]);return}
    fetch('https://openlibrary.org/search.json?q='+encodeURIComponent(q)+'&fields=cover_i&limit=10')
      .then(function(r){return r.json()})
      .then(function(j){
        var d=(j.docs||[]).filter(function(x){return x.cover_i})[0];
        if(!d)return;
        cache[q]='https://covers.openlibrary.org/b/id/'+d.cover_i+'-M.jpg';save();show(el,cache[q]);
      }).catch(function(){});
  });
})();
</script>
