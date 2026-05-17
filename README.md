<div id="profile-root" style="font-family: 'Segoe UI', system-ui, -apple-system, sans-serif; max-width: 900px; margin: 0 auto; padding: 20px; transition: background 0.3s, color 0.3s;">
  <div style="display: flex; justify-content: flex-end; gap: 12px; margin-bottom: 20px;">
    <button id="themeBtn" onclick="toggleTheme()" style="
      background: linear-gradient(135deg, #161b22, #1a1f2e);
      border: 1px solid #30363d;
      color: #c9d1d9;
      padding: 8px 16px;
      border-radius: 8px;
      cursor: pointer;
      font-family: inherit;
      font-size: 14px;
      transition: all 0.3s ease;
    " onmouseover="this.style.borderColor='#6366f1'; this.style.transform='translateY(-1px)'; this.style.boxShadow='0 4px 12px rgba(99,102,241,0.2)';" 
       onmouseout="this.style.borderColor='#30363d'; this.style.transform='translateY(0)'; this.style.boxShadow='none';">
      🌓 Тема
    </button>
    <button id="langBtn" onclick="toggleLang()" style="
      background: linear-gradient(135deg, #161b22, #1a1f2e);
      border: 1px solid #30363d;
      color: #c9d1d9;
      padding: 8px 16px;
      border-radius: 8px;
      cursor: pointer;
      font-family: inherit;
      font-size: 14px;
      transition: all 0.3s ease;
    " onmouseover="this.style.borderColor='#6366f1'; this.style.transform='translateY(-1px)'; this.style.boxShadow='0 4px 12px rgba(99,102,241,0.2)';" 
       onmouseout="this.style.borderColor='#30363d'; this.style.transform='translateY(0)'; this.style.boxShadow='none';">
      🌐 EN
    </button>
  </div>

  <!-- Шапка с градиентом -->
  <div align="center" style="margin-bottom: 30px;">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,14,18&height=160&section=header&text=wassss337&fontSize=70&fontColor=ffffff&animation=fadeIn" width="100%">
  </div>

  <h1 align="center" style="
    background: linear-gradient(135deg, #6366f1, #a78bfa);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 5px;
    font-size: 32px;
    animation: fadeInUp 0.8s ease;
  ">
    👋 <span class="ru">Привет</span><span class="en" style="display:none;">Hi</span>, я wassss337
  </h1>

  <p align="center" style="color: #8b949e; font-size: 16px; margin-bottom: 30px; animation: fadeInUp 0.8s ease 0.2s both;">
    <span class="ru">Создаю языки программирования, нейросети и мессенджеры.</span>
    <span class="en" style="display:none;">Building programming languages, neural networks and messengers.</span>
  </p>

  <!-- Статистика -->
  <div align="center" style="margin-bottom: 30px; animation: fadeInUp 0.8s ease 0.3s both;">
    <img src="https://komarev.com/ghpvc/?username=wassss337&style=for-the-badge&color=6366f1">
    <img src="https://img.shields.io/github/followers/wassss337?style=for-the-badge&color=6366f1">
    <img src="https://img.shields.io/github/stars/wassss337?style=for-the-badge&color=6366f1&affiliations=OWNER">
  </div>

  <!-- Обо мне -->
  <div id="about-card" style="
    background: linear-gradient(135deg, #161b22, #1a1f2e);
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 25px;
    margin-bottom: 25px;
    transition: all 0.3s ease;
    animation: fadeInUp 0.8s ease 0.4s both;
  " onmouseover="this.style.borderColor='#6366f1'; this.style.boxShadow='0 8px 30px rgba(99,102,241,0.1)'; this.style.transform='translateY(-2px)';" 
     onmouseout="this.style.borderColor='#30363d'; this.style.boxShadow='none'; this.style.transform='translateY(0)';">
    <h3 style="
      background: linear-gradient(135deg, #6366f1, #a78bfa);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-top: 0;
      font-size: 20px;
    ">
      📋 <span class="ru">Обо мне</span><span class="en" style="display:none;">About me</span>
    </h3>
    <ul style="color: #c9d1d9; line-height: 2.2; list-style: none; padding-left: 0;">
      <li style="transition: transform 0.2s;" onmouseover="this.style.transform='translateX(5px)'" onmouseout="this.style.transform='translateX(0)'">
        🔭 <span class="ru"><strong>Работаю над:</strong> Gava, Flask Messenger, LGTM Browser</span>
        <span class="en" style="display:none;"><strong>Working on:</strong> Gava, Flask Messenger, LGTM Browser</span>
      </li>
      <li style="transition: transform 0.2s;" onmouseover="this.style.transform='translateX(5px)'" onmouseout="this.style.transform='translateX(0)'">
        🌱 <span class="ru"><strong>Изучаю:</strong> C++ DLL, Windows Internals, AI</span>
        <span class="en" style="display:none;"><strong>Learning:</strong> C++ DLL, Windows Internals, AI</span>
      </li>
      <li style="transition: transform 0.2s;" onmouseover="this.style.transform='translateX(5px)'" onmouseout="this.style.transform='translateX(0)'">
        💬 <span class="ru"><strong>Спросите меня о:</strong> C++, Python, Flask, WinAPI, нейросетях</span>
        <span class="en" style="display:none;"><strong>Ask me about:</strong> C++, Python, Flask, WinAPI, neural networks</span>
      </li>
      <li style="transition: transform 0.2s;" onmouseover="this.style.transform='translateX(5px)'" onmouseout="this.style.transform='translateX(0)'">
        ⚡ <span class="ru"><strong>Факт:</strong> Упал на метровую медузу и выжил. Сделал язык программирования с нуля.</span>
        <span class="en" style="display:none;"><strong>Fun fact:</strong> Fell on a meter-wide jellyfish and survived. Built a programming language from scratch.</span>
      </li>
      <li style="transition: transform 0.2s;" onmouseover="this.style.transform='translateX(5px)'" onmouseout="this.style.transform='translateX(0)'">
        🏆 <span class="ru"><strong>Достижения:</strong> Создал свою соцсеть, нейросеть на C++, эмулятор терминала</span>
        <span class="en" style="display:none;"><strong>Achievements:</strong> Built own social network, neural net in C++, terminal emulator</span>
      </li>
    </ul>
  </div>

  <div id="projects-card" style="
    background: linear-gradient(135deg, #161b22, #1a1f2e);
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 25px;
    margin-bottom: 25px;
    transition: all 0.3s ease;
    animation: fadeInUp 0.8s ease 0.5s both;
  " onmouseover="this.style.borderColor='#6366f1'; this.style.boxShadow='0 8px 30px rgba(99,102,241,0.1)'; this.style.transform='translateY(-2px)';" 
     onmouseout="this.style.borderColor='#30363d'; this.style.boxShadow='none'; this.style.transform='translateY(0)';">
    <h3 style="
      background: linear-gradient(135deg, #6366f1, #a78bfa);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-top: 0;
      font-size: 20px;
    ">
      🚀 <span class="ru">Проекты</span><span class="en" style="display:none;">Projects</span>
    </h3>
    <table style="width: 100%; border-collapse: collapse;">
      <tr>
        <td style="padding: 15px; border-bottom: 1px solid #30363d; border-right: 1px solid #30363d; transition: background 0.2s;" onmouseover="this.style.background='rgba(99,102,241,0.05)'" onmouseout="this.style.background='transparent'">
          <strong style="color: #c9d1d9; font-size: 16px;">⚡ Gava</strong><br>
          <small style="color: #8b949e;">
            <span class="ru">Язык программирования на C++ с Java-подобным синтаксисом</span>
            <span class="en" style="display:none;">Programming language in C++ with Java-like syntax</span>
          </small><br>
          <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
          <img src="https://img.shields.io/badge/WinAPI-0078D6?style=flat-square&logo=windows&logoColor=white">
          <img src="https://img.shields.io/badge/GUI-6366f1?style=flat-square&logo=windowsterminal&logoColor=white">
        </td>
        <td style="padding: 15px; border-bottom: 1px solid #30363d; transition: background 0.2s;" onmouseover="this.style.background='rgba(99,102,241,0.05)'" onmouseout="this.style.background='transparent'">
          <strong style="color: #c9d1d9; font-size: 16px;">💬 Flask Messenger</strong><br>
          <small style="color: #8b949e;">
            <span class="ru">Социальная сеть с чатами, группами, каналами, AI</span>
            <span class="en" style="display:none;">Social network with chats, groups, channels, AI</span>
          </small><br>
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
          <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
          <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
        </td>
      </tr>
      <tr>
        <td style="padding: 15px; border-bottom: 1px solid #30363d; border-right: 1px solid #30363d; transition: background 0.2s;" onmouseover="this.style.background='rgba(99,102,241,0.05)'" onmouseout="this.style.background='transparent'">
          <strong style="color: #c9d1d9; font-size: 16px;">🧠 Neural C++</strong><br>
          <small style="color: #8b949e;">
            <span class="ru">Нейросеть на C++ без внешних библиотек, обучение на CPU</span>
            <span class="en" style="display:none;">Neural network in C++ without external libraries, CPU training</span>
          </small><br>
          <img src="https://img.shields.io/badge/CPU-FF6B6B?style=flat-square&logo=intel&logoColor=white">
          <img src="https://img.shields.io/badge/Math-333333?style=flat-square&logo=wolfram&logoColor=white">
        </td>
        <td style="padding: 15px; border-bottom: 1px solid #30363d; transition: background 0.2s;" onmouseover="this.style.background='rgba(99,102,241,0.05)'" onmouseout="this.style.background='transparent'">
          <strong style="color: #c9d1d9; font-size: 16px;">🌐 LGTM Browser</strong><br>
          <small style="color: #8b949e;">
            <span class="ru">Браузер своего языка разметки LGTM на C#</span>
            <span class="en" style="display:none;">Browser for own markup language LGTM in C#</span>
          </small><br>
          <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white">
          <img src="https://img.shields.io/badge/WinForms-512BD4?style=flat-square&logo=dotnet&logoColor=white">
        </td>
      </tr>
    </table>
    
    <div style="margin-top: 15px; padding: 10px; background: rgba(99,102,241,0.05); border-radius: 8px; border-left: 3px solid #6366f1;">
      <span class="ru" style="color: #8b949e;">💡 <strong>Другие проекты:</strong> Gava Terminal, Gava VS Code Extension, Системные утилиты на C++</span>
      <span class="en" style="display:none; color: #8b949e;">💡 <strong>Other projects:</strong> Gava Terminal, Gava VS Code Extension, System utilities in C++</span>
    </div>
  </div>
  <div id="tech-card" style="
    background: linear-gradient(135deg, #161b22, #1a1f2e);
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 25px;
    margin-bottom: 25px;
    transition: all 0.3s ease;
    animation: fadeInUp 0.8s ease 0.6s both;
  " onmouseover="this.style.borderColor='#6366f1'; this.style.boxShadow='0 8px 30px rgba(99,102,241,0.1)'; this.style.transform='translateY(-2px)';" 
     onmouseout="this.style.borderColor='#30363d'; this.style.boxShadow='none'; this.style.transform='translateY(0)';">
    <h3 style="
      background: linear-gradient(135deg, #6366f1, #a78bfa);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-top: 0;
      font-size: 20px;
    ">
      💻 <span class="ru">Технологии</span><span class="en" style="display:none;">Tech Stack</span>
    </h3>
    <div align="center" style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center;">
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
      <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
      <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
      <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">
      <img src="https://img.shields.io/badge/WinAPI-0078D6?style=for-the-badge&logo=windows&logoColor=white">
    </div>
  </div>

  <!-- Контакты -->
  <div id="contacts-card" style="
    background: linear-gradient(135deg, #161b22, #1a1f2e);
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 25px;
    margin-bottom: 25px;
    transition: all 0.3s ease;
    animation: fadeInUp 0.8s ease 0.7s both;
  " onmouseover="this.style.borderColor='#6366f1'; this.style.boxShadow='0 8px 30px rgba(99,102,241,0.1)'; this.style.transform='translateY(-2px)';" 
     onmouseout="this.style.borderColor='#30363d'; this.style.boxShadow='none'; this.style.transform='translateY(0)';">
    <h3 style="
      background: linear-gradient(135deg, #6366f1, #a78bfa);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-top: 0;
      font-size: 20px;
    ">
      📫 <span class="ru">Контакты</span><span class="en" style="display:none;">Contacts</span>
    </h3>
    <div align="center" style="display: flex; gap: 15px; flex-wrap: wrap; justify-content: center;">
      <a href="mailto:mamkin-nagibator10000@yandex.ru" style="text-decoration: none; transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
      </a>
      <a href="https://t.me/S22822" style="text-decoration: none; transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
        <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white">
      </a>
      <a href="https://github.com/wassss337" style="text-decoration: none; transition: transform 0.2s;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
      </a>
    </div>
    <p align="center" style="color: #8b949e; margin-top: 15px;">
      <span class="ru">ВК и Скам — благо, нет.</span>
      <span class="en" style="display:none;">VK and Scam — thankfully, no.</span>
    </p>
  </div>
  <div align="center" style="margin-top: 30px;">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,14,18&height=100&section=footer">
  </div>
</div>

<style>
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<script>
  (function() {
    const root = document.getElementById('profile-root');
    let isDark = true;
    let isRu = true;

    window.toggleTheme = function() {
      isDark = !isDark;
      const bg = isDark ? '#0d1117' : '#ffffff';
      const surface = isDark ? 'linear-gradient(135deg, #161b22, #1a1f2e)' : 'linear-gradient(135deg, #f6f8fa, #ffffff)';
      const border = isDark ? '#30363d' : '#d0d7de';
      const text = isDark ? '#c9d1d9' : '#24292f';
      const secondary = isDark ? '#8b949e' : '#57606a';

      root.style.background = bg;
      root.style.color = text;
      document.querySelectorAll('#about-card, #projects-card, #tech-card, #contacts-card').forEach(card => {
        card.style.background = surface;
        card.style.borderColor = border;
      });
      document.querySelectorAll('small, .ru, .en').forEach(el => {
        if (!el.querySelector('strong')) el.style.color = secondary;
      });
      document.getElementById('themeBtn').innerHTML = isDark ? '🌓 Тема' : '☀️ Тема';
    };

    window.toggleLang = function() {
      isRu = !isRu;
      document.querySelectorAll('.ru').forEach(el => el.style.display = isRu ? '' : 'none');
      document.querySelectorAll('.en').forEach(el => el.style.display = isRu ? 'none' : '');
      document.getElementById('langBtn').innerHTML = isRu ? '🌐 EN' : '🌐 RU';
    };
  })();
</script>
