<!--
  업로드 방법: github.com/new 에서 저장소 이름을 hoooni10099 (아이디와 동일) 로, Public + "Add a README file" 체크 → 이 내용으로 교체
  [대괄호] 부분만 채우거나 지우면 됩니다.
-->

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:0f2a1f&height=110&text=%20&section=header">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=rect&color=0:ffffff,100:e8f7ef&height=110&text=%20&section=header">
  <img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:0f2a1f&height=110&text=%20&section=header">
</picture>

<h1 align="left">
  이상훈 <sub><sup>/ Embedded Full-Stack Developer</sup></sub>
</h1>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2600&pause=900&color=2BD67B&vCenter=true&width=600&height=28&lines=%3E+%EC%84%BC%EC%84%9C%EC%97%90%EC%84%9C+%EB%8C%80%EC%8B%9C%EB%B3%B4%EB%93%9C%EA%B9%8C%EC%A7%80%2C+%ED%95%9C+%EC%A4%84%EB%A1%9C+%EC%9E%87%EC%8A%B5%EB%8B%88%EB%8B%A4.;%3E+firmware+%E2%86%92+serial+%E2%86%92+DB+%E2%86%92+analysis+%E2%86%92+dashboard;%3E+I'm+gonna+be+the+best+full-stack+dev+(embedded)." alt="typing" /></a>

<br/>

```c
/* whoami.h */
typedef struct {
    const char *name;       // "Lee Sang Hun"
    const char *role;       // "Embedded Full-Stack Developer"
    const char *layers[4];  // { "Firmware", "Embedded", "Data", "Analytics" }
    const char *focus;      // "Predictive Maintenance · Smart Factory (MES)"
    const char *certs[2];   // { "SQLD", "ADsP" }
    const char *contact;    // "lshun3604@gmail.com"
} engineer_t;

volatile uint8_t curiosity = 0xFF;   // always max
```

<br/>

## ▣ The Stack I Live In

> 전기 신호 하나가 판단 가능한 데이터가 되기까지, 전 구간을 직접 만듭니다.

```text
  ┌───────────────────────────────────────────────────────┐
  │  INSIGHT   Streamlit · Plotly · pandas · Z-score       │  ← 보여주고, 판단하고
  ├───────────────────────────────────────────────────────┤
  │  DATA      PostgreSQL · SQLite                         │  ← 쌓고, 질의하고
  ├───────────────────────────────────────────────────────┤
  │  APP       Python · Java                               │  ← 수집하고, 처리하고
  ├───────────────────────────────────────────────────────┤
  │  EMBEDDED  Raspberry Pi · Linux (Ubuntu/WSL)           │  ← 엣지에서 돌리고
  ├───────────────────────────────────────────────────────┤
  │  FIRMWARE  C · C++ · STM32 · Arduino · UART/Serial     │  ← 하드웨어를 깨우고
  └───────────────────────────────────────────────────────┘
                  ⚡ sensor / MCU / silicon
```

<br/>

## ▤ Toolbox

<table>
  <tr>
    <td width="110"><sub><b>Language</b></sub></td>
    <td><img src="https://skillicons.dev/icons?i=c,cpp,python,java&theme=dark" height="36"/></td>
  </tr>
  <tr>
    <td><sub><b>Hardware</b></sub></td>
    <td>
      <img src="https://skillicons.dev/icons?i=arduino,raspberrypi&theme=dark" height="36"/>
      <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" height="22"/>
    </td>
  </tr>
  <tr>
    <td><sub><b>Database</b></sub></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,sqlite&theme=dark" height="36"/></td>
  </tr>
  <tr>
    <td><sub><b>Data · Viz</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" height="22"/>
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" height="22"/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" height="22"/>
      <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" height="22"/>
    </td>
  </tr>
  <tr>
    <td><sub><b>Env</b></sub></td>
    <td><img src="https://skillicons.dev/icons?i=linux,ubuntu,git&theme=dark" height="36"/></td>
  </tr>
</table>

<br/>

## ▩ Certified Modules

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="https://img.shields.io/badge/SQLD-SQL%20개발자-336791?style=flat-square&logo=postgresql&logoColor=white" height="22"/>
      <br/><sub>한국데이터산업진흥원 · 데이터 모델링 & SQL 활용</sub>
    </td>
    <td width="50%" valign="top">
      <img src="https://img.shields.io/badge/ADsP-데이터분석%20준전문가-2BD67B?style=flat-square&logo=databricks&logoColor=white" height="22"/>
      <br/><sub>한국데이터산업진흥원 · 데이터 이해 · 분석 기획 · 통계 분석</sub>
    </td>
  </tr>
