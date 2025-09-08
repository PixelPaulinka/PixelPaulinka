
<svg xmlns="http://www.w3.org/2000/svg" width="880" height="180" viewBox="0 0 880 180" role="img" aria-label="Typing lines">
  <style>
    text { font-family: "Fira Code", "Courier New", monospace; font-weight: 600; fill:#0f1724; font-size:28px; }
    .big { font-size:30px; }
    .caret { fill:#0f1724; }
    .line { dominant-baseline:middle; }
  </style>

  <!-- defs: masks for "typing" -->
  <defs>
    <mask id="m1"><rect x="0" y="0" width="0" height="180" fill="#fff">
      <animate attributeName="width" from="0" to="880" dur="1.6s" begin="0s" fill="freeze"/>
    </rect></mask>

    <mask id="m2"><rect x="0" y="0" width="0" height="180" fill="#fff">
      <animate attributeName="width" from="0" to="880" dur="1.6s" begin="1.8s" fill="freeze"/>
    </rect></mask>

    <mask id="m3"><rect x="0" y="0" width="0" height="180" fill="#fff">
      <animate attributeName="width" from="0" to="880" dur="1.6s" begin="3.6s" fill="freeze"/>
    </rect></mask>
  </defs>

  <!-- lines (each uses its mask) -->
  <g mask="url(#m1)"><text x="24" y="38" class="line big">Technik mit Seele.</text></g>
  <g mask="url(#m2)"><text x="24" y="86" class="line">Ordnung mit Zukunft.</text></g>
  <g mask="url(#m3)"><text x="24" y="134" class="line">Ich gehe meinen Weg.</text></g>

  <!-- caret: появился после каждой строки (вручную синхронизирован) -->
  <rect id="c1" x="260" y="20" width="6" height="28" class="caret" opacity="0">
    <animate attributeName="opacity" values="0;1;0;1" dur="0.9s" begin="1.4s" repeatCount="indefinite"/>
  </rect>
  <rect id="c2" x="260" y="68" width="6" height="28" class="caret" opacity="0">
    <animate attributeName="opacity" values="0;1;0;1" dur="0.9s" begin="3.2s" repeatCount="indefinite"/>
  </rect>
  <rect id="c3" x="260" y="116" width="6" height="28" class="caret" opacity="0">
    <animate attributeName="opacity" values="0;1;0;1" dur="0.9s" begin="4.9s" repeatCount="indefinite"/>
  </rect>
</svg>



