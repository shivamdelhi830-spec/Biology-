# Biology-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NEET Crack AI Pro | By Shivam</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #070b14;
      --card-bg: #0f172a;
      --card-border: #1e293b;
      --primary: #38bdf8;
      --primary-glow: rgba(56, 189, 248, 0.25);
      --accent: #818cf8;
      --success: #22c55e;
      --danger: #ef4444;
      --warning: #f59e0b;
      --text: #f8fafc;
      --text-muted: #94a3b8;
      --radius-sm: 8px;
      --radius-md: 12px;
      --radius-lg: 16px;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Plus Jakarta Sans', sans-serif;
      -webkit-tap-highlight-color: transparent;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 16px;
    }

    .wrapper {
      width: 100%;
      max-width: 720px;
      display: flex;
      flex-direction: column;
      gap: 16px;
      margin-bottom: 24px;
    }

    .header-card {
      background: linear-gradient(180deg, #131d36 0%, var(--card-bg) 100%);
      border: 1px solid var(--card-border);
      border-radius: var(--radius-lg);
      padding: 24px 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
    }

    .header-card::before {
      content: "";
      position: absolute;
      top: -50px;
      left: 50%;
      transform: translateX(-50%);
      width: 200px;
      height: 100px;
      background: var(--primary-glow);
      filter: blur(50px);
      pointer-events: none;
    }

    .brand-title {
      font-size: 26px;
      font-weight: 800;
      letter-spacing: -0.5px;
      background: linear-gradient(135deg, #38bdf8 0%, #c084fc 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 4px;
    }

    .brand-sub {
      font-size: 13px;
      color: var(--text-muted);
      font-weight: 500;
    }

    .owner-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      margin-top: 10px;
      padding: 4px 14px;
      background: rgba(56, 189, 248, 0.08);
      border: 1px solid rgba(56, 189, 248, 0.25);
      border-radius: 99px;
      font-size: 12px;
      font-weight: 600;
      color: var(--primary);
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
    }

    .stat-box {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      border-radius: var(--radius-md);
      padding: 12px 8px;
      text-align: center;
    }

    .stat-label {
      font-size: 11px;
      color: var(--text-muted);
      font-weight: 600;
      text-transform: uppercase;
      margin-bottom: 4px;
    }

    .stat-val {
      font-size: 18px;
      font-weight: 800;
      font-family: 'JetBrains Mono', monospace;
    }

    .stat-score { color: var(--primary); }
    .stat-correct { color: var(--success); }
    .stat-wrong { color: var(--danger); }
    .stat-acc { color: var(--warning); }

    .control-card {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      border-radius: var(--radius-lg);
      padding: 20px;
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .input-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .form-group {
      display: flex;
      flex-direction: column;
      gap: 6px;
    }

    label {
      font-size: 12px;
      font-weight: 600;
      color: var(--text-muted);
    }

    select, input {
      width: 100%;
      background: #070d18;
      border: 1px solid var(--card-border);
      color: var(--text);
      padding: 12px 14px;
      border-radius: var(--radius-sm);
      font-size: 14px;
      outline: none;
      transition: all 0.2s ease;
    }

    select:focus, input:focus {
      border-color: var(--primary);
      box-shadow: 0 0 0 2px var(--primary-glow);
    }

    .btn {
      width: 100%;
      padding: 14px;
      border-radius: var(--radius-sm);
      border: none;
      font-size: 15px;
      font-weight: 700;
      cursor: pointer;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 8px;
      transition: transform 0.1s ease, filter 0.2s ease;
    }

    .btn:active {
      transform: scale(0.99);
    }

    .btn-main {
      background: linear-gradient(135deg, #0284c7 0%, #38bdf8 100%);
      color: #041320;
    }

    .btn-main:hover {
      filter: brightness(1.1);
    }

    .btn:disabled {
      opacity: 0.6;
      cursor: not-allowed;
      transform: none;
    }

    .quiz-card {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      border-radius: var(--radius-lg);
      padding: 20px;
      display: none;
      flex-direction: column;
      gap: 16px;
      animation: slideUp 0.3s ease-out forwards;
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .quiz-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 12px;
      border-bottom: 1px solid var(--card-border);
    }

    .badge-tag {
      font-size: 11px;
      padding: 4px 8px;
      border-radius: 4px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .tag-ai {
      background: rgba(168, 85, 247, 0.15);
      color: #c084fc;
      border: 1px solid rgba(168, 85, 247, 0.3);
    }

    .tag-offline {
      background: rgba(56, 189, 248, 0.15);
      color: #38bdf8;
      border: 1px solid rgba(56, 189, 248, 0.3);
    }

    .timer {
      font-family: 'JetBrains Mono', monospace;
      font-size: 13px;
      font-weight: 700;
      background: rgba(245, 158, 11, 0.1);
      color: var(--warning);
      padding: 4px 10px;
      border-radius: 99px;
      border: 1px solid rgba(245, 158, 11, 0.3);
    }

    .question-box {
      font-size: 16px;
      font-weight: 600;
      line-height: 1.5;
    }

    .options-list {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .opt-btn {
      width: 100%;
      text-align: left;
      background: #090e1a;
      border: 1px solid var(--card-border);
      color: var(--text);
      padding: 14px 16px;
      border-radius: var(--radius-sm);
      font-size: 14px;
      font-weight: 500;
      cursor: pointer;
      transition: all 0.15s ease;
      display: flex;
      align-items: flex-start;
      gap: 10px;
      line-height: 1.4;
    }

    .opt-btn:hover:not(:disabled) {
      border-color: var(--primary);
      background: #10192e;
    }

    .opt-btn.correct {
      background: rgba(34, 197, 94, 0.15) !important;
      border-color: var(--success) !important;
      color: #4ade80 !important;
      font-weight: 700;
    }

    .opt-btn.wrong {
      background: rgba(239, 68, 68, 0.15) !important;
      border-color: var(--danger) !important;
      color: #f87171 !important;
      font-weight: 700;
    }

    .exp-panel {
      display: none;
      background: #070c16;
      border-left: 4px solid var(--accent);
      border-radius: 4px;
      padding: 14px;
      font-size: 13px;
      line-height: 1.5;
      color: #cbd5e1;
    }

    footer {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      border-radius: var(--radius-lg);
      padding: 20px;
      text-align: center;
      display: flex;
      flex-direction: column;
      gap: 8px;
      font-size: 13px;
      color: var(--text-muted);
    }

    .footer-title {
      font-weight: 700;
      color: var(--text);
      font-size: 14px;
      margin-bottom: 2px;
    }

    .contact-links {
      display: flex;
      justify-content: center;
      gap: 16px;
      flex-wrap: wrap;
      margin-top: 4px;
    }

    .contact-links a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 600;
      display: inline-flex;
      align-items: center;
      gap: 4px;
    }

    .contact-links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<div class="wrapper">
  <!-- Header -->
  <div class="header-card">
    <div class="brand-title">NEET CRACK AI PRO</div>
    <div class="brand-sub">Class 11 & 12 NCERT Real-time Test Engine</div>
    <div class="owner-badge">Developed by: Shivam</div>
  </div>

  <!-- Live Stats -->
  <div class="stats-grid">
    <div class="stat-box">
      <div class="stat-label">Score</div>
      <div class="stat-val stat-score" id="scoreDisp">0</div>
    </div>
    <div class="stat-box">
      <div class="stat-label">Correct (+4)</div>
      <div class="stat-val stat-correct" id="correctDisp">0</div>
    </div>
    <div class="stat-box">
      <div class="stat-label">Wrong (-1)</div>
      <div class="stat-val stat-wrong" id="wrongDisp">0</div>
    </div>
    <div class="stat-box">
      <div class="stat-label">Accuracy</div>
      <div class="stat-val stat-acc" id="accDisp">0%</div>
    </div>
  </div>

  <!-- Selection Controls -->
  <div class="control-card">
    <div class="input-grid">
      <div class="form-group">
        <label>Class</label>
        <select id="classSel" onchange="renderChapters()">
          <option value="11">Class 11</option>
          <option value="12">Class 12</option>
        </select>
      </div>
      <div class="form-group">
        <label>Subject</label>
        <select id="subjectSel" onchange="renderChapters()">
          <option value="Biology">Biology</option>
          <option value="Physics">Physics</option>
          <option value="Chemistry">Chemistry</option>
        </select>
      </div>
    </div>

    <div class="form-group">
      <label>NCERT Chapter</label>
      <select id="chapterSel"></select>
    </div>

    <div class="form-group">
      <label>Google Gemini API Key (Optional for Unlimited AI Generation)</label>
      <input type="password" id="apiKeyInput" placeholder="Paste free API key (leave blank for Offline Bank)">
    </div>

    <button class="btn btn-main" id="generateBtn" onclick="nextQuestion()">
      Load Question
    </button>
  </div>

  <!-- Quiz Arena -->
  <div class="quiz-card" id="quizArena">
    <div class="quiz-top">
      <span class="badge-tag tag-offline" id="engineBadge">Offline Bank</span>
      <span class="timer" id="timerBox">00:60</span>
    </div>

    <div class="question-box" id="qDisplay"></div>
    <div class="options-list" id="optContainer"></div>
    <div class="exp-panel" id="expDisplay"></div>

    <button class="btn btn-main" id="nextQuestionBtn" style="display: none;" onclick="nextQuestion()">
      Next Question →
    </button>
  </div>

  <!-- Owner Footer -->
  <footer>
    <div class="footer-title">NEET AI Prep Portal</div>
    <div>Designed & Managed by <strong>Shivam</strong></div>
    <div class="contact-links">
      <a href="mailto:shivamdelhi830@gmail.com">✉ shivamdelhi830@gmail.com</a>
      <a href="tel:9263323156">📞 +91 9263323156</a>
    </div>
  </footer>
</div>

<script>
// FULL NCERT SYLLABUS LIST
const syllabusDB = {
  "11": {
    "Biology": [
      "The Living World", "Biological Classification", "Plant Kingdom", "Animal Kingdom",
      "Morphology of Flowering Plants", "Anatomy of Flowering Plants", "Structural Organisation in Animals",
      "Cell: The Unit of Life", "Biomolecules", "Cell Cycle and Cell Division",
      "Photosynthesis in Higher Plants", "Respiration in Plants", "Plant Growth and Development",
      "Breathing and Exchange of Gases", "Body Fluids and Circulation", "Excretory Products and Elimination",
      "Locomotion and Movement", "Neural Control and Coordination", "Chemical Coordination and Integration"
    ],
    "Physics": [
      "Units and Measurements", "Motion in a Straight Line", "Motion in a Plane",
      "Laws of Motion", "Work, Energy and Power", "System of Particles and Rotational Motion",
      "Gravitation", "Mechanical Properties of Solids", "Mechanical Properties of Fluids",
      "Thermal Properties of Matter", "Thermodynamics", "Kinetic Theory", "Oscillations", "Waves"
    ],
    "Chemistry": [
      "Some Basic Concepts of Chemistry", "Structure of Atom", "Classification of Elements and Periodicity",
      "Chemical Bonding and Molecular Structure", "Thermodynamics", "Equilibrium",
      "Redox Reactions", "Organic Chemistry: Some Basic Principles & Techniques", "Hydrocarbons"
    ]
  },
  "12": {
    "Biology": [
      "Sexual Reproduction in Flowering Plants", "Human Reproduction", "Reproductive Health",
      "Principles of Inheritance and Variation", "Molecular Basis of Inheritance", "Evolution",
      "Human Health and Disease", "Microbes in Human Welfare", "Biotechnology: Principles and Processes",
      "Biotechnology and its Applications", "Organisms and Populations", "Ecosystem",
      "Biodiversity and Conservation"
    ],
    "Physics": [
      "Electric Charges and Fields", "Electrostatic Potential and Capacitance", "Current Electricity",
      "Moving Charges and Magnetism", "Magnetism and Matter", "Electromagnetic Induction",
      "Alternating Current", "Electromagnetic Waves", "Ray Optics and Optical Instruments",
      "Wave Optics", "Dual Nature of Radiation and Matter", "Atoms", "Nuclei",
      "Semiconductor Electronics: Materials, Devices and Simple Circuits"
    ],
    "Chemistry": [
      "Solutions", "Electrochemistry", "Chemical Kinetics", "d- and f-Block Elements",
      "Coordination Compounds", "Haloalkanes and Haloarenes", "Alcohols, Phenols and Ethers",
      "Aldehydes, Ketones and Carboxylic Acids", "Amines", "Biomolecules"
    ]
  }
};

// OFFLINE HIGH-YIELD NEET QUESTIONS
const fallbackRepository = {
  "Biology": [
    {
      q: "Which enzyme is known as the molecular glue during recombinant DNA technology?",
      options: ["A) DNA Ligase", "B) DNA Polymerase", "C) Restriction Endonuclease", "D) Alkaline Phosphatase"],
      ans: "A",
      exp: "NCERT Class 12: DNA ligases catalyze the joining of DNA strands together by facilitating the formation of a phosphodiester bond."
    },
    {
      q: "In human females, the primary oocytes are arrested at which stage until puberty?",
      options: ["A) Metaphase II", "B) Prophase I (Diplotene)", "C) Anaphase I", "D) Telophase II"],
      ans: "B",
      exp: "NCERT Class 12: Primary oocytes enter prophase-I of meiotic division and get temporarily arrested at the diplotene stage."
    },
    {
      q: "The functional unit of nature where living organisms interact among themselves and with the physical environment is called:",
      options: ["A) Biosphere", "B) Ecosystem", "C) Biome", "D) Community"],
      ans: "B",
      exp: "NCERT Class 12: An ecosystem can be visualised as a functional unit of nature."
    }
  ],
  "Physics": [
    {
      q: "What is the work done in moving a test charge over an equipotential surface?",
      options: ["A) Maximum", "B) Negative", "C) Zero", "D) Infinite"],
      ans: "C",
      exp: "NCERT Class 12: Since potential difference ΔV = 0 on an equipotential surface, W = qΔV = 0."
    },
    {
      q: "A body of mass 2 kg moving at 10 m/s is brought to rest in 2 seconds. The opposing force applied is:",
      options: ["A) 5 N", "B) 10 N", "C) 20 N", "D) 2 N"],
      ans: "B",
      exp: "a = (v - u)/t = (0 - 10)/2 = -5 m/s². Force = m * a = 2 kg * 5 m/s² = 10 N."
    }
  ],
  "Chemistry": [
    {
      q: "Which of the following compounds exhibits highest boiling point due to extensive intermolecular hydrogen bonding?",
      options: ["A) Ethanol", "B) Diethyl ether", "C) Ethane", "D) Chloromethane"],
      ans: "A",
      exp: "NCERT Class 12: Alcohols have significantly higher boiling points due to intermolecular hydrogen bonding between oxygen and hydrogen."
    },
    {
      q: "The oxidation state of Chromium in Cr2O7^(2-) is:",
      options: ["A) +3", "B) +4", "C) +6", "D) +7"],
      ans: "C",
      exp: "2x + 7(-2) = -2 => 2x - 14 = -2 => 2x = 12 => x = +6."
    }
  ]
};

let currentQ = null;
let score = 0;
let correctCount = 0;
let wrongCount = 0;
let timer = null;
let secondsLeft = 60;

function renderChapters() {
  const cls = document.getElementById("classSel").value;
  const sub = document.getElementById("subjectSel").value;
  const chSel = document.getElementById("chapterSel");
  chSel.innerHTML = "";

  (syllabusDB[cls][sub] || []).forEach(ch => {
    const opt = document.createElement("option");
    opt.value = ch;
    opt.textContent = ch;
    chSel.appendChild(opt);
  });
}

function startTimer() {
  clearInterval(timer);
  secondsLeft = 60;
  const tBox = document.getElementById("timerBox");
  tBox.textContent = "00:60";
  tBox.style.color = "var(--warning)";

  timer = setInterval(() => {
    secondsLeft--;
    const display = secondsLeft < 10 ? `00:0${secondsLeft}` : `00:${secondsLeft}`;
    tBox.textContent = display;

    if (secondsLeft <= 10) {
      tBox.style.color = "var(--danger)";
    }

    if (secondsLeft <= 0) {
      clearInterval(timer);
      timeOutAnswer();
    }
  }, 1000);
}

function timeOutAnswer() {
  const allBtns = document.querySelectorAll(".opt-btn");
  allBtns.forEach(b => b.disabled = true);
  wrongCount++;
  score -= 1;
  updateStats();

  allBtns.forEach(b => {
    if (b.dataset.key === currentQ.ans) {
      b.classList.add("correct");
    }
  });

  const expBox = document.getElementById("expDisplay");
  expBox.innerHTML = `<strong>Time Out! (-1 Mark)</strong><br><strong>Explanation:</strong> ${currentQ.exp}`;
  expBox.style.display = "block";
  document.getElementById("nextQuestionBtn").style.display = "block";
}

async function nextQuestion() {
  clearInterval(timer);
  const genBtn = document.getElementById("generateBtn");
  const nextBtn = document.getElementById("nextQuestionBtn");
  const expBox = document.getElementById("expDisplay");
  const arena = document.getElementById("quizArena");
  const badge = document.getElementById("engineBadge");
  const apiKey = document.getElementById("apiKeyInput").value.trim();

  genBtn.disabled = true;
  genBtn.textContent = "Fetching NEET Standard Question...";
  nextBtn.style.display = "none";
  expBox.style.display = "none";

  const cls = document.getElementById("classSel").value;
  const sub = document.getElementById("subjectSel").value;
  const ch = document.getElementById("chapterSel").value;

  if (apiKey) {
    try {
      const prompt = `Act as an expert NEET Exam Question Setter. 
Generate 1 fresh, rigorous multiple choice question strictly based on NCERT Class ${cls} ${sub}, Chapter: "${ch}".
Format response strictly as valid raw JSON (no markdown ticks or backticks):
{
  "question": "Question text here",
  "options": ["A) Text", "B) Text", "C) Text", "D) Text"],
  "ans": "A",
  "exp": "Detailed NCERT reference line-by-line explanation"
}`;

      const res = await fetch(`https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${apiKey}`, {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({ contents: [{ parts: [{ text: prompt }] }] })
      });

      const data = await res.json();
      let text = data.candidates[0].content.parts[0].text;
      text = text.replace(/```json/g, "").replace(/```/g, "").trim();
      currentQ = JSON.parse(text);

      badge.textContent = "AI Dynamic Engine";
      badge.className = "badge-tag tag-ai";
    } catch (err) {
      console.warn("AI Load Failed, switching to built-in test bank", err);
      pickFallback(sub, ch);
    }
  } else {
    pickFallback(sub, ch);
  }

  showQuestion();
  arena.style.display = "flex";
  genBtn.disabled = false;
  genBtn.textContent = "Change / Refresh";
  startTimer();
}

function pickFallback(sub, ch) {
  const pool = fallbackRepository[sub] || fallbackRepository["Biology"];
  const item = pool[Math.floor(Math.random() * pool.length)];
  currentQ = {
    question: `[${ch}] ` + item.q,
    options: item.options,
    ans: item.ans,
    exp: item.exp
  };
  const badge = document.getElementById("engineBadge");
  badge.textContent = "NCERT Offline Bank";
  badge.className = "badge-tag tag-offline";
}

function showQuestion() {
  document.getElementById("qDisplay").textContent = currentQ.question;
  const container = document.getElementById("optContainer");
  container.innerHTML = "";

  currentQ.options.forEach(opt => {
    const key = opt.trim().charAt(0);
    const btn = document.createElement("button");
    btn.className = "opt-btn";
    btn.dataset.key = key;
    btn.textContent = opt;
    btn.onclick = () => evaluateChoice(btn, key);
    container.appendChild(btn);
  });
}

function evaluateChoice(selectedBtn, chosenKey) {
  clearInterval(timer);
  const allBtns = document.querySelectorAll(".opt-btn");
  allBtns.forEach(b => b.disabled = true);

  const isCorrect = chosenKey === currentQ.ans;

  if (isCorrect) {
    score += 4;
    correctCount++;
    selectedBtn.classList.add("correct");
  } else {
    score -= 1;
    wrongCount++;
    selectedBtn.classList.add("wrong");
    allBtns.forEach(b => {
      if (b.dataset.key === currentQ.ans) {
        b.classList.add("correct");
      }
    });
  }

  updateStats();

  const expBox = document.getElementById("expDisplay");
  expBox.innerHTML = `<strong>${isCorrect ? '✅ Correct (+4)' : '❌ Incorrect (-1)'}</strong><br><strong>Explanation:</strong> ${currentQ.exp}`;
  expBox.style.display = "block";

  document.getElementById("nextQuestionBtn").style.display = "block";
}

function updateStats() {
  const total = correctCount + wrongCount;
  const acc = total > 0 ? Math.round((correctCount / total) * 100) : 0;

  document.getElementById("scoreDisp").textContent = score;
  document.getElementById("correctDisp").textContent = correctCount;
  document.getElementById("wrongDisp").textContent = wrongCount;
  document.getElementById("accDisp").textContent = `${acc}%`;
}

renderChapters();
</script>

</body>
</html>
