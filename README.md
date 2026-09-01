# jit.ai — flight recorder site

Static site for team jit.ai's TikTok TechJam 2026 Track 2 entry: an autonomous ML research agent on KuaiRand-Pure.
Replays the designated run (`run_bigclock_07`, 0.6016 → 0.605575) from its journal, shows the 42-card method library and the provenance table.

Code, journals and cards: https://github.com/yxshrk/jitai_ml_agent

Presenter view used in the video: `/present.html` (arrow keys step through the scenes).

No build step. Serve locally with `python3 -m http.server 8642` and open `index.html`.
Data files (`rundata.js`, `methods.js`, `weights.js`) are generated in the main repo by `tools/build_site.py`, `tools/build_methods_js.py`, `tools/instrument_weights.py`.
