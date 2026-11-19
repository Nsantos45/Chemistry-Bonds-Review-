:root{--bg:#fff7e6;--card:#ffffff;--tx:#1f2340;--mu:#666a8c;--ac:#ff5a36;--ac2:#2b59ff;--ok:#12a36b;--no:#e03a4a;--bd:#ece3cc;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#14172b;--card:#1f2340;--tx:#f4f2ff;--mu:#a4a8d0;--ac:#ff7a59;--ac2:#7f9bff;--ok:#32d397;--no:#ff6b78;--bd:#33385f}}
:root[data-theme="dark"]{--bg:#14172b;--card:#1f2340;--tx:#f4f2ff;--mu:#a4a8d0;--ac:#ff7a59;--ac2:#7f9bff;--ok:#32d397;--no:#ff6b78;--bd:#33385f}
*{box-sizing:border-box}
html,body{margin:0}
body{background:var(--bg);color:var(--tx);font:16px/1.5 "Trebuchet MS","Segoe UI",system-ui,sans-serif;min-height:100vh}
#app{max-width:640px;margin:0 auto;padding:18px 16px 40px}
h1{font:900 2rem/1.1 "Arial Black",Impact,sans-serif;margin:8px 0 4px;letter-spacing:-.5px}
h2{margin:0 0 10px;font-size:1.25rem}
.sub{color:var(--mu);margin:0 0 16px}
.tiles{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.tile{background:var(--card);border:2px solid var(--bd);border-radius:14px;padding:12px;text-align:left;color:var(--tx);cursor:pointer;font:inherit}
.tile:hover,.tile:focus-visible{border-color:var(--ac2);outline:none}
.tile b{display:block;font-size:1.05rem}.tile small{color:var(--mu)}
.tile.wide{grid-column:1/-1;background:var(--ac);color:#fff;border-color:var(--ac)}
.tile.wide small{color:#fff;opacity:.9}
.hud{display:flex;justify-content:space-between;align-items:center;gap:8px;font-weight:700;margin-bottom:8px;flex-wrap:wrap}
.pill{background:var(--card);border:2px solid var(--bd);border-radius:99px;padding:2px 12px}
.bar{height:10px;background:var(--bd);border-radius:9px;overflow:hidden;margin-bottom:16px}
.bar i{display:block;height:100%;background:var(--ac2);transition:width .3s}
.q{background:var(--card);border:2px solid var(--bd);border-radius:16px;padding:16px;font-size:1.15rem;font-weight:700;margin-bottom:12px}
.opt{display:block;width:100%;text-align:left;background:var(--card);color:var(--tx);border:2px solid var(--bd);border-radius:12px;padding:12px 14px;margin:8px 0;font:inherit;cursor:pointer}
.opt:hover:not(:disabled),.opt:focus-visible{border-color:var(--ac2);outline:none}
.opt.ok{border-color:var(--ok);background:color-mix(in srgb,var(--ok) 18%,var(--card))}
.opt.no{border-color:var(--no);background:color-mix(in srgb,var(--no) 18%,var(--card))}
.opt.gone{opacity:.25;pointer-events:none}
.btn{background:var(--ac2);color:#fff;border:0;border-radius:12px;padding:12px 18px;font:700 1rem inherit;font-family:inherit;cursor:pointer}
.btn.alt{background:var(--card);color:var(--tx);border:2px solid var(--bd)}
.fb{border-radius:14px;padding:12px 14px;margin:12px 0;background:var(--card);border:2px solid var(--bd)}
.fb.ok{border-color:var(--ok)}.fb.no{border-color:var(--no)}
.row{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
.big{font:900 3rem/1 "Arial Black",Impact,sans-serif;color:var(--ac)}
.tb{display:flex;align-items:center;gap:8px;margin:6px 0;font-size:.92rem}
.tb span:first-child{width:150px;flex:none}.tb .bar{flex:1;margin:0;height:12px}
.tb .bar i.lo{background:var(--no)}.tb .bar i.hi{background:var(--ok)}
.tip{background:var(--card);border-left:6px solid var(--ac);border-radius:10px;padding:10px 12px;margin:8px 0}
.miss{border-top:1px dashed var(--bd);padding:8px 0;font-size:.92rem}
@media(prefers-reduced-motion:no-preference){.pop{animation:p .35s}@keyframes p{50%{transform:scale(1.04)}}}
