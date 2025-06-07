<html lang="vi"><head>
<meta charset="UTF-8">
<title>My Simple Panel</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      text-align: center;
      background-color: #1a1a1a;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
    }

    @media (max-width: 768px) {
      body {
        font-size: 16px;
        padding: 10px;
      }

      .panel {
        width: 100%;
        padding: 20px;
        box-sizing: border-box;
      }

      h1 {
        font-size: 40px;
      }

      .funtion {
        flex-direction: column;
        gap: 20px;
      }

      .inform {
        width: 100%;
      }

      button {
        width: 100%;
        font-size: 22px;
      }

      .social-buttons {
        flex-direction: column;
        align-items: center;
      }

      .social-buttons button {
        width: 100%;
      }

      .social-buttons button img {
        width: 40px;
        height: 40px;
      }
    }

    h1 {
      font-size: 80px;
      font-weight: bold;
      background: linear-gradient(270deg, #ff7f50, #FFFF00, #ff1493, #ff7f50, #ff0000, #ff00ff, #00EE00);
      background-size: 800% 800%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: gradientMove 3s ease infinite;
      margin: 0;
      text-align: center;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
let urls = ["Mở Free Fire", "Mở Free Fire Max"];
    let selectedURL = await showMenu(urls);
    
    if (selectedURL === 0) {
      Safari.open("freefire://");
    } else if (selectedURL === 1) {
      Safari.open("freefiremax://");
    }

    .panel {
      width: 90%;
      max-width: 900px;
      padding: 30px;
      background-color: #2c2c2c;
      border-radius: 15px;
      border: 2px solid #ff0000;
      box-shadow: 0 0 80px rgba(255, 99, 71, 0.9);
      animation: glow 2s ease-in-out infinite;
    }

    @keyframes glow {
      0% { box-shadow: 0 0 0 rgba(255, 255, 255, 0); }
      50% { box-shadow: 0 0 80px rgba(255, 99, 71, 0.8); }
      100% { box-shadow: 0 0 0 rgba(255, 255, 255, 0); }
    }

    .funtion {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 50px;
      margin: 40px auto;
      max-width: 800px;
    }

    .switch {
      position: relative;
      display: inline-block;
      width: 140px;
      height: 70px;
    }

    .switch input {
      opacity: 0;
      width: 0;
      height: 0;
    }

    .slider {
      position: absolute;
      cursor: pointer;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: #ccc;
      transition: 1s;
      border-radius: 70px;
      border: 2px solid transparent;
    }

    .slider:before {
      position: absolute;
      content: "";
      height: 60px;
      width: 60px;
      left: 4px;
      bottom: 3px;
      background-color: white !important;
      border-radius: 50%;
    }

    input:checked + .slider {
      background-color: #FF0000;
    }

    input:checked + .slider:before {
    transform: translateX(70px);
    }

    .divider {
      width: 80%;
      height: 6px;
      background: linear-gradient(to right, red, blue, red);
      animation: gradientMove 1s ease infinite;
      margin: 20px auto;
      border-radius: 5px;
    }

    .divider-x {
      width: 80%;
      height: 3px;
      background-color: #ff6347, #FF0000, #FF00FF;
      margin: 20px auto;
      animation: gradientMove 1s ease infinite;
      border-radius: 5px;
      border-top: 2px solid #FFFF00;
    }

    .inform {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
      margin-top: 40px;
      width: 100%;
    }

    button {
      padding: 12px 20px;
      font-size: 22px;
      background: linear-gradient(135deg,#FFFF00, #FF00FF, #00EE00, #FF0000);
      animation: gradientMove 1s ease infinite;
      box-shadow: 0 4px 15px rgba(255, 99, 71, 0.5);
      color: black;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      transition: all 1s ease;
    }

    button img {
      width: 40px;
      height: 40px;
      object-fit: contain;
      margin-right: 10px;
    }

    button:hover {
      filter: brightness(1.2);
      box-shadow: 0 6px 20px rgba(255, 99, 71, 0.8);
    }

    button:active {
      transform: scale(0.98);
    }

    p {
      font-weight: bold;
      font-size: 28px;
      margin: 10px 0;
      color: #FFFF00;
    }

    .social-buttons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      width: 100%;
    }

    .social-buttons button {
      width: 180px;
    }

    .funtion p {
      font-size: 50px;
      font-weight: bold;
      margin: 5px 0 0 0;
      color: #FFFFFF;
    }

    .final-note {
      margin-top: 15px;
    }

    a {
  text-decoration: none;
}

.social-buttons a {
  text-decoration: none;
}

  </style>
</head>
<body>
  <div class="panel">
    <h1>MENU IOS <br> CAO KHÁNH DUY</h1>
    <div class="divider"></div>

    <div class="funtion">
      <p>𝙄𝘼𝙈𝘽𝙊𝙏</p>
      <label class="switch">
        <input type="checkbox" id="switch𝙄𝘼𝙈𝘽𝙊𝙏" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
    </div>

    <div class="funtion">
      <p>𝑨𝑰𝑴𝑳𝑶𝑪𝑲</p>
      <label class="switch">
        <input type="checkbox" id="switch𝑨𝑰𝑴𝑳𝑶𝑪𝑲" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
    </div>

    <div class="funtion">
      <p>𝙆𝙃𝙊́𝘼 𝘾𝙊̂̉</p>
      <label class="switch">
        <input type="checkbox" id="switch𝙆𝙃𝙊́𝘼 𝘾𝙊̂̉" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
    </div>
    
    <div class="funtion">
      <p>𝙏𝘼̆𝙉𝙂 𝟮𝟱𝟬𝙃𝙋𝙎</p>
      <label class="switch">
        <input type="checkbox"
id="switch𝙏𝘼̆𝙉𝙂 𝟮𝟱𝟬𝙃𝙋𝙎" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
     </div>
    
    <div class="funtion">
      <p>𝑻𝑹𝑰𝑪𝑲 𝑯𝑬𝑨𝑫</p>
      <label class="switch">
        <input type="checkbox"
id="switch𝑻𝑹𝑰𝑪𝑲 𝑯𝑬𝑨𝑫" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
     </div>
    
    <div class="funtion">
      <p>𝑭𝑰𝑿 𝑹𝑼𝑵𝑮</p>
      <label class="switch">
        <input type="checkbox"
id="switch𝑭𝑰𝑿 𝑹𝑼𝑵𝑮" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
     </div>
    
    <div class="funtion">
      <p>𝑫𝑷𝑰 𝑻𝑹𝑰𝑪𝑲 𝑽𝟑</p>
      <label class="switch">
        <input type="checkbox"
id="switch𝑫𝑷𝑰 𝑻𝑹𝑰𝑪𝑲 𝑽𝟑" onchange="switchChanged()">
        <span class="slider"></span>
      </label>
     </div>

    <div class="divider"></div>

    <div class="inform">
      <div class="social-buttons">
        <a href="https://zalo.me.g/kfmghp515">
          <button><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Icon_of_Zalo.svg/75px-Icon_of_Zalo.svg.png?20221117065843" alt="Zalo Logo">Zalo</button>
        </a>
        <a href="https://www.facebook.com/share/14FrsDPeHbp/?mibextid=wwXlfr">
        <button><img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo">Facebook</button>
        </a>
        <a href="https://youtube.com/@CAOKHANHDUY2011?si=88RYXEJYKM01hEGy">
          <button><img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube Logo">YouTube</button>
        </a>
        <a href="https://www.tiktok.com/@caokhanhduy8?_t=ZS-8wFDJSvbBmJ&amp;_r=1">
          <button><img src="https://www.logo.wine/a/logo/TikTok/TikTok-Logo.wine.svg" alt="TikTok Logo">TikTok</button>
        </a>
      </div>
      <p class="final-note">nhớ Đăng ký YouTube và follow TikTok để ủng hộ mình nha ♥</p>
    </div>
  </div>

  <script>
    function switchChanged(feature) {
      var switchElement;
      
      switch (feature) {
        case 'Aimbot':
          switchElement = document.getElementById('switchAimbot');
          if (switchElement.checked) {
            console.log('Aimbot is enabled');
            address = ("https://ff.garena.com/vn/")
            Aimbot = ("headshot 90%");
            Aimlock = ("headshot 90%")
            Sensi = ("60%")
          } else {
            console.log('Aimbot is disabled');
            Aimbot = ("0");
          }
          break;
        
        case 'khóa cổ':
          switchElement = document.getElementById('switchAimLock');
          if (switchElement.checked) {
            console.log('AimLock is enabled');
            Aimlock = ("");
          } else {
            console.log('AimLock is disabled');
            Aimlock = ("0");
          }
          break;

        case 'khóa cổ':
          switchElement = document.getElementById('switchkhóa cổ');
          if (switchElement.checked) {
            console.log('khóa cổ is enabled');
            khóa cổ = ("0");
          } else {
            console.log('Khóa cổ is disabled');
            khóa cổ = ("0");
          }
          break;
      }
    }
  </script>


  </body></html>
