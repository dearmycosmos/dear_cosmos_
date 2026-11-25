<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="artifact-type" content="tool">
  <meta name="design-style" content="nocturne">
  <title>너에게 전하지 못했던 말들</title>
  <link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400..700;1,400..600&family=JetBrains+Mono:wght@400;500;600&family=Noto+Sans+KR:wght@400;500;600;700&family=Noto+Serif+KR:wght@400;500;600&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      color-scheme: dark;

      /* Nocturne base palette */
      --background: #0a101d;
      --surface-container-low: #0e1626;
      --surface-container: #111b2e;
      --surface-container-high: #17243c;

      --on-surface: #f2ece1;
      --on-surface-variant: #9ba8bf;

      --outline: #384d73;
      --outline-variant: #21304d;

      --primary: #dfaa5b;
      --on-primary: #0a101d;
      --primary-container: #2b261c;
      --on-primary-container: #f5dcb0;
      --secondary: #687a99;
      --tertiary: #7cc4e8;
      --error: #f27474;
      --on-error: #1a0606;

      --data-1: #dfaa5b;
      --data-2: #7cc4e8;
      --data-3: #52d19c;
      --data-4: #e07a5f;
      --data-context: #4a5d80;

      /* Semantic & interaction tokens */
      --positive: #52d19c;
      --warning: #e5b869;
      --focus: #dfaa5b;
      --cloak-red: #b93842;

      /* Atmosphere & analog paper tokens */
      --glass-bg: rgba(14, 22, 38, 0.72);
      --glass-bg-strong: rgba(17, 27, 46, 0.9);
      --scrim-bg: rgba(6, 10, 18, 0.68);
      --paper-bg: #f4ebd8;
      --paper-edge: #dfd0b4;
      --paper-ink: #2b241d;
      --paper-ink-muted: #6e5f4f;
      --paper-shadow: 0 22px 48px rgba(4, 7, 15, 0.62);
      --panel-highlight: inset 0 1px 0 rgba(242, 236, 225, 0.06);
      --sky-tint: color-mix(in srgb, var(--tertiary) 14%, transparent);
      --brass-tint: color-mix(in srgb, var(--primary) 16%, transparent);
      --mint-tint: color-mix(in srgb, var(--positive) 15%, transparent);
      --error-tint: color-mix(in srgb, var(--error) 16%, transparent);
      --title-glow: 0 0 28px rgba(242, 236, 225, 0.32), 0 0 60px rgba(124, 196, 232, 0.16);
      --star-btn-glow: 0 0 18px rgba(223, 170, 91, 0.25);

      /* Fonts (Korean first per non-Latin rule) */
      --font-headline: 'Noto Serif KR', 'EB Garamond', serif;
      --font-body: 'Noto Sans KR', 'Plus Jakarta Sans', sans-serif;
      --font-label: 'JetBrains Mono', 'Noto Sans KR', monospace;

      /* Type scale */
      --display-size: clamp(1.5rem, 1.15rem + 1.6vw, 2.35rem);
      --headline-size: clamp(1.2rem, 1.05rem + 0.55vw, 1.5rem);
      --subhead-size: clamp(1rem, 0.95rem + 0.25vw, 1.15rem);
      --body-size: clamp(0.9375rem, 0.9rem + 0.15vw, 1rem);
      --label-size: 0.75rem;

      /* Radii */
      --rounded: 0.375rem;
      --rounded-lg: 0.75rem;
      --rounded-full: 9999px;

      /* Borders */
      --hairline: 1px solid var(--outline-variant);
      --hairline-strong: 1px solid var(--outline);

      /* Spacing */
      --space-xs: 0.25rem;
      --space-sm: 0.5rem;
      --space-md: 1rem;
      --space-lg: 1.5rem;
      --space-xl: 2.5rem;
      --space-2xl: 4rem;

      /* Motion */
      --ease-out: cubic-bezier(0.16, 1, 0.3, 1);
      --ease-in-out: cubic-bezier(0.65, 0, 0.35, 1);
      --dur-micro: 120ms;
      --dur-short: 240ms;
      --dur-long: 440ms;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
      overflow-x: clip;
      background-color: var(--background);
      color: var(--on-surface);
      font-family: var(--font-body);
      font-size: var(--body-size);
      line-height: 1.6;
      word-break: keep-all;
      overflow-wrap: break-word;
      user-select: none;
      -webkit-font-smoothing: antialiased;
    }

    button, input, textarea, select {
      font-family: inherit;
      font-size: inherit;
      color: inherit;
    }

    button:focus-visible,
    input:focus-visible,
    textarea:focus-visible {
      outline: 2px solid var(--focus);
      outline-offset: 2px;
    }

    .stage-root {
      position: relative;
      width: 100%;
      height: 100dvh;
      min-height: 520px;
      overflow: hidden;
      background: var(--background);
    }

    #sky-canvas {
      display: block;
      width: 100%;
      height: 100%;
      cursor: crosshair;
      touch-action: none;
    }

    /* Breathing Center-Top Title */
    .sky-header {
      position: static !important;
      pointer-events: none;
    }

    .sky-title-wrap {
      position: absolute;
      top: clamp(1.1rem, 3.2vh, 2.5rem);
      left: 50%;
      transform: translateX(-50%);
      text-align: center;
      pointer-events: none;
      z-index: 4;
      width: min(92vw, 680px);
    }

    .sky-title {
      margin: 0;
      font-family: var(--font-headline);
      font-weight: 500;
      font-size: var(--display-size);
      line-height: 1.25;
      color: var(--on-surface);
      text-shadow: var(--title-glow);
      animation: breatheTitle 5.4s var(--ease-in-out) infinite;
    }

    @keyframes breatheTitle {
      0%, 100% {
        opacity: 0.78;
        filter: drop-shadow(0 0 8px rgba(242, 236, 225, 0.16));
      }
      50% {
        opacity: 1;
        filter: drop-shadow(0 0 18px rgba(242, 236, 225, 0.36));
      }
    }

    /* Top-right floating transparent starlight HUD */
    .hud-bar {
      position: absolute;
      top: var(--space-md);
      right: var(--space-md);
      display: flex;
      align-items: center;
      gap: var(--space-sm);
      z-index: 10;
    }

    .hud-btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 0.35rem;
      min-height: 40px;
      padding: 0.4rem 0.9rem;
      border-radius: var(--rounded-full);
      background: var(--glass-bg);
      border: 1px solid rgba(242, 236, 225, 0.18);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      color: var(--on-surface);
      font-size: var(--label-size);
      font-weight: 500;
      cursor: pointer;
      box-shadow: var(--panel-highlight), var(--star-btn-glow);
      transition: background-color var(--dur-micro) var(--ease-out),
                  border-color var(--dur-micro) var(--ease-out),
                  transform var(--dur-micro) var(--ease-out);
    }

    .hud-btn:hover {
      background: var(--surface-container-high);
      border-color: rgba(223, 170, 91, 0.45);
    }

    .hud-btn:active {
      transform: translateY(1px);
    }

    .badge-count {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-width: 1.25rem;
      height: 1.25rem;
      padding: 0 0.35rem;
      border-radius: var(--rounded-full);
      background: var(--brass-tint);
      color: var(--primary);
      font-family: var(--font-label);
      font-size: 0.72rem;
      font-weight: 600;
    }

    /* Sound Control Popover */
    .sound-popover {
      position: absolute;
      top: calc(var(--space-md) + 48px);
      right: var(--space-md);
      width: min(90vw, 320px);
      z-index: 15;
      background: var(--glass-bg-strong);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid rgba(242, 236, 225, 0.16);
      border-radius: var(--rounded-lg);
      padding: var(--space-lg);
      box-shadow: var(--panel-highlight), var(--paper-shadow);
      display: none;
      flex-direction: column;
      gap: var(--space-md);
    }

    .sound-popover.is-open {
      display: flex;
    }

    .popover-head {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: var(--hairline);
      padding-bottom: var(--space-xs);
    }

    .popover-title {
      margin: 0;
      font-family: var(--font-headline);
      font-size: var(--subhead-size);
      font-weight: 500;
    }

    .close-icon-btn {
      background: transparent;
      border: none;
      color: var(--on-surface-variant);
      cursor: pointer;
      padding: 0.2rem;
      border-radius: var(--rounded);
    }

    .close-icon-btn:hover {
      color: var(--on-surface);
      background: var(--surface-container-high);
    }

    .sound-row {
      display: flex;
      flex-direction: column;
      gap: 0.25rem;
    }

    .sound-label-row {
      display: flex;
      justify-content: space-between;
      font-size: 0.8rem;
    }

    .sound-val {
      font-family: var(--font-label);
      color: var(--primary);
    }

    input[type="range"] {
      width: 100%;
      accent-color: var(--primary);
      cursor: pointer;
    }

    /* Bottom Guide Text */
    .bottom-guide {
      position: absolute;
      bottom: clamp(1rem, 3vh, 2rem);
      left: 50%;
      transform: translateX(-50%);
      pointer-events: none;
      z-index: 4;
      text-align: center;
      width: min(92vw, 420px);
    }

    .guide-text {
      margin: 0;
      font-family: var(--font-headline);
      font-size: clamp(0.875rem, 0.82rem + 0.25vw, 1.05rem);
      color: rgba(242, 236, 225, 0.65);
      text-shadow: 0 2px 14px rgba(6, 10, 18, 0.8);
      animation: pulseGuide 4.5s var(--ease-in-out) infinite;
    }

    @keyframes pulseGuide {
      0%, 100% { opacity: 0.55; }
      50% { opacity: 0.95; }
    }

    /* Modal Backdrop */
    .modal-backdrop {
      position: fixed;
      inset: 0;
      z-index: 30;
      display: none;
      align-items: center;
      justify-content: center;
      padding: var(--space-md);
      background: var(--scrim-bg);
      backdrop-filter: blur(8px);
      -webkit-backdrop-filter: blur(8px);
    }

    .modal-backdrop.is-open {
      display: flex;
    }

    /* Generic Nocturne Modal */
    .modal-card {
      width: min(100%, 460px);
      max-height: 90dvh;
      overflow-y: auto;
      background: var(--surface-container);
      border: 1px solid rgba(242, 236, 225, 0.16);
      border-radius: var(--rounded-lg);
      padding: var(--space-xl);
      box-shadow: var(--panel-highlight), var(--paper-shadow);
    }

    .modal-kicker {
      margin: 0 0 0.25rem;
      font-size: 0.75rem;
      color: var(--primary);
      font-weight: 500;
    }

    .modal-title {
      margin: 0 0 var(--space-lg);
      font-family: var(--font-headline);
      font-size: var(--headline-size);
      font-weight: 500;
    }

    .field-group {
      display: flex;
      flex-direction: column;
      gap: 0.35rem;
      margin-bottom: var(--space-md);
    }

    .field-label {
      font-size: var(--label-size);
      color: var(--on-surface-variant);
    }

    .text-input,
    .text-area {
      width: 100%;
      background: var(--background);
      border: var(--hairline-strong);
      border-radius: var(--rounded);
      padding: 0.65rem 0.85rem;
      color: var(--on-surface);
      line-height: 1.55;
    }

    .text-area {
      min-height: 7rem;
      resize: vertical;
    }

    .text-input:focus,
    .text-area:focus {
      outline: none;
      border-color: var(--primary);
      box-shadow: 0 0 0 2px var(--brass-tint);
    }

    .modal-btn-row {
      display: flex;
      justify-content: flex-end;
      gap: var(--space-sm);
      margin-top: var(--space-lg);
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: var(--space-xs);
      min-height: 42px;
      padding: 0.5rem 1.1rem;
      border-radius: var(--rounded);
      font-size: var(--label-size);
      font-weight: 600;
      cursor: pointer;
      border: 1px solid transparent;
      transition: background-color var(--dur-micro) var(--ease-out),
                  border-color var(--dur-micro) var(--ease-out);
    }

    .btn-primary {
      background: var(--primary);
      color: var(--on-primary);
    }

    .btn-primary:hover {
      background: var(--on-primary-container);
    }

    .btn-secondary {
      background: transparent;
      border-color: var(--outline);
      color: var(--on-surface);
    }

    .btn-secondary:hover {
      background: var(--surface-container-high);
      border-color: var(--primary);
    }

    .btn-ghost {
      background: transparent;
      color: var(--on-surface-variant);
    }

    .btn-ghost:hover {
      background: var(--surface-container-high);
      color: var(--on-surface);
    }

    /* Paper boat & Fallen Star Read Card */
    .paper-letter-card {
      background-color: var(--paper-bg);
      color: var(--paper-ink);
      border-radius: var(--rounded-lg);
      padding: var(--space-xl);
      box-shadow: var(--paper-shadow);
      border: 1px solid var(--paper-edge);
      width: min(100%, 460px);
    }

    .paper-recipient {
      font-family: var(--font-headline);
      font-size: var(--subhead-size);
      font-weight: 600;
      color: var(--paper-ink);
      margin: 0 0 var(--space-md);
    }

    .paper-body {
      font-family: var(--font-headline);
      font-size: 1.05rem;
      line-height: 1.8;
      white-space: pre-wrap;
      margin: 0 0 var(--space-lg);
    }

    .paper-sender {
      text-align: right;
      font-family: var(--font-headline);
      color: var(--paper-ink-muted);
      margin: 0;
    }

    /* Toast Notification */
    .toast-msg {
      position: absolute;
      bottom: clamp(4rem, 9vh, 6rem);
      left: 50%;
      transform: translateX(-50%);
      z-index: 25;
      padding: var(--space-sm) var(--space-lg);
      border-radius: var(--rounded-full);
      background: var(--glass-bg-strong);
      border: 1px solid rgba(242, 236, 225, 0.2);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      color: var(--on-surface);
      font-size: var(--label-size);
      box-shadow: var(--star-btn-glow);
      pointer-events: none;
      display: none;
    }

    .toast-msg.is-visible {
      display: block;
    }
  </style>