</table>

<br/>

## ▥ Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📡 <a href="https://github.com/hoooni10099/PdM_monitoring_pipeline">PdM Monitoring Pipeline</a></h3>
      <sub>Arduino 센서 노드에서 대시보드까지 — 설비 고장을 <b>일어나기 전에</b> 잡는 예지보전 시스템</sub>
      <br/><br/>
<sub>

```
Arduino ─serial─▶ Collector ─▶ PostgreSQL
                                  │
          Dashboard ◀── Analysis ◀┘
```

</sub>
      <sub>▸ 충격·온습도·거리·화염 4종 센서 → 115200bps 시리얼 프로토콜 설계<br/>
      ▸ 규칙 기반 + Z-score(2.5σ) 이상 탐지, 8개 시나리오 검증<br/>
      ▸ SQLite → PostgreSQL 이관, MVCC로 수집·분석·시각화 3개 프로세스 독립 운영</sub>
      <br/><br/>
      <code>Arduino</code> <code>Python</code> <code>PostgreSQL</code> <code>Streamlit</code>
    </td>
    <td width="50%" valign="top">
      <h3>🏭 <a href="https://github.com/hoooni10099/Dx-Ax">Dx-Ax</a></h3>
      <sub>C · C++ · Java · Python · SQLite를 넘나들며 쌓은 <b>737 commits</b>의 학습·프로젝트 아카이브</sub>
      <br/><br/>
      <sub>▸ <b>Mini MES Project</b> — [제조 실행 시스템에서 구현한 기능 한 줄]<br/>
      ▸ 언어별 실습 코드와 SQLite 데이터 설계<br/>
      ▸ WSL(Ubuntu) 기반 개발 환경 구성</sub>
      <br/><br/>
      <code>C/C++</code> <code>Java</code> <code>Python</code> <code>SQLite</code>
    </td>
  </tr>
</table>

<br/>

## ▦ Boot Log

```console
[    0.000000] Booting Lee Sang Hun ...
[    0.104213] lang: C / C++ / Java / Python loaded ............................. [  OK  ]
[    1.337000] db: SQLite schema design, MES data modeling ....................... [  OK  ]
[    2.048000] fw: Arduino 4-sensor node, serial protocol, debounce .............. [  OK  ]
[    2.718281] cert: SQLD, ADsP (K-data) verified ................................ [ PASS ]
[    3.141592] data: PdM pipeline, SQLite → PostgreSQL migration ................. [  OK  ]
[    4.096000] now: [STM32 / Raspberry Pi 확장 · 진행 중인 일] ...................... [ BUSY ]
[    ∞       ] waiting for next interrupt_
```

<br/>

## ▧ Signals

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://github-readme-stats.vercel.app/api?username=hoooni10099&show_icons=true&hide_border=true&bg_color=00000000&title_color=2BD67B&icon_color=2BD67B&text_color=c9d1d9&hide_title=true&rank_icon=percentile">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=hoooni10099&show_icons=true&hide_border=true&bg_color=00000000&title_color=159a55&icon_color=159a55&text_color=24292f&hide_title=true&rank_icon=percentile" alt="stats"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=hoooni10099&layout=donut-vertical&hide_border=true&bg_color=00000000&text_color=c9d1d9&hide_title=true&langs_count=5">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hoooni10099&layout=donut-vertical&hide_border=true&bg_color=00000000&text_color=24292f&hide_title=true&langs_count=5" alt="langs"/>
</picture>

<br/>

## ▨ Interrupt Me

<a href="mailto:lshun3604@gmail.com"><img src="https://img.shields.io/badge/Email-lshun3604%40gmail.com-2BD67B?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/hoooni10099"><img src="https://img.shields.io/github/followers/hoooni10099?style=flat-square&logo=github&label=Followers&color=20232a"/></a>
<!-- 블로그/LinkedIn 있으면 추가:
<a href="URL"><img src="https://img.shields.io/badge/Blog-velog-20232a?style=flat-square&logo=velog&logoColor=white"/></a>
-->

<br/><br/>

<p align="right">
  <sub><code>while (1) { learn(); build(); __WFI(); }</code></sub>
</p>
