<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>【生命羅盤：星軌守護】</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* 基礎樣式：字體、背景、置中排版 */
        body {
            font-family: 'Noto Sans TC', sans-serif;
            /* 深邃的森林綠徑向漸變背景，營造自然與科技的交界感 */
            background: radial-gradient(circle at top left, #0A1B1C, #1C3A3B, #0A1B1C);
            color: #e2e8f0; /* 淺色文字，在深色背景上保持可讀性 */
            display: flex;
            justify-content: center;
            align-items: center; /* 讓內容置中 */
            min-height: 100vh; /* 最小高度為視窗高度 */
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
            overflow-y: auto; /* 允許垂直滾動以適應內容 */
        }

        /* 遊戲主容器 */
        .game-container {
            background-color: rgba(28, 58, 59, 0.9); /* 半透明深綠色背景 */
            border-radius: 16px; /* 更圓的圓角 */
            /* 更明顯的陰影和綠色光暈效果 */
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.6), 0 0 40px rgba(52, 211, 153, 0.4);
            border: 1px solid rgba(52, 211, 153, 0.3); /* 輕微綠色邊框 */
            animation: pulse-border 3s infinite alternate; /* 邊框脈衝動畫 */
            padding: 30px;
            max-width: 800px;
            width: 100%;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        /* 遊戲標題 */
        h1 {
            /* 亮綠色漸變文字，如同遊戲 LOGO */
            background: linear-gradient(90deg, #34D399, #6EE7B7);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-size: 2.8em; /* 更大字體 */
            margin-bottom: 20px;
            text-shadow: 0 0 10px rgba(52, 211, 153, 0.6); /* 標題發光效果 */
            animation: text-glow 2s infinite alternate; /* 文字發光動畫 */
            font-weight: 700; /* 加粗 */
        }

        /* 區塊標題 */
        h2 {
            color: #6EE7B7; /* 淺綠色 */
            font-size: 2em;
            margin-top: 25px;
            margin-bottom: 15px;
            text-shadow: 0 0 5px rgba(110, 231, 183, 0.3); /* 標題發光 */
            font-weight: 700; /* 加粗 */
        }

        /* 段落文字 */
        p {
            font-size: 1.1em;
            line-height: 1.6;
            margin-bottom: 15px;
            color: #bdc3c7; /* 淺灰藍文字 */
        }

        /* 狀態列 */
        .status-bar {
            display: flex;
            justify-content: space-around;
            background-color: rgba(44, 62, 80, 0.7); /* 深色半透明背景 */
            padding: 10px 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            border: 1px solid rgba(52, 73, 94, 0.5);
            box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.3);
        }

        /* 狀態項目文字 */
        .status-item {
            font-size: 1.2em;
            font-weight: bold;
            color: #f1c40f; /* 亮黃色，突出數值 */
            text-shadow: 0 0 5px rgba(241, 196, 15, 0.4);
        }

        /* 保險列表容器 */
        .insurance-list {
            text-align: left;
            margin-bottom: 20px;
            max-height: 180px; /* 限制高度，可滾動 */
            overflow-y: auto;
            padding: 10px;
            background-color: rgba(44, 62, 80, 0.7);
            border-radius: 8px;
            border: 1px solid rgba(52, 73, 94, 0.5);
            box-shadow: inset 0 0 8px rgba(0, 0, 0, 0.3);
        }

        /* 保險列表項目 */
        .insurance-item {
            padding: 8px 0;
            border-bottom: 1px dashed rgba(58, 83, 111, 0.5);
            color: #bdc3c7;
        }

        .insurance-item:last-child {
            border-bottom: none;
        }

        /* 選擇按鈕和行動按鈕 */
        .options-container button,
        .next-button,
        .start-button {
            /* 綠色漸變按鈕，電玩感 */
            background: linear-gradient(90deg, #10B981, #34D399);
            color: white;
            border: none;
            padding: 12px 25px;
            margin: 10px;
            border-radius: 8px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            position: relative; /* 為了按鈕的脈衝效果 */
            overflow: hidden; /* 隱藏脈衝溢出 */
        }

        .options-container button:hover,
        .next-button:hover,
        .start-button:hover {
            background-color: #0F9F6F; /* 更深的綠色 */
            transform: translateY(-3px); /* 輕微上浮 */
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4); /* 更強陰影 */
        }

        .options-container button:active,
        .next-button:active,
        .start-button:active {
            transform: translateY(0); /* 按下效果 */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .options-container button:disabled {
            background-color: #7f8c8d; /* 灰色禁用狀態 */
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

        /* 按鈕點擊脈衝效果 */
        .options-container button::after,
        .next-button::after,
        .start-button::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 5px;
            height: 5px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 50%;
            transform: scale(0);
            opacity: 0;
            animation: none; /* 預設不播放動畫 */
        }
        .options-container button:active::after,
        .next-button:active::after,
        .start-button:active::after {
            animation: btn-pulse 0.5s ease-out;
        }

        /* 訊息框 */
        .message {
            background-color: rgba(41, 128, 185, 0.8); /* 藍色半透明背景 */
            padding: 15px;
            border-radius: 8px;
            margin-top: 20px;
            font-size: 1.1em;
            color: white;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        /* 積極結果訊息 */
        .result-message.positive {
            background-color: rgba(46, 204, 113, 0.8); /* 綠色半透明 */
        }

        /* 消極結果訊息 */
        .result-message.negative {
            background-color: rgba(192, 57, 43, 0.8); /* 紅色半透明 */
        }

        /* 隱藏元素 */
        .hidden {
            display: none;
        }

        /* 結算報告中的強調文字 */
        .final-highlight {
            color: #f1c40f; /* 亮黃色 */
            text-shadow: 0 0 8px rgba(241, 196, 15, 0.5);
            font-weight: bold;
        }

        /* 守護者謎團揭示區 */
        #guardian-mystery {
            margin-top: 25px;
            padding: 20px;
            background-color: rgba(52, 73, 94, 0.7);
            border-radius: 10px;
            border: 1px solid rgba(46, 204, 113, 0.5);
            box-shadow: 0 0 15px rgba(46, 204, 113, 0.3);
        }
        #guardian-mystery h3 {
            color: #2ecc71;
            font-size: 1.5em;
            margin-bottom: 10px;
            text-shadow: 0 0 5px rgba(46, 204, 113, 0.4);
        }

        /* 國泰人壽 Logo */
        .cathay-logo {
            width: 150px; /* 調整大小 */
            height: auto;
            margin: 20px auto;
            display: block;
        }

        /* 獲得新生彈窗 */
        .rebirth-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.85); /* 更深的半透明背景 */
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.3s ease, visibility 0.3s ease;
        }

        .rebirth-modal.show {
            opacity: 1;
            visibility: visible;
        }

        .rebirth-content {
            background-color: #1C3A3B; /* 遊戲主題色 */
            border-radius: 15px;
            padding: 40px;
            text-align: center;
            box-shadow: 0 10px 40px rgba(52, 211, 153, 0.6); /* 綠色光暈 */
            border: 2px solid #34D399;
            max-width: 500px;
            width: 90%;
            transform: scale(0.9);
            transition: transform 0.3s ease;
        }

        .rebirth-modal.show .rebirth-content {
            transform: scale(1);
        }

        .rebirth-content h2 {
            color: #FFD700; /* 金色 */
            font-size: 2.2em;
            margin-bottom: 20px;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.5);
        }

        .rebirth-content p {
            font-size: 1.2em;
            margin-bottom: 30px;
            color: #e2e8f0;
        }

        .rebirth-button {
            background: linear-gradient(90deg, #FF6B6B, #FF8E8E); /* 鮮豔的漸變色 */
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 10px;
            font-size: 1.3em;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
        }

        .rebirth-button:hover {
            background: linear-gradient(90deg, #FF4B4B, #FF7E7E);
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }

        /* 動畫定義 */
        @keyframes pulse-border {
            0% { border-color: rgba(52, 211, 153, 0.3); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.6), 0 0 40px rgba(52, 211, 153, 0.4); }
            50% { border-color: rgba(110, 231, 183, 0.6); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.8), 0 0 60px rgba(110, 231, 183, 0.6); }
            100% { border-color: rgba(52, 211, 153, 0.3); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.6), 0 0 40px rgba(52, 211, 153, 0.4); }
        }

        @keyframes text-glow {
            0% { text-shadow: 0 0 8px rgba(52, 211, 153, 0.6); }
            50% { text-shadow: 0 0 15px rgba(110, 231, 183, 0.8); }
            100% { text-shadow: 0 0 8px rgba(52, 211, 153, 0.6); }
        }

        @keyframes btn-pulse {
            0% { transform: scale(0); opacity: 1; }
            100% { transform: translate(-50%, -50%) scale(2); opacity: 0; }
        }

        /* 測驗問題樣式 */
        .quiz-question-container {
            background-color: rgba(44, 62, 80, 0.7);
            padding: 25px;
            border-radius: 12px;
            margin-top: 20px;
            text-align: left;
        }
        .quiz-question-container h3 {
            color: #6EE7B7;
            font-size: 1.4em;
            margin-bottom: 15px;
        }
        .quiz-options button {
            display: block;
            width: 100%;
            background-color: #2980b9;
            margin-bottom: 10px;
            padding: 12px;
            border-radius: 8px;
            color: white;
            font-size: 1.05em;
            text-align: left;
            transition: background-color 0.3s ease;
        }
        .quiz-options button:hover {
            background-color: #3498db;
        }
        .quiz-options button.selected {
            border: 2px solid #f1c40f;
            box-shadow: 0 0 10px rgba(241, 196, 15, 0.5);
        }
        .quiz-options button.correct {
            background-color: #27ae60;
            border: 2px solid #2ecc71;
        }
        .quiz-options button.incorrect {
            background-color: #c0392b;
            border: 2px solid #e74c3c;
        }

        /* 行銷推廣區塊 (已移除，但保留樣式以防未來使用) */
        .promotion-block {
            background-color: rgba(65, 105, 225, 0.2); /* 較淺的藍色半透明 */
            border: 1px solid #4169E1;
            border-radius: 10px;
            padding: 20px;
            margin-top: 25px;
            margin-bottom: 25px;
            text-align: center;
            box-shadow: 0 0 15px rgba(65, 105, 225, 0.4);
            cursor: pointer; /* 顯示為可點擊 */
            transition: transform 0.2s ease;
        }

        .promotion-block:hover {
            transform: translateY(-5px);
        }

        .promotion-block h3 {
            color: #87CEFA; /* 天藍色 */
            font-size: 1.6em;
            margin-bottom: 10px;
            text-shadow: 0 0 8px rgba(135, 206, 250, 0.5);
        }

        .promotion-block p {
            color: #e0e0e0;
            font-size: 1.05em;
            line-height: 1.5;
            margin-bottom: 15px;
        }

        .promotion-block img.qr-code {
            width: 120px; /* QR Code 尺寸 */
            height: 120px;
            border: 2px solid white;
            border-radius: 5px;
            margin-top: 10px;
        }
        .promotion-block .cta-button {
            background: linear-gradient(90deg, #FF69B4, #FFB6C1); /* 粉色系按鈕 */
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            font-size: 1.1em;
            cursor: pointer;
            margin-top: 15px;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        .promotion-block .cta-button:hover {
            background: linear-gradient(90deg, #FF1493, #FF69B4);
            transform: translateY(-2px);
        }

        /* 排行榜數據顯示 */
        .leaderboard-data {
            background-color: rgba(44, 62, 80, 0.7);
            padding: 15px;
            border-radius: 8px;
            margin-top: 20px;
            text-align: left;
            border: 1px solid rgba(52, 73, 94, 0.5);
        }
        .leaderboard-data div {
            margin-bottom: 8px;
            font-size: 1.1em;
            color: #e2e8f0;
        }
        .leaderboard-data strong {
            color: #f1c40f;
        }
        .social-share-button {
            background: linear-gradient(90deg, #00C6FF, #0072FF); /* 藍色漸變 */
            color: white;
            border: none;
            padding: 12px 25px;
            margin: 15px 10px;
            border-radius: 8px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .social-share-button:hover {
            background: linear-gradient(90deg, #00B0E0, #0056B3);
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
        }
        .copy-message {
            color: #2ecc71;
            margin-top: 10px;
            font-weight: bold;
        }

        /* 新增地圖階段顯示 */
        #map-stage-display {
            background-color: rgba(52, 73, 94, 0.7);
            padding: 10px 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            color: #6EE7B7;
            font-size: 1.3em;
            font-weight: bold;
            text-shadow: 0 0 5px rgba(110, 231, 183, 0.3);
        }

        /* 星座幸運祝福卡樣式 */
        #zodiac-blessing-card {
            margin-top: 25px;
            padding: 20px;
            background: linear-gradient(45deg, #FFD700, #FFA500); /* 金色漸變 */
            border-radius: 12px;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.7); /* 金色光暈 */
            color: #0F1E2A; /* 深藍色文字，在亮色背景上保持可讀性 */
            font-size: 1.5em; /* 更大字體 */
            font-weight: bold;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.3); /* 輕微文字陰影 */
        }
        #zodiac-blessing-card h3 {
            color: #1A4B4C; /* 深綠色，與金色搭配 */
            font-size: 1.8em;
            margin-bottom: 10px;
            text-shadow: none; /* 移除發光，保持清晰 */
        }
        /* 新增的祝福名稱高亮樣式 */
        .blessing-name-highlight {
            color: #0A1B1C; /* 顯眼黑色 */
            font-size: 1.2em; /* 保持原有的字體大小放大效果 */
            text-shadow: none; /* 移除光暈效果，確保黑色清晰 */
        }

        /* 摩羯座圖片樣式 */
        /* #capricorn-blessing-image img {
            max-width: 150px;
            height: auto;
            border-radius: 8px;
            margin-top: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        } */
        /* 新增所有星座圖片容器的共同樣式 */
        .zodiac-image-container img {
            max-width: 150px; /* 圖片最大寬度 */
            height: auto;
            border-radius: 8px;
            margin-top: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>
<body>
    <div class="game-container" id="game-container">
        <h1 id="game-title">【生命羅盤：星軌守護】</h1>

        <!-- 1. 開始畫面 -->
        <div id="start-screen">
            <!-- 國泰人壽 Logo 已從封面移除 -->
            <p>歡迎來到《生命羅盤：星軌守護》！在這裡，您將扮演一位人生角色，體驗面對各種風險與挑戰的旅程。您的選擇，特別是是否擁有保險，將深刻影響您的命運。</p>
            <p style="color: #6EE7B7; font-weight: bold;">國泰人壽：您的人生最佳夥伴，從啟程開始守護。</p>
            <button class="start-button" id="startButton">啟動羅盤</button>
        </div>

        <!-- 2. 角色選擇畫面 (改為星座選擇) -->
        <div id="character-selection" class="hidden">
            <h2>選擇您的星座</h2>
            <p>您的星座將揭示您的人生特質，並決定您在遊戲中的初始角色。</p>
            <div class="options-container" id="zodiac-buttons-container">
                </div>
            <p id="role-description" style="margin-top: 20px; color: #bdc3c7;"></p>
            <p id="zodiac-blessing-description" style="margin-top: 10px; color: #f1c40f; font-weight: bold;"></p>
        </div>

        <!-- 3. 保險購買畫面 -->
        <div id="insurance-purchase" class="hidden">
            <h2>序章：人生啟航 - 投保環節</h2>
            <p>您有 <span id="current-assets-purchase" class="status-item"></span> 初始資產。請選擇您想購買的保險契約卡，為您的生命旅程增添保障。保費會從您的資產中扣除。</p>
            <div class="insurance-list" id="available-insurances">
                </div>
            <div class="options-container">
                <button id="confirm-purchase">確認投保，進入生命羅盤</button>
            </div>
             <p class="message hidden" id="purchase-message"></p>
        </div>

        <!-- 4. 遊戲主畫面 (結合問答與事件) -->
        <div id="game-play" class="hidden">
            <div class="status-bar">
                <div class="status-item">資產: <span id="display-assets">$</span></div>
                <div class="status-item">健康: <span id="display-health"></span>/100</div>
                <div class="status-item">回合: <span id="display-round"></span>/<span id="total-rounds"></span></div>
            </div>
            <div id="map-stage-display"></div> <!-- 新增地圖階段顯示 -->
            <div class="insurance-list" id="owned-insurances">
                <h3>我的保險契約:</h3>
                <p id="no-insurance-yet" style="color: #95a5a6;">目前沒有購買任何保險契約。</p>
            </div>
            <div class="insurance-list" id="clues-collected">
                <h3>守護者線索:</h3>
                <ul id="clues-list"></ul>
                <p id="no-clues-yet" style="color: #95a5a6;">尚未發現任何線索。</p>
            </div>

            <div id="quiz-section" class="quiz-question-container">
                <h2>知識考驗：保險情境題</h2>
                <p>在您的生命旅程中，知識是重要的羅盤。請回答以下保險情境題，正確的選擇將為您帶來額外收穫！</p>
                <h3 id="quiz-question-text"></h3>
                <div class="options-container quiz-options" id="quiz-options-container">
                    </div>
                <p class="message hidden" id="quiz-feedback-message"></p>
                <button class="next-button hidden" id="nextQuizQuestionButton">確認答案</button>
            </div>

            <div id="event-section" class="hidden">
                <h2>【生命羅盤】事件發生！</h2>
                <p id="event-description"></p>
                <p id="outcome-message" class="message hidden"></p>
                <button class="next-button" id="nextEventButton">進入下一回合</button>
            </div>
        </div>

        <!-- 5. 人生轉折點加購保險畫面 (新增人生挑戰模擬器功能) -->
        <div id="turning-point-purchase" class="hidden">
            <h2>人生轉折點：重新規劃保障</h2>
            <p>您已走過人生旅程的初期，現在是檢視您的保障並做出調整的時刻。您當前擁有 <span id="turning-point-assets" class="status-item"></span> 資產。是否需要加購保險，以應對未來的挑戰？</p>
            <div class="insurance-list" id="turning-point-insurances">
                </div>
            <div class="options-container">
                <button id="confirm-turning-point-purchase" disabled>確認加購，繼續旅程</button>
            </div>
             <p class="message hidden" id="turning-point-message"></p>

            <div id="life-challenge-simulator" style="margin-top: 30px; padding: 20px; background-color: rgba(65, 105, 225, 0.2); border-radius: 10px; border: 1px solid #4169E1; box-shadow: 0 0 15px rgba(65, 105, 225, 0.4);">
                <h3>【人生挑戰模擬器】</h3>
                <p>您的人生來到一個十字路口，擺在眼前的是【留學深造】、【自主創業】、【步入婚姻】三條道路，您會選擇哪一個？您的選擇將影響未來的旅程挑戰！</p>
                <div class="options-container">
                    <button id="choose-study" data-challenge="study">選擇：留學深造</button>
                    <button id="choose-business" data-challenge="business">選擇：自主創業</button>
                    <button id="choose-marriage" data-challenge="marriage">選擇：步入婚姻</button>
                </div>
                <p id="challenge-outcome-message" class="message hidden" style="margin-top: 15px;"></p>
            </div>
        </div>


        <!-- 6. 遊戲結束畫面 -->
        <div id="end-game" class="hidden">
            <h2>【人生終章：羅盤歸位】</h2>
            <p id="final-outcome-text"></p>
            <div class="status-bar">
                <div class="status-item">最終資產: <span id="final-assets">$</span></div>
                <div class="status-item">最終健康: <span id="final-health"></span>/100</div>
            </div>
            <p class="message result-message positive" id="beat-percentage-message"></p>
            <div class="leaderboard-data">
                <h3>您的最終成就：</h3>
                <div id="final-risk-judgment">風險判斷力指數: <strong></strong></div>
                <div id="final-protection-completion">保障完成度: <strong></strong></div>
                <div id="final-lucky-escapes">幸運逃脫次數: <strong></strong></div>
                <div id="final-achievement-title">成就稱號: <strong></strong></div>
                <div id="final-zodiac-blessing-summary">您的本命星祝福: <strong></strong></div>
            </div>
            <div id="zodiac-blessing-card">
                <h3>您的專屬【星軌守護祝福卡】</h3>
                <p id="blessing-card-text"></p>
                <!-- 放置所有星座圖片的容器 -->
                <div id="zodiac-blessing-images-container">
                    <img id="aries-image" class="zodiac-image-container hidden" src="" alt="牡羊座圖片">
                    <img id="taurus-image" class="zodiac-image-container hidden" src="" alt="金牛座圖片">
                    <img id="gemini-image" class="zodiac-image-container hidden" src="" alt="雙子座圖片">
                    <img id="cancer-image" class="zodiac-image-container hidden" src="" alt="巨蟹座圖片">
                    <img id="leo-image" class="zodiac-image-container hidden" src="" alt="獅子座圖片">
                    <img id="virgo-image" class="zodiac-image-container hidden" src="" alt="處女座圖片">
                    <img id="libra-image" class="zodiac-image-container hidden" src="" alt="天秤座圖片">
                    <img id="scorpio-image" class="zodiac-image-container hidden" src="" alt="天蠍座圖片">
                    <img id="sagittarius-image" class="zodiac-image-container hidden" src="" alt="射手座圖片">
                    <img id="capricorn-image" class="zodiac-image-container hidden" src="" alt="摩羯座圖片">
                    <img id="aquarius-image" class="zodiac-image-container hidden" src="" alt="水瓶座圖片">
                    <img id="pisces-image" class="zodiac-image-container hidden" src="" alt="雙魚座圖片">
                </div>
            </div>
            <div id="leaderboard-section">
                <h3 style="color: #6EE7B7;">【生命羅盤成就榜】</h3>
                <p style="color: #e2e8f0; font-size: 0.9em;">您的使用者ID: <span id="display-user-id" style="font-weight: bold; color: #f1c40f; word-break: break-all;"></span></p>
                <ul id="leaderboard-list">
                    </ul>
            </div>

            <div class="insurance-list">
                <h3>您擁有的保險契約:</h3>
                <ul id="final-owned-insurances-list"></ul>
            </div>
            <div id="guardian-mystery">
                <h3>守護者之謎 - 最終揭示：</h3>
                <p id="mystery-reveal-text"></p>
            </div>
            <div id="cathay-recommendation" style="margin-top: 30px; padding: 20px; background-color: rgba(44, 62, 80, 0.7); border-radius: 10px; border: 1px solid #34D399;">
                <h3 style="color: #6EE7B7;">國泰人壽 推薦產品：</h3>
                <p style="color: #e2e8f0;" id="recommended-products-text"></p>
                <p style="color: #34D399; font-weight: bold; font-size: 1.1em;">國泰人壽：守護您的現在，成就您的未來。</p>
            </div>
            <button class="social-share-button" id="shareResultButton">分享我的生命羅盤成就</button>
            <p id="copy-message" class="copy-message hidden">成就文字已複製到剪貼簿！</p>
            <button class="start-button" id="restartGameButton">重新啟動羅盤 (再玩一次)</button>
        </div>

        <div id="rebirth-modal" class="rebirth-modal hidden">
            <div class="rebirth-content">
                <h2>【危急時刻：獲得新生！】</h2>
                <p>您的資產或健康已達極限，生命羅盤即將停擺！</p>
                <img src="https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/國泰logo.jpg" alt="Cathay Life Logo" class="cathay-logo">
                <p>國泰人壽在此為您提供一次「時光倒流」的機會，讓您重獲新生，繼續未完的旅程！</p>
                <button class="rebirth-button" id="activateRebirth">獲得新生 / 時光倒流</button>
            </div>
        </div>
    </div>

    <script type="module">
        // Firebase imports
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, collection, addDoc, query, getDocs } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // Global Firebase variables (provided by Canvas environment)
        const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-app-id';
        const firebaseConfig = JSON.parse(typeof __firebase_config !== 'undefined' ? __firebase_config : '{}');
        const initialAuthToken = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;

        let app;
        let db;
        let auth;
        let userId; // To store the authenticated user ID

        async function setupFirebase() {
            if (!app) { // Initialize only once
                app = initializeApp(firebaseConfig);
                db = getFirestore(app);
                auth = getAuth(app);

                // Authenticate user
                try {
                    if (initialAuthToken) {
                        await signInWithCustomToken(auth, initialAuthToken);
                    } else {
                        await signInAnonymously(auth);
                    }
                    userId = auth.currentUser?.uid || crypto.randomUUID(); // Get UID or generate random for anonymous
                    console.log("Firebase initialized. User ID:", userId);
                } catch (error) {
                    console.error("Firebase authentication failed:", error);
                    userId = crypto.randomUUID(); // Fallback to random ID if auth fails
                }
            }
        }

        // --- 遊戲數據 ---
        // 玩家角色設定
        const initialStates = {
            steady_guardian: { id: "steady_guardian", name: "穩健守護者", desc: "重視家庭、安全、長期穩定，是家庭的堅實後盾。", assets: 110000, health: 85 },
            free_explorer: { id: "free_explorer", name: "自由探索家", desc: "熱愛自由、探索、新奇體驗，勇於挑戰未知。", assets: 105000, health: 90 },
            ambitious_pioneer: { id: "ambitious_pioneer", name: "積極開拓者", desc: "追求成就、突破、事業發展，充滿熱情與自信。", assets: 120000, health: 90 },
            wise_planner: { id: "wise_planner", name: "智慧規劃師", desc: "嚴謹、注重細節、有遠見，擅長精確規劃未來。", assets: 130000, health: 80 },
            harmonious_co_creator: { id: "harmonious_co_creator", name: "和諧共創者", desc: "追求人際和諧、合作、平衡，善於溝通與協調。", assets: 100000, health: 88 },
            empathic_connector: { id: "empathic_connector", name: "情感共鳴者", desc: "敏感、富有同情心、追求心靈連結，關懷他人。", assets: 95000, health: 92 }
        };

        // 星座與角色映射 (包含月份日期區間、本命星祝福和圖片 URL)
        const zodiacToRoleMap = {
            "aries": { name: "牡羊座", dates: "3/21-4/19", role: initialStates.ambitious_pioneer, desc: "熱情衝動，勇於冒險，行動力強。", blessing: { name: "勇者之財", type: "asset_per_round", value: 1500, desc: "每回合額外獲得少量資產。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/牡羊座_星座守護卡.jpg" },
            "taurus": { name: "金牛座", dates: "4/20-5/20", role: initialStates.steady_guardian, desc: "務實穩健，重視物質安全與累積。", blessing: { name: "豐饒之體", type: "health_per_round", value: 3, desc: "每回合額外恢復少量健康。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/金牛座_星座守護卡.jpg" },
            "gemini": { name: "雙子座", dates: "5/21-6/20", role: initialStates.harmonious_co_creator, desc: "聰明多變，好奇心強，適應力好。", blessing: { name: "智慧之語", type: "clue_chance", value: 0.2, desc: "更容易發現守護者線索，線索事件機率提升20%。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/雙子座_星座守護卡.jpg" },
            "cancer": { name: "巨蟹座", dates: "6/21-7/22", role: initialStates.steady_guardian, desc: "情感豐富，戀家顧家，重視安全感。", blessing: { name: "家庭之盾", type: "health_per_round", value: 4, desc: "家庭相關風險對健康影響較小，每回合額外恢復健康。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/巨蟹座_星座守護卡.jpg" },
            "leo": { name: "獅子座", dates: "7/23-8/22", role: initialStates.ambitious_pioneer, desc: "自信大方，熱愛生活，樂於展現自我。", blessing: { name: "榮耀之光", type: "asset_per_round", value: 2000, desc: "事業發展更順遂，每回合額外獲得較多資產。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/獅子座_星座守護卡.jpg" },
            "virgo": { name: "處女座", dates: "8/23-9/22", role: initialStates.wise_planner, desc: "細心謹慎，追求完美，善於分析和規劃。", blessing: { name: "分析之眼", type: "quiz_bonus_asset", value: 2000, desc: "答對保險題時獲得更多資產獎勵。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/處女座_星座守護卡.jpg" },
            "libra": { name: "天秤座", dates: "9/23-10/22", role: initialStates.harmonious_co_creator, desc: "追求和諧與平衡，善於溝通。", blessing: { name: "和諧之境", type: "health_per_round", value: 3, desc: "人際關係帶來健康增益，每回合額外恢復健康。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/天秤座_星座守護卡.jpg" },
            "scorpio": { name: "天蠍座", dates: "10/23-11/21", role: initialStates.empathic_connector, desc: "洞察力強，直覺敏銳，重視掌控與深度。", blessing: { name: "深邃之韌", type: "risk_mitigation_percent", value: 0.05, desc: "在風險事件中，損失稍微減輕5%。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/天蠍座_星座守護卡.jpg" },
            "sagittarius": { name: "射手座", dates: "11/22-12/21", role: initialStates.free_explorer, desc: "樂觀開朗，熱愛自由與探索，喜歡旅行。", blessing: { name: "冒險之運", type: "asset_per_round", value: 1800, desc: "探索帶來意外之財，每回合額外獲得少量資產。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/射手座_星座守護卡.jpg" },
            "capricorn": { name: "摩羯座", dates: "12/22-1/19", role: initialStates.wise_planner, desc: "有責任感，務實謹慎，目標明確，擅長長期規劃。", blessing: { name: "堅實之基", type: "protection_score_boost", value: 0.1, desc: "保險保障效果更佳，最終保障完成度分數更高。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/摩羯座_星座守護卡.jpg" },
            "aquarius": { name: "水瓶座", dates: "1/20-2/18", role: initialStates.free_explorer, desc: "獨立創新，思維獨特，重視自由與群體利益。", blessing: { name: "創新之庇", type: "lucky_escape_boost_count", value: 1, desc: "更容易從困境中幸運逃脫一次(最終計分+1)。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/水瓶座_星座守護卡.jpg" },
            "pisces": { name: "雙魚座", dates: "2/19-3/20", role: initialStates.empathic_connector, desc: "敏感浪漫，富有同情心，直覺力強。", blessing: { name: "療癒之泉", type: "health_per_round", value: 5, desc: "心靈平靜帶來健康，每回合額外恢復較多健康。" }, imageUrl: "https://raw.githubusercontent.com/Celinecwf/Life_compass_game/main/images/雙魚座_星座守護卡.jpg" }
        };

        // 可購買的保險種類
        const availableInsurances = [
            { id: "medical", name: "醫療險", cost: 10000, desc: "保障因疾病或意外住院、手術等醫療費用。", type: "health" },
            { id: "accident", name: "意外險", cost: 8000, desc: "保障因意外事故造成的傷害或身故。", type: "accident" },
            { id: "life", name: "壽險", cost: 15000, desc: "保障身故後留給家人的經濟來源。", type: "life" },
            { id: "savings", name: "儲蓄險", cost: 20000, desc: "兼具保障與儲蓄功能，幫助累積財富。", type: "savings" },
            { id: "critical_illness", name: "重大疾病險", cost: 12000, desc: "罹患特定重大疾病時，一次性給付保險金。", type: "health" },
            { id: "travel", name: "旅遊平安險", cost: 5000, desc: "保障旅遊期間可能發生的意外與醫療費用。", type: "travel" },
            { id: "long_term_care", name: "長期照護險", cost: 18000, desc: "因失能需要長期照護時，提供經濟支援。", type: "health" }
        ];

        // 風險事件 (會造成損失，有保險則減輕損失或有補償)
        const riskEvents = [
            {
                name: "突發性大病", desc: "您突然感到身體不適，被診斷出需要長期治療的大病。龐大的醫療費用和收入中斷讓您備感壓力...",
                trigger: ["medical", "critical_illness"], // 醫療險 或 重大疾病險
                no_insurance: { assets: -80000, health: -30, msg: "您沒有相關保險！積蓄快速耗盡，健康狀況急速惡化。" },
                with_insurance: { assets: +50000, health: +10, msg: "慶幸您有醫療險/重大疾病險！保險理賠金大幅減輕您的負擔，讓您能專心養病。", class: "positive" },
                tags: ["health", "family"]
            },
            {
                name: "嚴重意外事故", desc: "一場突如其來的嚴重事故導致您受傷，需要住院與復健。這筆開銷與收入中斷是個沉重打擊...",
                trigger: ["accident", "medical"], // 意外險 或 醫療險
                no_insurance: { assets: -60000, health: -25, msg: "您沒有意外險！醫療費與休養期間的收入損失讓您陷入困境。" },
                with_insurance: { assets: +40000, health: +15, msg: "幸好您有意外險/醫療險！保險金即時給付，助您渡過難關，專心康復。", class: "positive" },
                tags: ["accident", "career"]
            },
            {
                name: "投資失利", desc: "您投入大筆資金的投資案不幸失敗，資金遭到凍結，面臨嚴重的財務危機。",
                trigger: ["savings"], // 儲蓄險 (作為備用金/資產保護)
                no_insurance: { assets: -70000, health: -10, msg: "您的投資全數虧損，財務拉警報，心情也受到影響。" },
                with_insurance: { assets: +20000, health: +5, msg: "雖然投資失利，但您有儲蓄險的保單價值，為您提供了緩衝資金，減輕部分壓力。", class: "positive" },
                tags: ["finance", "career"]
            },
            {
                name: "海外突發狀況", desc: "您在海外旅行時遭遇緊急醫療狀況，或行李遺失、行程取消等，面臨高額海外費用。",
                trigger: ["travel"], // 旅遊平安險
                no_insurance: { assets: -30000, health: -15, msg: "海外狀況讓您措手不及！高額費用和不便讓您的旅程變成噩夢。" },
                with_insurance: { assets: +15000, health: +5, msg: "幸好您有旅遊平安險！保險公司承擔了大部分費用，讓您在異地也能安心應對。", class: "positive" },
                tags: ["travel", "health"]
            },
            {
                name: "家庭經濟支柱驟逝", desc: "家庭經濟支柱突然身故，家庭收入中斷，子女教育和生活面臨巨大挑戰。",
                trigger: ["life"], // 壽險
                no_insurance: { assets: -100000, health: -20, msg: "家庭失去經濟支柱，未來的生活、子女的教育金面臨巨大缺口，讓家人陷入困境。" },
                with_insurance: { assets: +80000, health: +10, msg: "您生前有壽險保障！保險金的給付為家人提供了應急資金和未來的保障，讓他們能繼續前行。", class: "positive" },
                tags: ["family", "life"]
            },
            {
                name: "全球經濟衰退", desc: "一場全球性的經濟衰退來襲，您的產業受到嚴重衝擊，收入銳減，甚至面臨失業風險。",
                trigger: ["savings"], // 儲蓄險 (作為抗風險的穩定資產)
                no_insurance: { assets: -50000, health: -10, msg: "經濟寒冬讓您的財務雪上加霜，生活陷入困境。" },
                with_insurance: { assets: +10000, health: 0, msg: "幸好您有儲蓄險，這筆穩健的資產在此時提供了部分現金流，幫助您度過難關。", class: "positive" },
                tags: ["finance", "career"]
            },
            {
                name: "晚年失能", desc: "您在晚年因意外或疾病導致身體失能，需要長期專業照護。這筆龐大的照護費用和人力需求，對您的家庭造成了沉重負擔...",
                trigger: ["long_term_care"], // 長期照護險
                no_insurance: { assets: -120000, health: -35, msg: "您沒有長期照護險！高昂的照護費用迅速耗盡積蓄，生活品質嚴重下降，甚至影響家人。" },
                with_insurance: { assets: +60000, health: +10, msg: "幸好您有長期照護險！保險公司每月給付照護金，讓您能安心聘請專業看護，維持晚年生活品質。", class: "positive" },
                tags: ["health", "family"]
            },
            {
                name: "學業/進修壓力", desc: "您選擇深造後，學業壓力劇增，導致健康下降，同時也需要額外資金支持學費和生活費。",
                trigger: ["savings", "medical"], // 儲蓄險 (備用金) 或 醫療險 (健康問題)
                no_insurance: { assets: -40000, health: -20, msg: "龐大的學費和生活開銷讓您捉襟見肘，健康也亮起紅燈。" },
                with_insurance: { assets: +15000, health: +5, msg: "幸好有儲蓄險支持學業，醫療險則為健康問題提供了保障，壓力大減。", class: "positive" },
                tags: ["study", "finance", "health"],
                only_if_challenge: "study" // 只有在選擇「留學深造」後才會增加機率
            },
            {
                name: "創業初期資金斷裂", desc: "您的創業專案在初期面臨資金鏈斷裂，需要緊急注入資金才能繼續營運。",
                trigger: ["savings"], // 儲蓄險 (應急資金)
                no_insurance: { assets: -90000, health: -25, msg: "創業夢想戛然而止，資金耗盡讓您陷入絕境。" },
                with_insurance: { assets: +30000, health: +10, msg: "幸好有儲蓄險這筆應急資金！它幫助您度過難關，讓創業之路得以延續。", class: "positive" },
                tags: ["business", "finance"],
                only_if_challenge: "business"
            },
            {
                name: "家庭緊急開銷", desc: "新婚後，家庭突發緊急事件（例如新居裝修費用、親人意外醫療），需要一筆意外的支出。",
                trigger: ["savings", "medical"], // 儲蓄險 (應急金) 或 醫療險
                no_insurance: { assets: -50000, health: -15, msg: "突如其來的家庭開銷讓您手忙腳亂，影響了新婚生活。" },
                with_insurance: { assets: +20000, health: +5, msg: "有了儲蓄險或醫療險，這些意外支出得到有效緩解，讓您能更從容應對。", class: "positive" },
                tags: ["marriage", "finance", "family"],
                only_if_challenge: "marriage"
            }
        ];

        // 線索事件 (不會造成損失，但會提供線索)
        const clueEvents = [
            { name: "偶遇智者", desc: "您在旅途中偶遇一位智者，他分享了關於「未雨綢繆」的古老智慧。", clue: "線索一：真正的力量，在於預見與準備。", type: "clue" },
            { name: "讀到古籍", desc: "您在舊書店發現一本塵封的古籍，其中記載了關於「分擔風險」的故事。", clue: "線索二：個體的脆弱，可由群體的力量彌補。", type: "clue" },
            { name: "夢境啟示", desc: "一個奇特的夢境讓您思考，人生中的「無形之手」究竟如何運作。", clue: "線索三：最堅固的盾牌，往往無形無影。", type: "clue" },
            { name: "觀察自然", desc: "您觀察到大自然中生物如何適應環境，並從中領悟到「適應與韌性」的重要性。", clue: "線索四：生命的韌性，來自於對變化的擁抱。", type: "clue" },
            { name: "聆聽故事", desc: "您聽到一個關於某人因提前規劃而成功渡過難關的故事，深受啟發。", clue: "線索五：過去的智慧，指引未來的方向。", type: "clue" }
        ];

        // 生活事件 (可能帶來小幅資產或健康增益)
        const lifeEvents = [
            { name: "獲得加薪", desc: "您的努力獲得認可，公司為您加薪了！", assets: +15000, health: +5 },
            { name: "學習新技能", desc: "您投入時間學習了新技能，這讓您感到充實和自信。", assets: 0, health: +10 },
            { name: "結交新朋友", desc: "您認識了新朋友，拓展了人際圈，感到心情愉悅。", assets: 0, health: +5 },
            { name: "小額中獎", desc: "您購買的彩票意外中得了小獎！", assets: +5000, health: 0 },
            { name: "健康生活習慣", desc: "您堅持運動和健康飲食，身體狀況良好。", assets: 0, health: +8 },
            { name: "找到打工機會", desc: "留學期間找到一份兼職，減輕了部分經濟壓力。", assets: +8000, health: +2, only_if_challenge: "study" },
            { name: "產品獲得好評", desc: "您創業的產品獲得市場初步好評，帶來了第一筆收入。", assets: +10000, health: +5, only_if_challenge: "business" },
            { name: "伴侶送出驚喜", desc: "您的伴侶為您準備了小驚喜，讓您心情大好，幸福感滿滿。", assets: 0, health: +5, only_if_challenge: "marriage" }
        ];

        // 10 題保險情境選擇題 (已縮短至10題)
        const quizQuestions = [
            {
                id: "q1", question: "您剛步入職場，手頭預算有限，但想為自己規劃一份基礎保障。您會優先考慮哪種保險？",
                options: [
                    { text: "A. 高額儲蓄險，追求長期回報", correct: false },
                    { text: "B. 醫療險，保障突發疾病或意外住院", correct: true, clue: "線索六：基礎保障，是人生基石。" },
                    { text: "C. 投資型保單，積極累積財富", correct: false },
                    { text: "D. 長期照護險，為遙遠的未來做準備", correct: false }
                ]
            },
            {
                id: "q2", question: "您是家庭的經濟支柱，上有老下有小。若您不幸發生意外，最擔心的是什麼？您會選擇哪種保險來轉嫁這份風險？",
                options: [
                    { text: "A. 旅遊平安險，保障出遊安全", correct: false },
                    { text: "B. 壽險，確保家人在您身故後仍有經濟來源", correct: true, clue: "線索七：愛與責任，由壽險延續。" },
                    { text: "C. 儲蓄險，為自己存退休金", correct: false },
                    { text: "D. 寵物險，保障毛小孩健康", correct: false }
                ]
            },
            {
                id: "q3", question: "您熱愛戶外運動，經常登山、潛水。為了應對可能發生的運動傷害，您會考慮哪種保險？",
                options: [
                    { text: "A. 汽車強制險，保障行車安全", correct: false },
                    { text: "B. 醫療險，保障因意外就醫的費用", correct: false },
                    { text: "C. 意外險，專門保障因意外造成的傷害或身故", correct: true, clue: "線索八：無懼挑戰，意外有備。" },
                    { text: "D. 房屋火險，保障居家安全", correct: false }
                ]
            },
            {
                id: "q4", question: "您即將前往歐洲自助旅行一個月。除了當地的醫療費用，您還擔心行李遺失或行程取消。哪種保險能提供最全面的保障？",
                options: [
                    { text: "A. 國內旅遊險，保障台灣境內旅遊", correct: false },
                    { text: "B. 醫療險，僅保障海外醫療費用", correct: false },
                    { text: "C. 旅遊平安險，涵蓋海外醫療、意外、行李遺失、行程延誤等", correct: true, clue: "線索九：世界再大，守護不變。" },
                    { text: "D. 壽險，保障身故後家人經濟", correct: false }
                ]
            },
            {
                id: "q5", question: "您開始思考退休生活，希望未來能有穩定的收入來源，不依賴子女。哪種保險產品最符合您的需求？",
                options: [
                    { text: "A. 意外險，保障退休後的意外", correct: false },
                    { text: "B. 醫療險，保障退休後的醫療費用", correct: false },
                    { text: "C. 年金險，提供退休後定期給付的收入", correct: true, clue: "線索十：晚年尊嚴，規劃先行。" },
                    { text: "D. 儲蓄險，短期儲蓄目標", correct: false }
                ]
            },
            { // 第6題 (索引5)
                id: "q6", question: "您被診斷出罹患了需要長期且高額治療的重大疾病，例如癌症。哪種保險能提供一次性的大筆理賠金，讓您能專心治療？",
                options: [
                    { text: "A. 醫療險，按實際醫療費用給付", correct: false },
                    { text: "B. 意外險，保障意外傷害", correct: false },
                    { text: "C. 重大疾病險，確診即給付一筆保險金", correct: true, clue: "線索十一：生命重擊，財務無憂。" },
                    { text: "D. 壽險，身故才給付", correct: false }
                ]
            },
            { // 第7題 (索引6)
                id: "q7", question: "您的孩子剛出生，您希望為他準備一筆未來讀大學的教育基金，同時也希望在他成長過程中獲得保障。哪種保險產品能兼顧這兩點？",
                options: [
                    { text: "A. 純壽險，只保障身故", correct: false },
                    { text: "B. 意外險，只保障意外傷害", correct: false },
                    { text: "C. 儲蓄型壽險或教育基金險，兼具保障與儲蓄功能", correct: true, clue: "線索十二：育兒之路，保障伴隨。" },
                    { text: "D. 旅遊平安險，保障旅遊安全", correct: false }
                ]
            },
            { // 第8題 (索引7)
                id: "q8", question: "您發現自己開始出現失能的風險，擔心未來生活無法自理，需要長期照護。哪種保險能提供這方面的經濟支援？",
                options: [
                    { text: "A. 醫療險，保障住院醫療費用", correct: false },
                    { text: "B. 意外險，保障意外傷害", correct: false },
                    { text: "C. 長期照護險，提供長期照護費用補貼", correct: true, clue: "線索十三：老有所依，尊嚴不減。" },
                    { text: "D. 儲蓄險，累積財富", correct: false }
                ]
            },
            { // 第9題 (索引8)
                id: "q9", question: "您是一位自由工作者，收入不穩定。您希望在收入中斷或突發狀況時，能有一筆應急資金。哪種保險或理財工具最適合您的需求？",
                options: [
                    { text: "A. 高風險股票投資，追求高報酬", correct: false },
                    { text: "B. 儲蓄險，兼具保障與穩健資產累積", correct: true, clue: "線索十四：財務彈性，應變自如。" },
                    { text: "C. 豪華汽車保險，保障車輛安全", correct: false },
                    { text: "D. 海外醫療險，保障海外就醫", correct: false }
                ]
            },
            { // 第10題 (索引9)
                id: "q10", question: "您居住的地區近年來地震頻繁，您擔心房屋受損。除了政府的災害補助，您還能透過什麼方式來轉嫁房屋的潛在損失？",
                options: [
                    { text: "A. 購買更多黃金，作為實物資產", correct: false },
                    { text: "B. 房屋火險，保障火災損失", correct: false },
                    { text: "C. 住宅地震保險，專門保障地震造成的房屋損失", correct: true, clue: "線索十五：家園安穩，風險可控。" },
                    { text: "D. 人壽保險，保障生命安全", correct: false }
                ]
            }
        ];

        // 遊戲階段定義 (尋寶圖概念)
        const gameStages = [
            { id: "stage1", name: "【啟程之徑】", description: "人生伊始，您將探索基礎知識與潛在風險。", quizCount: 3 }, // 3個問答 (q1, q2, q3)
            { id: "stage2", name: "【成長之林】", description: "步入社會，您將面對更多元的挑戰與機遇。", quizCount: 2 }, // 2個問答 (q4, q5)
            // 人生轉折點會在此階段結束後觸發，不作為獨立的 quizCount 階段
            { id: "stage3", name: "【挑戰之峰】", description: "人生下半場，您將在所選道路上迎接更艱鉅的考驗。", quizCount: 3 }, // 3個問答 (q6, q7, q8)
            { id: "stage4", name: "【歸途之海】", description: "旅程尾聲，回顧與總結您的生命羅盤。", quizCount: 2 }  // 2個問答 (q9, q10)
        ];


        // 所有遊戲事件的集合，用於隨機抽取 (不包含 quizQuestions)
        let allGameEvents = []; // 將在 initializeGame 中填充
        let playerChallenge = null; // 記錄玩家選擇的人生挑戰

        // --- 遊戲狀態變數 ---
        let player = {
            zodiac: null, // 儲存星座名稱 (例如 "牡羊座")
            zodiacId: null, // 儲存星座 ID (例如 "aries")
            role: null, // 將儲存 initialStates 中的角色物件
            assets: 0,
            health: 0,
            ownedInsurances: new Set(), // 使用Set來存儲已購買的保險ID
            cluesCollected: new Set(), // 使用Set來存儲已收集的線索
            rebirthUsed: false, // 標記是否已使用過「獲得新生」功能
            luckyEscapesCount: 0, // 新增：幸運逃脫次數
            riskJudgmentScore: 0, // 新增：風險判斷力分數 (答對題數)
            protectionCompletionScore: 0, // 新增：保障完成度分數 (擁有保險數)
            zodiacBlessing: null // 新增：儲存玩家的本命星祝福
        };

        let currentStageIndex = 0; // 當前遊戲階段的索引
        let currentQuizQuestionIndex = 0; // 當前問答題的索引 (0-indexed)
        let quizzesCompletedInCurrentStage = 0; // 當前階段已完成的問答數

        let currentRound = 1; // 總回合數 (用於顯示進度)
        let totalRoundsCalculated = 0; // 總回合數 (所有問答題數)

        let justAnsweredQuiz = false; // 標記是否剛回答完問題，接下來應該觸發事件
        let justFinishedTurningPoint = false; // 標記是否剛結束人生轉折點，接下來應該觸發事件

        // --- DOM 元素獲取 ---
        const gameContainer = document.getElementById('game-container');
        const startScreen = document.getElementById('start-screen');
        const characterSelection = document.getElementById('character-selection');
        const insurancePurchase = document.getElementById('insurance-purchase');
        const gamePlay = document.getElementById('game-play'); // 主要遊戲畫面，包含問答和事件區塊
        const turningPointPurchase = document.getElementById('turning-point-purchase'); // 人生轉折點環節
        const endGameScreen = document.getElementById('end-game');

        const startButton = document.getElementById('startButton');
        const zodiacButtonsContainer = document.getElementById('zodiac-buttons-container');
        const roleDescription = document.getElementById('role-description');
        const zodiacBlessingDescription = document.getElementById('zodiac-blessing-description'); // 新增祝福描述元素
        const availableInsurancesDiv = document.getElementById('available-insurances');
        const currentAssetsPurchaseSpan = document.getElementById('current-assets-purchase');
        const confirmPurchaseButton = document.getElementById('confirm-purchase');
        const purchaseMessage = document.getElementById('purchase-message');

        // 遊戲主畫面中的狀態顯示
        const displayAssets = document.getElementById('display-assets');
        const displayHealth = document.getElementById('display-health');
        const displayRound = document.getElementById('display-round');
        const totalRoundsSpan = document.getElementById('total-rounds'); // 顯示總回合數
        const mapStageDisplay = document.getElementById('map-stage-display'); // 地圖階段顯示
        const ownedInsurancesListDiv = document.getElementById('owned-insurances');
        const noInsuranceYet = document.getElementById('no-insurance-yet');
        const cluesCollectedDiv = document.getElementById('clues-collected');
        const cluesList = document.getElementById('clues-list');
        const noCluesYet = document.getElementById('no-clues-yet');

        // 知識考驗區塊的元素
        const quizSection = document.getElementById('quiz-section');
        const quizQuestionText = document.getElementById('quiz-question-text');
        const quizOptionsContainer = document.getElementById('quiz-options-container');
        const quizFeedbackMessage = document.getElementById('quiz-feedback-message');
        const nextQuizQuestionButton = document.getElementById('nextQuizQuestionButton');

        // 生命羅盤事件區塊的元素
        const eventSection = document.getElementById('event-section');
        const eventDescription = document.getElementById('event-description');
        const outcomeMessage = document.getElementById('outcome-message');
        const nextEventButton = document.getElementById('nextEventButton');

        // 人生轉折點的元素
        const turningPointAssetsSpan = document.getElementById('turning-point-assets');
        const turningPointInsurancesDiv = document.getElementById('turning-point-insurances');
        const confirmTurningPointPurchaseButton = document.getElementById('confirm-turning-point-purchase');
        const turningPointMessage = document.getElementById('turning-point-message');
        const lifeChallengeSimulator = document.getElementById('life-challenge-simulator');
        const chooseStudyButton = document.getElementById('choose-study');
        const chooseBusinessButton = document.getElementById('choose-business');
        const chooseMarriageButton = document.getElementById('choose-marriage'); // 修正此行錯誤
        const challengeOutcomeMessage = document.getElementById('challenge-outcome-message');


        // 遊戲結束畫面的元素
        const finalOutcomeText = document.getElementById('final-outcome-text');
        const finalAssets = document.getElementById('final-assets');
        const finalHealth = document.getElementById('final-health');
        const beatPercentageMessage = document.getElementById('beat-percentage-message');
        const finalOwnedInsurancesList = document.getElementById('final-owned-insurances-list');
        const guardianMysteryDiv = document.getElementById('guardian-mystery');
        const mysteryRevealText = document.getElementById('mystery-reveal-text');
        const recommendedProductsText = document.getElementById('recommended-products-text');
        const restartGameButton = document.getElementById('restartGameButton');

        // 新增排行榜相關元素
        const finalRiskJudgment = document.getElementById('final-risk-judgment');
        const finalProtectionCompletion = document.getElementById('final-protection-completion');
        const finalLuckyEscapes = document.getElementById('final-lucky-escapes');
        const finalAchievementTitle = document.getElementById('final-achievement-title');
        const finalZodiacBlessingSummary = document.getElementById('final-zodiac-blessing-summary');
        const shareResultButton = document.getElementById('shareResultButton');
        const copyMessage = document.getElementById('copy-message');

        // 星座幸運祝福卡元素
        const blessingCardText = document.getElementById('blessing-card-text');
        // const capricornBlessingImage = document.getElementById('capricorn-blessing-image'); // 這個已不再需要，由通用邏輯取代
        const zodiacBlessingImagesContainer = document.getElementById('zodiac-blessing-images-container'); // 所有星座圖片的容器


        // 排行榜元素
        const leaderboardSection = document.getElementById('leaderboard-section');
        const leaderboardList = document.getElementById('leaderboard-list');
        const displayUserId = document.getElementById('display-user-id');


        // 獲得新生彈窗的元素
        const rebirthModal = document.getElementById('rebirth-modal');
        const activateRebirthButton = document.getElementById('activateRebirth');

        // --- 遊戲流程控制 ---

        // 顯示指定畫面
        function showScreen(screenId) {
            startScreen.classList.add('hidden');
            characterSelection.classList.add('hidden');
            insurancePurchase.classList.add('hidden');
            gamePlay.classList.add('hidden'); // 主要遊戲畫面
            turningPointPurchase.classList.add('hidden'); // 人生轉折點
            endGameScreen.classList.add('hidden');
            rebirthModal.classList.remove('show'); // 確保彈窗關閉
            document.getElementById(screenId).classList.remove('hidden');
        }

        // 初始化遊戲
        function initializeGame() {
            player = {
                zodiac: null,
                zodiacId: null, // 重置
                role: null,
                assets: 0,
                health: 0,
                ownedInsurances: new Set(), // 使用Set來存儲已購買的保險ID
                cluesCollected: new Set(), // 使用Set來存儲已收集的線索
                rebirthUsed: false, // 標記是否已使用過「獲得新生」功能
                luckyEscapesCount: 0, // 重置
                riskJudgmentScore: 0, // 重置
                protectionCompletionScore: 0, // 重置
                zodiacBlessing: null // 重置
            };
            currentStageIndex = 0; // 從第一階段開始
            currentQuizQuestionIndex = 0; // 從第0題開始
            quizzesCompletedInCurrentStage = 0;
            currentRound = 1; // 總回合數從1開始
            
            // 計算總回合數 (所有問答題的總和)
            totalRoundsCalculated = quizQuestions.length;

            justAnsweredQuiz = false;
            justFinishedTurningPoint = false;
            playerChallenge = null; // 重置人生挑戰選擇
            totalRoundsSpan.textContent = totalRoundsCalculated; // 顯示總回合數
            updateDisplay();
            showScreen('start-screen');
        }

        // 更新狀態顯示
        function updateDisplay() {
            displayAssets.textContent = `$${player.assets.toLocaleString()}`;
            displayHealth.textContent = player.health;
            displayRound.textContent = currentRound; // 顯示當前回合數

            // 更新地圖階段顯示
            const currentStage = gameStages[currentStageIndex];
            if (currentStage) {
                mapStageDisplay.textContent = `當前階段: ${currentStage.name} - ${currentStage.description}`;
            } else {
                mapStageDisplay.textContent = `遊戲結束`;
            }

            // 更新已擁有的保險列表
            ownedInsurancesListDiv.innerHTML = '<h3>我的保險契約:</h3>';
            if (player.ownedInsurances.size === 0) {
                ownedInsurancesListDiv.appendChild(noInsuranceYet);
                noInsuranceYet.classList.remove('hidden');
            } else {
                noInsuranceYet.classList.add('hidden');
                const ul = document.createElement('ul');
                player.ownedInsurances.forEach(id => {
                    const insurance = availableInsurances.find(ins => ins.id === id);
                    if (insurance) {
                        const li = document.createElement('li');
                        li.className = 'insurance-item';
                        li.textContent = insurance.name;
                        ul.appendChild(li);
                    }
                });
                ownedInsurancesListDiv.appendChild(ul);
            }

            // 更新收集到的線索列表
            cluesList.innerHTML = ''; // 清空
            if (player.cluesCollected.size === 0) {
                cluesCollectedDiv.appendChild(noCluesYet);
                noCluesYet.classList.remove('hidden');
            } else {
                noCluesYet.classList.add('hidden');
                player.cluesCollected.forEach(clueText => {
                    const li = document.createElement('li');
                    li.className = 'insurance-item'; // 沿用樣式
                    li.textContent = clueText;
                    cluesList.appendChild(li);
                });
            }
        }

        // 渲染星座選擇按鈕
        function renderZodiacSelection() {
            zodiacButtonsContainer.innerHTML = '';
            for (const zodiacId in zodiacToRoleMap) {
                const zodiac = zodiacToRoleMap[zodiacId];
                const button = document.createElement('button');
                button.dataset.zodiac = zodiacId;
                button.innerHTML = `【${zodiac.name}】<br><small>(${zodiac.dates})</small>`; // 加入日期區間
                button.classList.add('zodiac-button'); // 添加一個 class 以便統一管理
                zodiacButtonsContainer.appendChild(button);
            }

            // 為星座按鈕添加事件監聽器
            document.querySelectorAll('.zodiac-button').forEach(button => {
                button.addEventListener('click', (event) => {
                    const zodiacId = event.target.dataset.zodiac || event.target.closest('button').dataset.zodiac; // 確保點擊到文字也能獲取
                    const zodiacInfo = zodiacToRoleMap[zodiacId];

                    player.zodiac = zodiacInfo.name; // 儲存星座名稱 (例如 "牡羊座")
                    player.zodiacId = zodiacId; // 儲存星座 ID (例如 "aries")
                    player.role = zodiacInfo.role; // 設定玩家角色物件
                    player.assets = player.role.assets;
                    player.health = player.role.health;
                    player.zodiacBlessing = zodiacInfo.blessing; // 儲存本命星祝福

                    roleDescription.innerHTML = `您選擇了【<span class="final-highlight">${player.zodiac}</span>】。您的生命特質是：「${zodiacInfo.desc}」。這將決定您在遊戲中扮演【<span class="final-highlight">${player.role.name}</span>】的角色。`;
                    zodiacBlessingDescription.innerHTML = `您的本命星祝福是：【${player.zodiacBlessing.name}】 - ${player.zodiacBlessing.desc}`;

                    // 過渡到下一個畫面
                    setTimeout(() => {
                        showScreen('insurance-purchase');
                        renderInsuranceOptions();
                    }, 1500); // 稍微延長顯示時間讓玩家閱讀
                });
            });
        }


        // 渲染保險購買選項
        function renderInsuranceOptions() {
            currentAssetsPurchaseSpan.textContent = `$${player.assets.toLocaleString()}`;
            availableInsurancesDiv.innerHTML = ''; // 清空舊選項

            availableInsurances.forEach(insurance => {
                const div = document.createElement('div');
                div.className = 'insurance-item';
                div.innerHTML = `
                    <strong>${insurance.name}</strong> - 費用: <span style="color:#f1c40f;">$${insurance.cost.toLocaleString()}</span><br>
                    <small style="color:#bdc3c7;">${insurance.desc}</small>
                    <button class="buy-insurance-btn" data-id="${insurance.id}" data-cost="${insurance.cost}" ${player.assets < insurance.cost ? 'disabled' : ''}>購買</button>
                `;
                availableInsurancesDiv.appendChild(div);
            });

            // 為購買按鈕添加事件監聽器
            document.querySelectorAll('.buy-insurance-btn').forEach(button => {
                button.addEventListener('click', (event) => {
                    const id = event.target.dataset.id;
                    const cost = parseInt(event.target.dataset.cost);

                    if (player.assets >= cost && !player.ownedInsurances.has(id)) {
                        player.assets -= cost;
                        player.ownedInsurances.add(id);
                        purchaseMessage.textContent = `成功購買 ${availableInsurances.find(i => i.id === id).name}！資產剩餘 $${player.assets.toLocaleString()}。`;
                        purchaseMessage.classList.remove('hidden', 'negative');
                        purchaseMessage.classList.add('positive'); // 購買成功是積極訊息
                        event.target.disabled = true; // 購買後禁用按鈕
                        currentAssetsPurchaseSpan.textContent = `$${player.assets.toLocaleString()}`; // 更新資產顯示
                        // 重新檢查其他保險是否可購買
                        document.querySelectorAll('.buy-insurance-btn').forEach(btn => {
                            if (player.assets < parseInt(btn.dataset.cost)) {
                                btn.disabled = true;
                            }
                        });
                    } else {
                        purchaseMessage.textContent = "資產不足或已購買此保險契約！";
                        purchaseMessage.classList.remove('hidden', 'positive');
                        purchaseMessage.classList.add('negative');
                    }
                    setTimeout(() => purchaseMessage.classList.add('hidden'), 2000); // 訊息顯示2秒後消失
                });
            });
        }

        // 確認投保，進入遊戲主循環 (開始問答與事件交錯)
        confirmPurchaseButton.addEventListener('click', () => {
            showScreen('game-play'); // 顯示遊戲主畫面
            updateDisplay();
            startNextStage(); // 開始第一個回合 (問答)
        });

        // 渲染測驗問題
        function renderQuizQuestion() {
            const questionData = quizQuestions[currentQuizQuestionIndex];
            quizQuestionText.textContent = `Q${currentQuizQuestionIndex + 1}. ${questionData.question}`;
            quizOptionsContainer.innerHTML = ''; // 清空舊選項
            quizFeedbackMessage.classList.add('hidden');
            nextQuizQuestionButton.classList.add('hidden'); // 隱藏「確認答案」按鈕

            questionData.options.forEach((option, index) => {
                const button = document.createElement('button');
                button.textContent = option.text;
                button.dataset.index = index;
                button.classList.add('quiz-option-button');
                quizOptionsContainer.appendChild(button);

                button.addEventListener('click', (event) => {
                    // 禁用所有選項，防止重複點擊
                    document.querySelectorAll('.quiz-option-button').forEach(btn => btn.disabled = true);

                    const selectedIndex = parseInt(event.target.dataset.index);
                    const selectedOption = questionData.options[selectedIndex];

                    if (selectedOption.correct) {
                        quizFeedbackMessage.textContent = "恭喜您，回答正確！您獲得了額外資產和健康點數，並發現一條線索！";
                        quizFeedbackMessage.classList.remove('negative');
                        quizFeedbackMessage.classList.add('positive');
                        player.assets += 5000;
                        // 應用處女座祝福：答對保險題時獲得更多資產獎勵
                        if (player.zodiacBlessing && player.zodiacBlessing.type === "quiz_bonus_asset") {
                            player.assets += player.zodiacBlessing.value;
                            quizFeedbackMessage.textContent += ` (您的【${player.zodiacBlessing.name}】額外獲得 $${player.zodiacBlessing.value.toLocaleString()})。`;
                        }
                        player.health = Math.min(100, player.health + 5);
                        if (selectedOption.clue) {
                            player.cluesCollected.add(selectedOption.clue);
                        }
                        player.riskJudgmentScore++; // 答對題數加1
                    } else {
                        quizFeedbackMessage.textContent = "很可惜，回答錯誤。請繼續努力學習保險知識！";
                        quizFeedbackMessage.classList.remove('positive');
                        quizFeedbackMessage.classList.add('negative');
                    }
                    quizFeedbackMessage.classList.remove('hidden');
                    nextQuizQuestionButton.classList.remove('hidden'); // 顯示「確認答案」按鈕

                    // 標示正確答案
                    document.querySelectorAll('.quiz-option-button').forEach((btn, idx) => {
                        if (questionData.options[idx].correct) {
                            btn.classList.add('correct');
                        } else if (idx === selectedIndex) {
                            btn.classList.add('incorrect');
                        }
                    });

                    updateDisplay(); // 更新狀態顯示
                    justAnsweredQuiz = true; // 標記已回答問題，下一步應觸發事件
                });
            });
        }

        // 「確認答案」按鈕的點擊事件 (用於從問答跳轉到事件或轉折點)
        nextQuizQuestionButton.addEventListener('click', () => {
            quizFeedbackMessage.classList.add('hidden');
            nextQuizQuestionButton.classList.add('hidden');
            // Re-enable quiz option buttons for next quiz (if any)
            document.querySelectorAll('.quiz-option-button').forEach(btn => {
                btn.disabled = false;
                btn.classList.remove('correct', 'incorrect');
            });

            // 人生轉折點在第5題和第6題之間 (索引4之後)
            if (currentQuizQuestionIndex === 4) { // 如果是第5題 (索引4)
                showScreen('turning-point-purchase');
                renderTurningPointPurchaseOptions();
                lifeChallengeSimulator.classList.remove('hidden'); // 顯示人生挑戰模擬器
                // 啟用挑戰按鈕
                chooseStudyButton.disabled = false;
                chooseBusinessButton.disabled = false;
                chooseMarriageButton.disabled = false;
                challengeOutcomeMessage.classList.add('hidden'); // 隱藏結果訊息
                confirmTurningPointPurchaseButton.disabled = true; // 預設禁用加購確認按鈕
                // 這裡不遞增 currentQuizQuestionIndex 或呼叫 startNextStage，遊戲流程暫停
            } else {
                justAnsweredQuiz = true; // 標記已回答問題，下一步應觸發事件
                currentQuizQuestionIndex++; // 遞增到下一題的索引
                startNextStage(); // 繼續遊戲流程 (觸發事件)
            }
        });

        // 渲染人生轉折點加購保險選項
        function renderTurningPointPurchaseOptions() {
            turningPointAssetsSpan.textContent = `$${player.assets.toLocaleString()}`;
            turningPointInsurancesDiv.innerHTML = ''; // 清空舊選項

            availableInsurances.forEach(insurance => {
                const div = document.createElement('div');
                div.className = 'insurance-item';
                div.innerHTML = `
                    <strong>${insurance.name}</strong> - 費用: <span style="color:#f1c40f;">$${insurance.cost.toLocaleString()}</span><br>
                    <small style="color:#bdc3c7;">${insurance.desc}</small>
                    <button class="buy-turning-point-btn" data-id="${insurance.id}" data-cost="${insurance.cost}" ${player.assets < insurance.cost || player.ownedInsurances.has(insurance.id) ? 'disabled' : ''}>加購</button>
                `;
                turningPointInsurancesDiv.appendChild(div);
            });

            // 為加購按鈕添加事件監聽器
            document.querySelectorAll('.buy-turning-point-btn').forEach(button => {
                button.addEventListener('click', (event) => {
                    const id = event.target.dataset.id;
                    const cost = parseInt(event.target.dataset.cost);

                    if (player.assets >= cost && !player.ownedInsurances.has(id)) {
                        player.assets -= cost;
                        player.ownedInsurances.add(id);
                        turningPointMessage.textContent = `成功加購 ${availableInsurances.find(i => i.id === id).name}！資產剩餘 $${player.assets.toLocaleString()}。`;
                        turningPointMessage.classList.remove('hidden', 'negative');
                        turningPointMessage.classList.add('positive');
                        event.target.disabled = true;
                        turningPointAssetsSpan.textContent = `$${player.assets.toLocaleString()}`;
                        // 重新檢查其他保險是否可購買
                        document.querySelectorAll('.buy-turning-point-btn').forEach(btn => {
                            if (player.assets < parseInt(btn.dataset.cost)) {
                                btn.disabled = true;
                            }
                        });
                    } else {
                        turningPointMessage.textContent = "資產不足或已擁有此保險契約！";
                        turningPointMessage.classList.remove('hidden', 'positive');
                        turningPointMessage.classList.add('negative');
                    }
                    setTimeout(() => turningPointMessage.classList.add('hidden'), 2000);
                });
            });
        }

        // 人生挑戰選擇事件
        [chooseStudyButton, chooseBusinessButton, chooseMarriageButton].forEach(button => {
            button.addEventListener('click', (event) => {
                playerChallenge = event.target.dataset.challenge; // 儲存玩家選擇的挑戰
                let message = "";
                // 禁用所有挑戰按鈕
                chooseStudyButton.disabled = true;
                chooseBusinessButton.disabled = true;
                chooseMarriageButton.disabled = true;

                switch (playerChallenge) {
                    case "study":
                        message = "您選擇了【留學深造】！這將為您的知識和視野帶來提升，但也可能伴隨學業與財務壓力。";
                        break;
                    case "business":
                        message = "您選擇了【自主創業】！這條路充滿機遇，但也可能面臨資金與市場的巨大風險。";
                        break;
                    case "marriage":
                        message = "您選擇了【步入婚姻】！這意味著新的責任與家庭的建立，但也可能帶來預期外的家庭開銷。";
                        break;
                }
                challengeOutcomeMessage.textContent = message;
                challengeOutcomeMessage.classList.remove('hidden', 'negative');
                challengeOutcomeMessage.classList.add('positive');

                // 確認加購按鈕在選擇挑戰後即可繼續
                confirmTurningPointPurchaseButton.disabled = false;
            });
        });


        // 確認人生轉折點加購，繼續遊戲流程 (觸發事件)
        confirmTurningPointPurchaseButton.addEventListener('click', () => {
            // 在玩家選擇挑戰後，才允許繼續
            if (!playerChallenge) {
                challengeOutcomeMessage.textContent = "請先選擇您的人生挑戰！";
                challengeOutcomeMessage.classList.remove('hidden', 'positive');
                challengeOutcomeMessage.classList.add('negative');
                return;
            }

            // 轉折點結束後，手動推進到下一個階段和測驗索引
            currentStageIndex = 2; // 移動到 gameStages 中的「挑戰之峰」階段 (索引 2)
            quizzesCompletedInCurrentStage = 0; // 重置當前階段問答計數
            currentQuizQuestionIndex = 5; // 設定為第 6 題的索引 (從 0 開始)
            
            justFinishedTurningPoint = true; // 標記剛結束轉折點，下一步應觸發事件
            lifeChallengeSimulator.classList.add('hidden'); // 隱藏人生挑戰模擬器
            startNextStage(); // 繼續遊戲流程 (觸發事件)
        });


        // 觸發隨機事件
        function triggerRandomEvent() {
            // 隱藏問答區塊，顯示事件區塊
            quizSection.classList.add('hidden');
            eventSection.classList.remove('hidden');

            // 應用本命星祝福：每回合資產/健康增益
            if (player.zodiacBlessing) {
                if (player.zodiacBlessing.type === "asset_per_round") {
                    player.assets += player.zodiacBlessing.value;
                    // 如果 outcomeMessage 已有內容，則追加
                    if (outcomeMessage.textContent) {
                        outcomeMessage.textContent += ` 您的【${player.zodiacBlessing.name}】祝福生效，額外獲得 $${player.zodiacBlessing.value.toLocaleString()} 資產！`;
                    } else {
                        outcomeMessage.textContent = `您的【${player.zodiacBlessing.name}】祝福生效，額外獲得 $${player.zodiacBlessing.value.toLocaleString()} 資產！`;
                    }
                    outcomeMessage.className = `message result-message positive`;
                    outcomeMessage.classList.remove('hidden');
                } else if (player.zodiacBlessing.type === "health_per_round") {
                    player.health = Math.min(100, player.health + player.zodiacBlessing.value);
                     // 如果 outcomeMessage 已有內容，則追加
                    if (outcomeMessage.textContent) {
                        outcomeMessage.textContent += ` 您的【${player.zodiacBlessing.name}】祝福生效，額外恢復 ${player.zodiacBlessing.value} 點健康！`;
                    } else {
                        outcomeMessage.textContent = `您的【${player.zodiacBlessing.name}】祝福生效，額外恢復 ${player.zodiacBlessing.value} 點健康！`;
                    }
                    outcomeMessage.className = `message result-message positive`;
                    outcomeMessage.classList.remove('hidden');
                }
            }


            // 根據玩家挑戰和本命星祝福調整事件機率
            let weightedEvents = [];
            const normalWeight = 1; // 預設權重
            const highWeight = 3; // 高權重，增加出現機率
            const clueBoostWeight = player.zodiacBlessing && player.zodiacBlessing.type === "clue_chance" ? (1 + player.zodiacBlessing.value) : 1;


            // 重新填充 allGameEvents，確保每次遊戲事件池是完整的
            allGameEvents = [];
            
            riskEvents.forEach(e => {
                let weight = normalWeight;
                if (e.only_if_challenge && e.only_if_challenge === playerChallenge) {
                    weight = highWeight; // 如果事件與玩家選擇的挑戰相關，權重增加
                }
                for (let i = 0; i < weight; i++) {
                    allGameEvents.push({ ...e, type: "risk" });
                }
            });

            clueEvents.forEach(e => {
                let weight = normalWeight * clueBoostWeight; // 應用線索祝福
                for (let i = 0; i < weight; i++) {
                    allGameEvents.push({ ...e, type: "clue" });
                }
            });
            
            lifeEvents.forEach(e => {
                let weight = normalWeight;
                if (e.only_if_challenge && e.only_if_challenge === playerChallenge) {
                    weight = highWeight; // 如果事件與玩家選擇的挑戰相關，權重增加
                }
                for (let i = 0; i < weight; i++) {
                    allGameEvents.push({ ...e, type: "life" });
                }
            });


            const eventIndex = Math.floor(Math.random() * allGameEvents.length);
            const event = allGameEvents[eventIndex];

            eventDescription.textContent = `【${event.name}】 - ${event.desc}`;

            if (event.type === "risk") {
                let hasRelevantInsurance = false;
                for (const triggerType of event.trigger) {
                    if (player.ownedInsurances.has(triggerType)) {
                        hasRelevantInsurance = true;
                        break;
                    }
                }

                let outcome;
                let msgClass = '';
                if (hasRelevantInsurance) {
                    outcome = event.with_insurance;
                    msgClass = 'result-message positive';
                    player.luckyEscapesCount++; // 幸運逃脫次數加1
                } else {
                    outcome = event.no_insurance;
                    msgClass = 'result-message negative';
                }

                let assetChange = outcome.assets;
                let healthChange = outcome.health;

                // 應用天蠍座祝福：風險損失減輕
                if (player.zodiacBlessing && player.zodiacBlessing.type === "risk_mitigation_percent") {
                    assetChange = Math.round(assetChange * (1 - player.zodiacBlessing.value)); // 減少損失
                    healthChange = Math.round(healthChange * (1 - player.zodiacBlessing.value));
                    if (assetChange < 0) assetChange = Math.min(0, assetChange); // 確保是損失減少
                    if (healthChange < 0) healthChange = Math.min(0, healthChange); // 確保是損失減少
                    outcomeMessage.textContent += ` (您的【${player.zodiacBlessing.name}】祝福減輕了部分損失)。`;
                }

                player.assets = Math.max(0, player.assets + assetChange); // 資產不低於0
                player.health = Math.max(0, Math.min(100, player.health + healthChange)); // 健康在0-100之間

                outcomeMessage.textContent = outcome.msg;
                outcomeMessage.className = `message ${msgClass}`;
                outcomeMessage.classList.remove('hidden');

            } else if (event.type === "clue") {
                player.cluesCollected.add(event.clue); // 收集線索
                outcomeMessage.textContent = `您發現了一條守護者線索！ "${event.clue}"`;
                outcomeMessage.className = `message result-message positive`;
                outcomeMessage.classList.remove('hidden');
                // 線索事件不影響資產和健康
            } else if (event.type === "life") {
                player.assets = player.assets + (event.assets || 0);
                player.health = Math.max(0, Math.min(100, player.health + (event.health || 0)));
                outcomeMessage.textContent = `【人生小確幸】${event.desc}！`;
                outcomeMessage.className = `message result-message positive`;
                outcomeMessage.classList.remove('hidden');
            }

            updateDisplay();

            // 判斷遊戲是否應提前結束 (破產或健康歸零)
            if ((player.assets <= 0 || player.health <= 0) && !player.rebirthUsed) {
                setTimeout(() => {
                    showRebirthModal(); // 顯示獲得新生彈窗
                }, 1000);
            } else if (player.assets <= 0 || player.health <= 0) { // 如果已經用過重生，就直接結束
                 setTimeout(() => {
                    endGame("early");
                }, 1000);
            }
        }

        // 顯示獲得新生彈窗
        function showRebirthModal() {
            rebirthModal.classList.add('show');
            nextEventButton.disabled = true; // 禁用繼續按鈕
        }

        // 激活獲得新生功能
        activateRebirthButton.addEventListener('click', () => {
            player.rebirthUsed = true;
            player.assets = Math.max(initialStates[player.role.id].assets * 0.2, 10000); // 恢復到初始資產的20%或至少10000
            player.health = Math.max(initialStates[player.role.id].health * 0.3, 30); // 恢復到初始健康的30%或至少30
            
            rebirthModal.classList.remove('show');
            nextEventButton.disabled = false; // 啟用繼續按鈕
            outcomeMessage.textContent = "您啟動了「獲得新生」！生命羅盤為您重啟，繼續您的旅程！";
            outcomeMessage.className = `message result-message positive`;
            outcomeMessage.classList.remove('hidden');
            updateDisplay();
            // 繼續當前回合的流程
            startNextStage();
        });


        // 「進入下一回合」按鈕的點擊事件 (用於從事件跳轉到下一回合的問答)
        nextEventButton.addEventListener('click', () => {
            currentRound++; // 總回合數增加
            quizzesCompletedInCurrentStage++; // 當前階段已完成的問答數增加

            const currentStage = gameStages[currentStageIndex];

            // 檢查當前階段的問答是否已完成
            if (quizzesCompletedInCurrentStage >= currentStage.quizCount) {
                currentStageIndex++; // 移動到下一個階段
                quizzesCompletedInCurrentStage = 0; // 重置當前階段問答計數
            }
            // currentQuizQuestionIndex 在 nextQuizQuestionButton 中或 confirmTurningPointPurchaseButton 中已處理
            startNextStage(); // 繼續遊戲流程 (問答或結束)
        });

        // 主要遊戲進程控制函數
        function startNextStage() {
            updateDisplay();

            // 檢查遊戲是否結束 (所有階段都已完成)
            if (currentStageIndex >= gameStages.length) {
                endGame();
                return;
            }

            // 檢查是否需要觸發「獲得新生」
            if ((player.assets <= 0 || player.health <= 0) && !player.rebirthUsed) {
                showRebirthModal();
                return;
            } else if (player.assets <= 0 || player.health <= 0) { // 如果已經用過重生，就直接結束
                 endGame("early");
                 return;
            }

            // 判斷當前應該是問答還是事件
            if (justAnsweredQuiz || justFinishedTurningPoint) {
                // 如果剛回答完問題或剛結束轉折點，則觸發隨機事件
                justAnsweredQuiz = false; // 重置標記
                justFinishedTurningPoint = false; // 重置標記
                showScreen('game-play');
                triggerRandomEvent();
            } else {
                // 否則，顯示問答環節
                quizSection.classList.remove('hidden');
                eventSection.classList.add('hidden');
                showScreen('game-play');
                renderQuizQuestion();
            }
        }


        // 計算最終得分與擊敗百分比 (模擬數據)
        function calculateFinalScoreAndPercentage() {
            // 修正：確保 player.role 存在，若不存在則返回預設值
            if (!player.role) {
                console.error("Error: player.role is undefined when calculating final score. Returning default.");
                return 0; // 或者可以返回一個表示錯誤的特殊值
            }

            const initialAssets = player.role.assets;
            const initialHealth = player.role.health;

            // 綜合分數計算：考慮最終資產、健康，以及是否有保險的正面影響
            // 簡化分數計算：最終資產 / 初始資產 + 最終健康 / 初始健康
            let financialRatio = player.assets / initialAssets;
            let healthRatio = player.health / initialHealth;

            // 如果健康或資產歸零，分數會很低
            if (player.assets <= 0) financialRatio = 0;
            if (player.health <= 0) healthRatio = 0;

            // 基礎分數 (0-2)
            let baseScore = financialRatio + healthRatio;

            // 擁有保險的額外加分 (鼓勵投保)
            player.protectionCompletionScore = player.ownedInsurances.size; // 更新保障完成度分數
            let insuranceBonus = player.ownedInsurances.size * 0.1; // 每多一份保險加0.1分
            // 應用摩羯座祝福：保障完成度分數更高
            if (player.zodiacBlessing && player.zodiacBlessing.type === "protection_score_boost") {
                insuranceBonus += player.zodiacBlessing.value * player.ownedInsurances.size;
            }
            baseScore += insuranceBonus;

            // 應用水瓶座祝福：幸運逃脫次數加成
            if (player.zodiacBlessing && player.zodiacBlessing.type === "lucky_escape_boost_count") {
                player.luckyEscapesCount += player.zodiacBlessing.value;
            }

            // 將分數轉換為百分比 (模擬擊敗其他玩家)
            // 這裡使用一個非線性轉換，讓值映射到0-100
            let percentage = Math.round(Math.tanh(baseScore / 1.5) * 100); // tanh函數將值映射到-1到1，再調整到0-100
            
            // 確保百分比在合理範圍內，例如 10% 到 99%
            percentage = Math.max(10, Math.min(99, percentage + Math.floor(Math.random() * 10 - 5))); // 增加一些隨機波動

            return percentage;
        }

        // 根據最終狀態推薦產品
        function getRecommendedProducts() {
            let recommendations = [];
            let roleId = player.role ? player.role.id : null;

            if (player.assets <= 50000 || player.health <= 50) {
                recommendations.push("醫療險 (實支實付型)", "意外險", "定期壽險");
                recommendations.push("強化基礎保障，避免風險再次侵蝕您的資產與健康。");
            } else if (player.assets > 150000 && player.health > 80) {
                recommendations.push("儲蓄險", "年金險", "投資型保單");
                recommendations.push("恭喜您！您的財務穩健，可考慮透過儲蓄或投資型保單，進一步累積財富，規劃更豐盛的未來。");
            } else {
                recommendations.push("重大疾病險", "長期照護險", "家庭保障型壽險");
                recommendations.push("您的旅程平穩，但仍需未雨綢繆。建議加強重大疾病與長期照護保障，確保未來生活品質。");
            }

            // 根據角色特性進行微調
            if (roleId === "steady_guardian") {
                recommendations.push("特別推薦：家庭保障型壽險、子女教育金險。");
            } else if (roleId === "free_explorer") {
                recommendations.push("特別推薦：高額意外險、海外突發疾病醫療險。");
            } else if (roleId === "ambitious_pioneer") {
                recommendations.push("特別推薦：定期壽險 (高保額)、重大疾病險。");
            } else if (roleId === "wise_planner") {
                 recommendations.push("特別推薦：年金險、長期照護險。");
            } else if (roleId === "harmonious_co_creator") {
                 recommendations.push("特別推薦：綜合型醫療險、家庭保障方案。");
            } else if (roleId === "empathic_connector") {
                 recommendations.push("特別推薦：醫療險、防癌險。");
            }
            // 根據人生挑戰進行微調
            if (playerChallenge === "study") {
                recommendations.push("因留學挑戰，更建議：海外突發疾病醫療險、儲蓄險（備用金）。");
            } else if (playerChallenge === "business") {
                recommendations.push("因創業挑戰，更建議：高額意外險、儲蓄險（創業備用金）。");
            } else if (playerChallenge === "marriage") {
                recommendations.push("因婚姻挑戰，更建議：家庭保障型壽險、醫療險、子女教育金險。");
            }


            return recommendations.join("<br>");
        }

        // 獲取成就稱號
        function getAchievementTitle() {
            let title = "平凡的旅者";
            const totalPossibleScore = quizQuestions.length; // 總題數
            const quizAccuracy = player.riskJudgmentScore / totalPossibleScore;
            const insuranceCoverage = player.ownedInsurances.size / availableInsurances.length;

            if (quizAccuracy >= 0.9 && insuranceCoverage >= 0.7 && player.luckyEscapesCount >= 3) {
                title = "【生命羅盤大師】";
            } else if (quizAccuracy >= 0.7 && insuranceCoverage >= 0.5 && player.luckyEscapesCount >= 2) {
                title = "【智慧守護者】";
            } else if (player.luckyEscapesCount >= 1) {
                title = "【幸運的探索者】";
            } else if (player.riskJudgmentScore >= totalPossibleScore * 0.6) {
                 title = "【知識領航員】";
            } else if (player.ownedInsurances.size >= availableInsurances.length * 0.5) {
                title = "【保障先行者】";
            }

            // 結合星座特質
            if (player.zodiac === "水瓶座" && title === "幸運的探索者") {
                title = "【最聰明的水瓶座】"; // 範例：水瓶座的幸運逃脫加成
            } else if (player.zodiac === "射手座" && player.assets < initialStates[player.role.id].assets * 0.5) {
                title = "【最倒楣的射手座】"; // 範例：射手座如果資產很低
            }

            return title;
        }

        // 保存分數到排行榜
        async function saveScoreToLeaderboard() {
            if (!db || !userId) {
                console.error("Firestore not initialized or user not authenticated. Cannot save score.");
                return;
            }

            try {
                const finalScore = calculateFinalScoreAndPercentage(); // 使用百分比作為分數
                const achievementTitle = getAchievementTitle();
                const zodiac = player.zodiac;
                const blessingName = player.zodiacBlessing ? player.zodiacBlessing.name : "無";

                const leaderboardCollectionRef = collection(db, `artifacts/${appId}/public/data/leaderboard`);
                await addDoc(leaderboardCollectionRef, {
                    userId: userId,
                    zodiac: zodiac,
                    achievementTitle: achievementTitle,
                    finalScore: finalScore,
                    blessingName: blessingName,
                    timestamp: new Date()
                });
                console.log("Score saved to leaderboard!");
            } catch (e) {
                console.error("Error adding document to leaderboard: ", e);
            }
        }

        // 載入並顯示排行榜
        async function loadLeaderboard() {
            if (!db) {
                console.error("Firestore not initialized. Cannot load leaderboard.");
                return;
            }

            leaderboardList.innerHTML = '<li>載入排行榜中...</li>';
            displayUserId.textContent = userId; // 顯示當前使用者的 ID

            try {
                const leaderboardCollectionRef = collection(db, `artifacts/${appId}/public/data/leaderboard`);
                const querySnapshot = await getDocs(leaderboardCollectionRef);
                
                let scores = [];
                querySnapshot.forEach((doc) => {
                    scores.push(doc.data());
                });

                // 依分數降序排序 (客戶端排序，避免 Firestore 索引問題)
                scores.sort((a, b) => b.finalScore - a.finalScore); 

                leaderboardList.innerHTML = ''; // 清除載入訊息

                // 顯示前 10 名或所有分數
                const topScores = scores.slice(0, 10);
                if (topScores.length === 0) {
                    leaderboardList.innerHTML = '<li>目前無排行榜資料。</li>';
                } else {
                    topScores.forEach((score, index) => {
                        const li = document.createElement('li');
                        li.style.cssText = `
                            background-color: rgba(52, 73, 94, 0.5);
                            padding: 8px 15px;
                            margin-bottom: 5px;
                            border-radius: 5px;
                            display: flex;
                            justify-content: space-between;
                            align-items: center;
                            font-size: 1em;
                            ${score.userId === userId ? 'border: 2px solid #f1c40f; box-shadow: 0 0 10px rgba(241, 196, 15, 0.5);' : ''} /* 突出顯示當前使用者 */
                        `;
                        li.innerHTML = `
                            <span>${index + 1}. <strong>${score.zodiac}</strong> (${score.achievementTitle})</span>
                            <span>分數: <span style="color: #34D399; font-weight: bold;">${score.finalScore}%</span></span>
                        `;
                        leaderboardList.appendChild(li);
                    });
                }
            } catch (e) {
                console.error("Error loading leaderboard: ", e);
                leaderboardList.innerHTML = '<li>載入排行榜失敗。</li>';
            }
        }

        // 遊戲結束
        function endGame(reason = "normal") {
            showScreen('end-game');
            finalAssets.textContent = `$${player.assets.toLocaleString()}`;
            finalHealth.textContent = player.health;

            const beatPercentage = calculateFinalScoreAndPercentage();
            beatPercentageMessage.textContent = `根據您的生命旅程表現，您贏過了 ${beatPercentage}% 的模擬者！`;
            beatPercentageMessage.classList.remove('hidden');

            if (reason === "early") {
                finalOutcomeText.textContent = `很抱歉，您的旅程提前結束了。因資產耗盡或健康歸零，您未能完成所有人生階段。這提醒我們，面對風險，規劃和保障的重要性！`;
                beatPercentageMessage.classList.remove('positive'); // 移除可能存在的positive class
                beatPercentageMessage.classList.add('negative'); // 顯示為紅色
            } else if (player.role && player.assets > initialStates[player.role.id].assets * 0.8 && player.health > initialStates[player.role.id].health * 0.8) {
                finalOutcomeText.textContent = `恭喜您！您的【${player.zodiac}】旅程圓滿結束。您在風險中做出了明智的決策，保險的「守護者」力量助您平穩度過挑戰，最終取得了不錯的成就！`;
                beatPercentageMessage.classList.remove('negative');
                beatPercentageMessage.classList.add('positive');
            } else if (player.role) { // 確保 player.role 存在再顯示角色名稱
                finalOutcomeText.textContent = `您的【${player.zodiac}】旅程結束了。儘管遇到挑戰，您的選擇讓您堅持到了最後。下次或許可以更全面地運用「守護者」的力量，讓人生羅盤更加穩固！`;
                beatPercentageMessage.classList.remove('positive', 'negative'); // 移除所有顏色
            } else { // 如果 player.role 仍然是 null 或 undefined，提供一個通用訊息
                finalOutcomeText.textContent = `您的生命旅程結束了。由於某些原因，無法完整呈現您的角色資訊。請重新開始遊戲。`;
                beatPercentageMessage.classList.add('hidden'); // 隱藏百分比訊息
            }

            // 最終保險列表
            finalOwnedInsurancesList.innerHTML = '';
            if (player.ownedInsurances.size === 0) {
                finalOwnedInsurancesList.innerHTML = '<li>無任何保險契約</li>';
            } else {
                player.ownedInsurances.forEach(id => {
                    const insurance = availableInsurances.find(ins => ins.id === id);
                    if (insurance) {
                        const li = document.createElement('li');
                        li.textContent = insurance.name;
                        finalOwnedInsurancesList.appendChild(li);
                    }
                });
            }

            // 守護者之謎揭示
            let revealText = "";
            if (player.cluesCollected.size >= 3) { // 收集到足夠線索
                revealText = `您收集了足夠的線索，終於揭開了「守護者」的真面目！<br><br>「守護者」並非單一實體，而是**「風險分散、預防與轉嫁」**的集合體，它以**保險**的形式存在於世，默默守護著每個人的生命旅程。當您預先規劃、承擔責任時，它便會顯現其力量，為您抵擋風雨，讓您的人生羅盤穩固前行。`;
            } else {
                revealText = `您的人生旅程結束了，但「守護者」之謎仍未完全解開。或許在未來的旅程中，您會發現更多關於它如何默默守護的線索。`;
            }
            mysteryRevealText.innerHTML = revealText;

            // 國泰人壽推薦產品和標語
            recommendedProductsText.innerHTML = getRecommendedProducts();

            // 更新排行榜數據
            finalRiskJudgment.querySelector('strong').textContent = `${player.riskJudgmentScore} / ${quizQuestions.length}`;
            finalProtectionCompletion.querySelector('strong').textContent = `${player.ownedInsurances.size} / ${availableInsurances.length} 項`;
            finalLuckyEscapes.querySelector('strong').textContent = `${player.luckyEscapesCount} 次`;
            finalAchievementTitle.querySelector('strong').textContent = getAchievementTitle();
            finalZodiacBlessingSummary.querySelector('strong').textContent = player.zodiacBlessing ? `${player.zodiacBlessing.name} (${player.zodiacBlessing.desc})` : "無";

            // 顯示星座幸運祝福卡和對應圖片
            // 隱藏所有星座圖片
            document.querySelectorAll('.zodiac-image-container').forEach(img => img.classList.add('hidden'));

            if (player.zodiacBlessing) {
                blessingCardText.innerHTML = `您的本命星【<span class="blessing-name-highlight">${player.zodiacBlessing.name}</span>】持續守護著您！<br>${player.zodiacBlessing.desc}`;
                
                // 根據 player.zodiacId 找到對應的圖片元素並顯示
                const zodiacImageElement = document.getElementById(`${player.zodiacId}-image`);
                const zodiacInfo = zodiacToRoleMap[player.zodiacId];

                if (zodiacImageElement && zodiacInfo && zodiacInfo.imageUrl) {
                    zodiacImageElement.src = zodiacInfo.imageUrl; // 設定圖片來源
                    zodiacImageElement.classList.remove('hidden'); // 顯示對應圖片
                } else {
                    console.warn(`無法找到或載入 ${player.zodiac} 的圖片。`);
                }
            } else {
                blessingCardText.textContent = "您沒有獲得特殊的本命星祝福。";
            }
            
            // 保存分數並載入排行榜
            saveScoreToLeaderboard();
            loadLeaderboard();
        }

        // 社群分享功能
        shareResultButton.addEventListener('click', () => {
            const achievementTitle = getAchievementTitle();
            const finalScore = calculateFinalScoreAndPercentage();
            const blessingSummary = player.zodiacBlessing ? `您的本命星祝福：${player.zodiacBlessing.name} - ${player.zodiacBlessing.desc}` : "無本命星祝福。";

            const shareText = `我在國泰人壽【生命羅盤：星軌守護】中，完成了【${player.zodiac}】的人生模擬！\n` +
                               `我的最終成就稱號：${achievementTitle}\n` +
                               `綜合分數：${finalScore}%\n` +
                               `風險判斷力指數：${player.riskJudgmentScore}/${quizQuestions.length}\n` +
                               `保障完成度：${player.ownedInsurances.size}/${availableInsurances.length} 項\n` +
                               `幸運逃脫次數：${player.luckyEscapesCount} 次\n` +
                               `${blessingSummary}\n\n` +
                               `快來挑戰你的人生羅盤吧！#國泰人壽 #生命羅盤 #安心守護`;
            
            // 直接呼叫 fallback 函數，因為 Clipboard API 在某些環境下可能被阻擋
            fallbackCopyTextToClipboard(shareText);
        });

        function fallbackCopyTextToClipboard(text) {
            const textArea = document.createElement("textarea");
            textArea.value = text;
            // 避免在頁面上顯示滾動條
            textArea.style.position = "fixed";
            textArea.style.left = "-999999px";
            textArea.style.top = "-999999px";
            document.body.appendChild(textArea);
            textArea.focus();
            textArea.select();
            try {
                const successful = document.execCommand('copy');
                const msg = successful ? '成功複製到剪貼簿！' : '無法自動複製，請手動複製。';
                copyMessage.textContent = msg;
                copyMessage.classList.remove('hidden');
                setTimeout(() => copyMessage.classList.add('hidden'), 3000);
            } catch (err) {
                console.error('Fallback: 無法複製文字', err);
                copyMessage.textContent = '無法自動複製，請手動複製。';
                copyMessage.classList.remove('hidden');
                setTimeout(() => copyMessage.classList.add('hidden'), 3000);
            }
            document.body.removeChild(textArea);
        }

        // 重新開始遊戲
        restartGameButton.addEventListener('click', initializeGame);
        startButton.addEventListener('click', () => {
            showScreen('character-selection');
            renderZodiacSelection(); // 渲染星座選擇按鈕
            roleDescription.textContent = "請點擊您的星座按鈕了解更多。"; // Reset desc
            zodiacBlessingDescription.textContent = ""; // Reset blessing desc
        });

        // 初始載入：先設定 Firebase，然後初始化遊戲
        window.onload = async () => {
            await setupFirebase();
            initializeGame();
        };
    </script>
</body>
</html>
