Delhi Run Collective — redesign versions
========================================
Open any .html directly in a browser. Each file is fully self-contained:
no build step, no CDN, no external assets.

01-paceboard-dark.html
    Night-run direction. Committed dark theme, hi-vis yellow-green on
    asphalt, condensed uppercase type. Weekly schedule as a timing table
    with colour-coded pace chips.

02-fivefourty-dawn.html
    "5:40 AM" editorial/zine direction. Cool pale-lilac paper, sodium
    amber accent, Didot-class serif display. Full light + dark themes.

03-delhi-wireframe-dark.html
    First 3D attempt. Hand-plotted wireframe Delhi (ring roads, Yamuna,
    radials) on near-black, Yamuna teal + marigold. Run-club-first
    section order; merch last.

04-orbit-white-orange.html
    White + orange, light mode, elegant serif. Extruded 11-district slab
    dead centre, orbiting. District shapes are stylised approximations.

05-real-delhi-comic.html   <-- latest
    Same white/orange system, but the map is REAL geometry:
      - Delhi NCT outline, 349 pts (simplified from 3,363)
      - all 11 district rings, 973 pts total
      - source: geoBoundaries gbOpen IND ADM1 + ADM2 (2021),
        via lgdirectory.gov.in / Pathways Data Pvt. Ltd.
        ODbL 1.0 — attribution is printed under the hero
      - longitude cosine-corrected at Delhi's latitude
      - run pins placed by real lat/lng; the page runs point-in-polygon
        at load to resolve which district each run sits in
    Hero copy is arranged around the revolving map. The "Six a.m. looks
    like this" section is a six-panel comic strip (canvas art, real HTML
    lettering in the balloons and caption boxes).

delhi_geo.js
    The extracted + simplified Delhi geometry on its own, if you want to
    reuse it in the production build. Already inlined into version 05.

Note on content: copy, member quotes, run times, pace groups and the
1,840 figure are plausible placeholders written to match the club's
voice — verify before shipping. Gallery/comic art is procedurally drawn
and should be replaced with real photography.