</head>
<body>
  <div class="stage-root">
    <canvas id="sky-canvas"></canvas>

    <div class="sky-title-wrap">
      <h1 class="sky-title">너에게 전하지 못했던 말들</h1>
    </div>

    <!-- Top Right HUD -->
    <nav class="hud-bar">
      <button type="button" class="hud-btn" id="btn-sound-toggle" onclick="toggleSoundPopover()">
        <span>🔊 별빛 소리</span>
      </button>
      <button type="button" class="hud-btn" id="btn-archive-toggle" onclick="openArchiveModal()">
        <span>✨ 별자리 보관함</span>
        <span class="badge-count" id="archive-count-badge">0</span>
      </button>
    </nav>

    <!-- Sound Popover -->
    <div class="sound-popover" id="sound-popover">
      <div class="popover-head">
        <h3 class="popover-title">밤하늘 소리 조절</h3>
        <button type="button" class="close-icon-btn" onclick="toggleSoundPopover()">✕</button>
      </div>
      <div class="sound-row">
        <div class="sound-label-row">
          <span>배경음 (피아노)</span>
          <span class="sound-val" id="val-bgm">70%</span>
        </div>
        <input type="range" id="slider-bgm" min="0" max="100" value="70" oninput="updateAudioVol('bgm', this.value)">
      </div>
      <div class="sound-row">
        <div class="sound-label-row">
          <span>별빛음 (실로폰·바이올린)</span>
          <span class="sound-val" id="val-starlight">80%</span>
        </div>
        <input type="range" id="slider-starlight" min="0" max="100" value="80" oninput="updateAudioVol('starlight', this.value)">
      </div>
      <div class="sound-row">
        <div class="sound-label-row">
          <span>물소리 (호수 발자국)</span>
          <span class="sound-val" id="val-water">75%</span>
        </div>
        <input type="range" id="slider-water" min="0" max="100" value="75" oninput="updateAudioVol('water', this.value)">
      </div>
    </div>

    <!-- Bottom Guide -->
    <div class="bottom-guide">
      <p class="guide-text">하늘을 클릭하면 궤도가 보이게 됩니다</p>
    </div>

    <!-- Toast -->
    <div class="toast-msg" id="toast-banner"></div>
  </div>

  <!-- Name Input Initial Modal -->
  <div class="modal-backdrop is-open" id="name-modal-backdrop">
    <div class="modal-card">
      <p class="modal-kicker">밤하늘 바다에 오신 것을 환영합니다</p>
      <h2 class="modal-title">당신의 이름을 적어주세요</h2>
      <div class="field-group">
        <label class="field-label" for="user-name-input">캐릭터 이름</label>
        <input type="text" class="text-input" id="user-name-input" placeholder="이름을 입력하세요 (예: 밤바람)" maxlength="15" value="여행자">
      </div>
      <div class="modal-btn-row">
        <button type="button" class="btn btn-primary" onclick="confirmName()">밤하늘 시작하기</button>
      </div>
    </div>
  </div>

  <!-- Write Letter Modal -->
  <div class="modal-backdrop" id="write-modal-backdrop">
    <div class="modal-card">
      <p class="modal-kicker">별의 궤적 위에 남기는 기록</p>
      <h2 class="modal-title">전하지 못했던 말 적기</h2>
      <div class="field-group">
        <label class="field-label" for="letter-to">받는 이</label>
        <input type="text" class="text-input" id="letter-to" placeholder="누구에게 전하는 말인가요?" maxlength="40">
      </div>
      <div class="field-group">
        <label class="field-label" for="letter-body">편지 내용</label>
        <textarea class="text-area" id="letter-body" placeholder="마음속 묵혀둔 이야기를 적어주세요." maxlength="500"></textarea>
      </div>
      <div class="field-group">
        <label class="field-label" for="letter-from">보내는 이 (선택)</label>
        <input type="text" class="text-input" id="letter-from" placeholder="익명 가능" maxlength="30">
      </div>
      <div class="modal-btn-row">
        <button type="button" class="btn btn-ghost" onclick="closeModal('write-modal-backdrop')">취소</button>
        <button type="button" class="btn btn-secondary" onclick="submitStarLetter('keep')">간직하기</button>
        <button type="button" class="btn btn-primary" onclick="submitStarLetter('send')">보내기</button>
      </div>
    </div>
  </div>

  <!-- Read Letter Modal -->
  <div class="modal-backdrop" id="read-modal-backdrop">
    <div class="paper-letter-card">
      <p class="modal-kicker" id="read-kicker">도착한 편지</p>
      <h3 class="paper-recipient" id="read-to"></h3>
      <div class="paper-body" id="read-body"></div>
      <p class="paper-sender" id="read-from"></p>
      <div class="modal-btn-row">
        <button type="button" class="btn btn-secondary" onclick="closeModal('read-modal-backdrop')">닫기</button>
        <button type="button" class="btn btn-primary" id="btn-keep-read" onclick="keepCurrentLetter()">보관함에 담기</button>
      </div>
    </div>
  </div>

  <!-- 1:1 Anonymous Chat Request Modal -->
  <div class="modal-backdrop" id="chat-req-backdrop">
    <div class="modal-card">
      <p class="modal-kicker">다른 사용자 접속</p>
      <h2 class="modal-title" id="chat-req-title">대화 요청이 도착했습니다</h2>
      <p id="chat-req-desc">상대방 캐릭터와 1:1 익명 대화를 시작하시겠습니까?</p>
      <div class="modal-btn-row">
        <button type="button" class="btn btn-ghost" onclick="declineChat()">거절</button>
        <button type="button" class="btn btn-primary" onclick="acceptChat()">수락하기</button>
      </div>
    </div>
  </div>

  <!-- 1:1 Anonymous Chat Modal -->
  <div class="modal-backdrop" id="chat-box-backdrop">
    <div class="modal-card" style="width: min(100%, 500px);">
      <p class="modal-kicker">1:1 익명 대화방</p>
      <h2 class="modal-title" id="chat-partner-name">익명의 밤하늘 여행자</h2>
      <div id="chat-messages" style="height: 220px; overflow-y: auto; background: var(--background); border: var(--hairline); border-radius: var(--rounded); padding: var(--space-md); margin-bottom: var(--space-md); display: flex; flex-direction: column; gap: var(--space-xs);">
        <p style="font-size: 0.8rem; color: var(--on-surface-variant); text-align: center;">대화가 연결되었습니다. 따뜻한 대화를 나눠보세요.</p>
      </div>
      <div style="display: flex; gap: var(--space-xs);">
        <input type="text" class="text-input" id="chat-input" placeholder="메시지를 입력하세요..." onkeydown="if(event.key==='Enter') sendChatMessage()">
        <button type="button" class="btn btn-primary" onclick="sendChatMessage()">전송</button>
      </div>
      <div class="modal-btn-row">
        <button type="button" class="btn btn-ghost" onclick="closeModal('chat-box-backdrop')">대화 종료</button>
      </div>
    </div>
  </div>

  <!-- Archive Modal -->
  <div class="modal-backdrop" id="archive-modal-backdrop">
    <div class="modal-card" style="width: min(100%, 600px);">
      <p class="modal-kicker">나의 밤하늘 기록</p>
      <h2 class="modal-title">별자리 보관함</h2>
      <div id="archive-list-wrap" style="max-height: 320px; overflow-y: auto; display: flex; flex-direction: column; gap: var(--space-sm);"></div>
      <div class="modal-btn-row">
        <button type="button" class="btn btn-primary" onclick="closeModal('archive-modal-backdrop')">밤하늘로 돌아가기</button>
      </div>
    </div>
  </div>

  <script>
    (function() {
      'use strict';

      /* State */
      const state = {
        userName: '여행자',
        keptLetters: [],
        sentLetters: [],
        activeLetter: null,
        trajectories: [],
        fallenStars: [],
        paperBoat: { x: 0, y: 0, reached: false, letter: null },
        otherUsers: [],
        maxTrajectories: 9
      };

      const canvas = document.getElementById('sky-canvas');
      const ctx = canvas.getContext('2d');
      let W = window.innerWidth, H = window.innerHeight;

      function resize() {
        W = window.innerWidth;
        H = window.innerHeight;
        canvas.width = W;
        canvas.height = H;
        character.y = getGroundY(character.x);
        state.paperBoat.x = W * 0.82;
        state.paperBoat.y = getWaterY() + 10;
      }

      function getWaterY() { return H * 0.76; }
      function getShoreX() { return W * 0.52; }
      function getGroundY(x) {
        const shoreX = getShoreX();
        const waterY = getWaterY();
        if (x < shoreX) return waterY;
        const u = (x - shoreX) / (W - shoreX);
        return waterY - u * u * (H * 0.18);
      }

      const character = {
        x: W * 0.25,
        y: 0,
        targetX: W * 0.25,
        wetness: 0,
        facingLeft: false
      };

      /* Audio synth */
      const audio = {
        ctx: null,
        init() {
          if (!this.ctx) {
            const AC = window.AudioContext || window.webkitAudioContext;
            if (AC) this.ctx = new AC();
          }
        },
        playNote(freq) {
          if (!this.ctx) return;
          const osc = this.ctx.createOscillator();
          const g = this.ctx.createGain();
          osc.type = 'sine';
          osc.frequency.value = freq;
          g.gain.setValueAtTime(0.08, this.ctx.currentTime);
          g.gain.exponentialRampToValueAtTime(0.0001, this.ctx.currentTime + 1.2);
          osc.connect(g);
          g.connect(this.ctx.destination);
          osc.start();
          osc.stop(this.ctx.currentTime + 1.25);
        }
      };

      /* UI Handlers */
      window.confirmName = function() {
        const val = document.getElementById('user-name-input').value.trim();
        if (val) state.userName = val;
        document.getElementById('name-modal-backdrop').classList.remove('is-open');
        audio.init();
      };

      window.toggleSoundPopover = function() {
        document.getElementById('sound-popover').classList.toggle('is-open');
      };

      window.updateAudioVol = function(type, val) {
        document.getElementById('val-' + type).textContent = val + '%';
      };

      window.openArchiveModal = function() {
        renderArchive();
        document.getElementById('archive-modal-backdrop').classList.add('is-open');
      };

      window.closeModal = function(id) {
        document.getElementById(id).classList.remove('is-open');
      };

      function renderArchive() {
        const wrap = document.getElementById('archive-list-wrap');
        wrap.innerHTML = '';
        if (state.keptLetters.length === 0) {
          wrap.innerHTML = '<p style="color:var(--on-surface-variant); text-align:center;">보관된 편지가 없습니다.</p>';
          return;
        }
        state.keptLetters.forEach((item, idx) => {
          const div = document.createElement('div');
          div.style.cssText = 'background:var(--surface-container-low); padding:0.8rem; border-radius:var(--rounded); border:var(--hairline);';
          div.innerHTML = `<strong style="color:var(--primary);">To. ${item.to}</strong><p style="margin:0.4rem 0;">${item.body}</p><small style="color:var(--on-surface-variant);">From. ${item.from}</small>`;
          wrap.appendChild(div);
        });
      }

      window.submitStarLetter = function(mode) {
        const to = document.getElementById('letter-to').value.trim() || '이름 없음';
        const body = document.getElementById('letter-body').value.trim();
        const from = document.getElementById('letter-from').value.trim() || state.userName;
        if (!body) return;

        const letter = { to, body, from, date: new Date().toLocaleDateString() };
        if (mode === 'keep') {
          state.keptLetters.push(letter);
          showToast('보관함에 편지가 저장되었습니다.');
        } else {
          state.sentLetters.push(letter);
          showToast('별의 궤적에 편지를 띄워 보냈습니다.');
        }
        document.getElementById('archive-count-badge').textContent = state.keptLetters.length;
        closeModal('write-modal-backdrop');
      };

      function showToast(msg) {
        const t = document.getElementById('toast-banner');
        t.textContent = msg;
        t.classList.add('is-visible');
        setTimeout(() => t.classList.remove('is-visible'), 3000);
      }

      /* Spawn Trajectory on canvas click */
      canvas.addEventListener('pointerdown', (e) => {
        audio.init();
        const rect = canvas.getBoundingClientRect();
        const cx = e.clientX - rect.left;
        const cy = e.clientY - rect.top;

        /* Move character if click ground */
        if (cy > H * 0.6) {
          character.targetX = cx;
          return;
        }

        /* Check paper boat click */
        const boatDx = cx - state.paperBoat.x;
        const boatDy = cy - state.paperBoat.y;
        if (Math.hypot(boatDx, boatDy) < 40) {
          if (state.paperBoat.reached) {
            readLetter({ to: '호수의 안부를 묻는 이에게', body: '빨간 망토 아이가 호수 너머 종이배에 다다랐습니다. 조용한 수면 위로 달빛이 번집니다.', from: '호수 파수꾼' });
          } else {
            showToast('빨간 망토 캐릭터가 종이배에 도달해야 열립니다.');
          }
          return;
        }

        /* Trajectories (Max 9) */
        if (state.trajectories.length >= state.maxTrajectories) {
          state.trajectories.shift();
        }

        const traj = {
          cx: cx,
          cy: cy,
          r: 60 + Math.random() * 80,
          progress: 0,
          color: '#dfaa5b',
          star: { x: cx, y: cy, createdAt: performance.now() }
        };
        state.trajectories.push(traj);
        audio.playNote(523 + Math.random() * 300);

        /* 10 seconds falling star timer */
        setTimeout(() => {
          const idx = state.trajectories.indexOf(traj);
          if (idx !== -1) {
            state.trajectories.splice(idx, 1);
            showToast('10초가 지나 별이 별똥별이 되어 사라졌습니다.');
          }
        }, 10000);
      });

      function readLetter(letter) {
        document.getElementById('read-to').textContent = 'To. ' + letter.to;
        document.getElementById('read-body').textContent = letter.body;
        document.getElementById('read-from').textContent = 'From. ' + letter.from;
        state.activeLetter = letter;
        document.getElementById('read-modal-backdrop').classList.add('is-open');
      }

      window.keepCurrentLetter = function() {
        if (state.activeLetter) {
          state.keptLetters.push(state.activeLetter);
          document.getElementById('archive-count-badge').textContent = state.keptLetters.length;
          showToast('보관함에 보관되었습니다.');
        }
        closeModal('read-modal-backdrop');
      };

      /* Chat simulation */
      window.acceptChat = function() {
        closeModal('chat-req-backdrop');
        document.getElementById('chat-box-backdrop').classList.add('is-open');
      };

      window.declineChat = function() {
        closeModal('chat-req-backdrop');
      };

      window.sendChatMessage = function() {
        const inp = document.getElementById('chat-input');
        const txt = inp.value.trim();
        if (!txt) return;

        const box = document.getElementById('chat-messages');
        const p1 = document.createElement('p');
        p1.style.cssText = 'align-self: flex-end; background:var(--brass-tint); color:var(--primary); padding:0.4rem 0.8rem; border-radius:var(--rounded); margin:0;';
        p1.textContent = txt;
        box.appendChild(p1);
        inp.value = '';

        setTimeout(() => {
          const p2 = document.createElement('p');
          p2.style.cssText = 'align-self: flex-start; background:var(--surface-container-high); padding:0.4rem 0.8rem; border-radius:var(--rounded); margin:0;';
          p2.textContent = '밤하늘 빛이 따뜻하네요. 반갑습니다!';
          box.appendChild(p2);
          box.scrollTop = box.scrollHeight;
        }, 1000);
      };

      /* Spawn initial mock other user */
      setTimeout(() => {
        state.otherUsers.push({
          name: '익명 여행자',
          x: W * 0.7,
          y: getGroundY(W * 0.7),
          accessory: '목도리',
          color: '#e07a5f'
        });
      }, 5000);

      /* Main Loop */
      function update(dt) {
        // Character move
        const dx = character.targetX - character.x;
        if (Math.abs(dx) > 2) {
          character.facingLeft = dx < 0;
          character.x += Math.sign(dx) * Math.min(Math.abs(dx), 130 * dt);
        }
        character.y = getGroundY(character.x);

        // Wetness
        if (character.x < getShoreX()) {
          character.wetness = Math.min(1, character.wetness + dt * 0.2);
        } else {
          character.wetness = Math.max(0, character.wetness - dt * 0.3);
        }

        // Check paperboat reach
        if (Math.abs(character.x - state.paperBoat.x) < 40) {
          state.paperBoat.reached = true;
        }
      }

      function draw() {
        ctx.clearRect(0, 0, W, H);

        // Sky gradient
        const grad = ctx.createLinearGradient(0, 0, 0, H);
        grad.addColorStop(0, '#0a101d');
        grad.addColorStop(0.6, '#111b2e');
        grad.addColorStop(1, '#0e1626');
        ctx.fillStyle = grad;
        ctx.fillRect(0, 0, W, H);

        // Hills & Lake
        const shoreX = getShoreX();
        const waterY = getWaterY();

        // Right Lake
        ctx.fillStyle = `rgba(18, 32, 58, ${0.85 + Math.sin(performance.now() * 0.002) * 0.05})`;
        ctx.beginPath();
        ctx.rect(0, waterY, shoreX, H - waterY);
        ctx.fill();

        // Lake ripples
        ctx.strokeStyle = 'rgba(124, 196, 232, 0.2)';
        ctx.lineWidth = 1;
        for (let i = 0; i < 5; i++) {
          const y = waterY + 15 + i * 14;
          ctx.beginPath();
          ctx.moveTo(10, y + Math.sin(performance.now() * 0.003 + i) * 3);
          ctx.lineTo(shoreX - 10, y + Math.sin(performance.now() * 0.003 + i + 1) * 3);
          ctx.stroke();
        }

        // Left Hill
        ctx.fillStyle = '#142238';
        ctx.beginPath();
        ctx.moveTo(shoreX, waterY);
        for (let x = shoreX; x <= W; x += 10) {
          ctx.lineTo(x, getGroundY(x));
        }
        ctx.lineTo(W, H);
        ctx.lineTo(shoreX, H);
        ctx.closePath();
        ctx.fill();

        // Grass clusters on hill
        ctx.fillStyle = '#223c52';
        for (let x = shoreX + 20; x < W; x += 60) {
          const gy = getGroundY(x);
          ctx.beginPath();
          ctx.arc(x, gy - 2, 6, 0, Math.PI * 2);
          ctx.arc(x + 5, gy - 4, 8, 0, Math.PI * 2);
          ctx.fill();
        }

        // Paper Boat
        ctx.fillStyle = '#f4ebd8';
        ctx.beginPath();
        const bx = state.paperBoat.x, by = state.paperBoat.y;
        ctx.moveTo(bx - 14, by);
        ctx.lineTo(bx + 14, by);
        ctx.lineTo(bx, by - 12);
        ctx.closePath();
        ctx.fill();

        // Trajectories & Stars
        state.trajectories.forEach(t => {
          ctx.strokeStyle = 'rgba(223, 170, 91, 0.3)';
          ctx.beginPath();
          ctx.arc(t.cx, t.cy, t.r, 0, Math.PI * 2);
          ctx.stroke();

          // Star
          ctx.fillStyle = '#dfaa5b';
          ctx.beginPath();
          ctx.arc(t.cx + t.r * Math.cos(performance.now() * 0.001), t.cy + t.r * Math.sin(performance.now() * 0.001), 6, 0, Math.PI * 2);
          ctx.fill();
        });

        // Other Users (Black silhouette with colored accessory)
        state.otherUsers.forEach(u => {
          ctx.fillStyle = '#05080e';
          ctx.beginPath();
          ctx.arc(u.x, u.y - 18, 7, 0, Math.PI * 2);
          ctx.fill();
          ctx.fillRect(u.x - 5, u.y - 11, 10, 11);

          // Colored Accessory (e.g. Scarf)
          ctx.fillStyle = u.color;
          ctx.fillRect(u.x - 6, u.y - 12, 12, 3);

          // Label
          ctx.fillStyle = 'rgba(242, 236, 225, 0.7)';
          ctx.font = '11px sans-serif';
          ctx.textAlign = 'center';
          ctx.fillText(u.name, u.x, u.y - 30);
        });

        // My Character (Red Cloak Little Girl)
        const cx = character.x, cy = character.y;

        // Cloak (Darker when wet)
        const wetDarken = character.wetness * 0.4;
        ctx.fillStyle = `rgb(${Math.round(185 * (1 - wetDarken))}, ${Math.round(56 * (1 - wetDarken))}, ${Math.round(66 * (1 - wetDarken))})`;
        ctx.beginPath();
        ctx.moveTo(cx, cy - 14);
        ctx.lineTo(cx - 10, cy);
        ctx.lineTo(cx + 10, cy);
        ctx.closePath();
        ctx.fill();

        // Head
        ctx.fillStyle = '#f4ebd8';
        ctx.beginPath();
        ctx.arc(cx, cy - 18, 6, 0, Math.PI * 2);
        ctx.fill();

        // Character Name Label
        ctx.fillStyle = '#f2ece1';
        ctx.font = '11px sans-serif';
        ctx.textAlign = 'center';
        ctx.fillText(state.userName, cx, cy - 28);
      }

      let lastT = performance.now();
      function boot() {
        resize();
        window.addEventListener('resize', resize);
        function loop(t) {
          const dt = (t - lastT) / 1000;
          lastT = t;
          update(dt);
          draw();
          requestAnimationFrame(loop);
        }
        requestAnimationFrame(loop);
      }

      if (document.readyState === 'complete') boot();
      else window.addEventListener('DOMContentLoaded', boot);
    })();
  </script>
</body>
</html>
