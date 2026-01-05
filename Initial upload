<!doctype html>
<html lang="en" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teachers Day Card</title>
  <script src="/_sdk/element_sdk.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      box-sizing: border-box;
    }
    
    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-20px); }
    }
    
    @keyframes sparkle {
      0%, 100% { opacity: 1; transform: scale(1); }
      50% { opacity: 0.5; transform: scale(0.8); }
    }
    
    .floating {
      animation: float 3s ease-in-out infinite;
    }
    
    .sparkle {
      animation: sparkle 2s ease-in-out infinite;
    }
    
    .card-shadow {
      box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full">
  <div id="card-container" class="w-full h-full overflow-auto flex items-center justify-center p-8">
   <div class="card-shadow rounded-3xl p-12 max-w-2xl w-full text-center relative overflow-hidden"><!-- Decorative elements -->
    <div class="absolute top-8 left-8 sparkle">
     <svg width="40" height="40" viewbox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 0L22.5 17.5L40 20L22.5 22.5L20 40L17.5 22.5L0 20L17.5 17.5L20 0Z" fill="currentColor" opacity="0.6" />
     </svg>
    </div>
    <div class="absolute top-8 right-8 sparkle" style="animation-delay: 0.5s;">
     <svg width="40" height="40" viewbox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 0L22.5 17.5L40 20L22.5 22.5L20 40L17.5 22.5L0 20L17.5 17.5L20 0Z" fill="currentColor" opacity="0.6" />
     </svg>
    </div><!-- Book Icon -->
    <div class="floating mb-8">
     <svg width="120" height="120" viewbox="0 0 120 120" fill="none" xmlns="http://www.w3.org/2000/svg" class="mx-auto"><rect x="20" y="25" width="80" height="70" rx="4" fill="currentColor" opacity="0.9" /> <rect x="25" y="30" width="70" height="60" rx="2" fill="white" /> <line x1="60" y1="30" x2="60" y2="90" stroke="currentColor" stroke-width="2" opacity="0.3" /> <line x1="35" y1="45" x2="55" y2="45" stroke="currentColor" stroke-width="2" stroke-linecap="round" opacity="0.5" /> <line x1="35" y1="55" x2="55" y2="55" stroke="currentColor" stroke-width="2" stroke-linecap="round" opacity="0.5" /> <line x1="35" y1="65" x2="55" y2="65" stroke="currentColor" stroke-width="2" stroke-linecap="round" opacity="0.5" /> <line x1="65" y1="45" x2="85" y2="45" stroke="currentColor" stroke-width="2" stroke-linecap="round" opacity="0.5" /> <line x1="65" y1="55" x2="85" y2="55" stroke="currentColor" stroke-width="2" stroke-linecap="round" opacity="0.5" /> <line x1="65" y1="65" x2="85" y2="65" stroke="currentColor" stroke-width="2" stroke-linecap="round" opacity="0.5" /> <!-- Apple on book --> <circle cx="60" cy="15" r="8" fill="#dc2626" /> <path d="M60 7 Q62 5, 64 7" stroke="#22c55e" stroke-width="1.5" fill="none" /> <ellipse cx="61" cy="13" rx="2" ry="3" fill="white" opacity="0.3" />
     </svg>
    </div><!-- Student Info -->
    <div class="mb-8">
     <h2 id="student-name" class="text-3xl font-bold mb-2"></h2>
     <p id="student-section" class="text-xl font-medium opacity-80"></p>
    </div><!-- Main Greeting -->
    <h1 id="main-greeting" class="text-6xl font-bold mb-6"></h1><!-- Message -->
    <div class="space-y-3 mb-8">
     <p id="message-line-1" class="text-2xl font-light"></p>
     <p id="message-line-2" class="text-2xl font-light"></p>
    </div><!-- Decorative line -->
    <div class="flex items-center justify-center mb-8">
     <div class="h-px w-16 opacity-30"></div><span class="mx-4 text-3xl">✨</span>
     <div class="h-px w-16 opacity-30"></div>
    </div><!-- Closing -->
    <p id="closing-message" class="text-xl font-medium italic"></p><!-- Bottom decorative elements -->
    <div class="absolute bottom-8 left-8 sparkle" style="animation-delay: 1s;">
     <svg width="40" height="40" viewbox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 0L22.5 17.5L40 20L22.5 22.5L20 40L17.5 22.5L0 20L17.5 17.5L20 0Z" fill="currentColor" opacity="0.6" />
     </svg>
    </div>
    <div class="absolute bottom-8 right-8 sparkle" style="animation-delay: 1.5s;">
     <svg width="40" height="40" viewbox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20 0L22.5 17.5L40 20L22.5 22.5L20 40L17.5 22.5L0 20L17.5 17.5L20 0Z" fill="currentColor" opacity="0.6" />
     </svg>
    </div>
   </div>
  </div>
  <script>
    const defaultConfig = {
      background_color: "#fef3c7",
      card_background: "#ffffff",
      primary_color: "#f59e0b",
      text_color: "#78350f",
      accent_color: "#dc2626",
      font_family: "Georgia",
      font_size: 16,
      student_name: "Johnrey P. Oliva",
      student_section: "BSIS-2B",
      main_greeting: "Belated Happy Teachers Day!",
      message_line_1: "Dear Sir Randy Bello,",
      message_line_2: "Thank you for being my teacher",
      closing_message: "With gratitude and respect"
    };

    async function onConfigChange(config) {
      const container = document.getElementById('card-container');
      const card = container.querySelector('div');
      const bookSvg = card.querySelector('svg:nth-of-type(3)');
      const decorativeLines = card.querySelectorAll('.h-px');
      const sparkles = card.querySelectorAll('.sparkle svg');
      
      // Apply colors
      container.style.background = config.background_color || defaultConfig.background_color;
      card.style.background = config.card_background || defaultConfig.card_background;
      
      bookSvg.style.color = config.primary_color || defaultConfig.primary_color;
      
      sparkles.forEach(sparkle => {
        sparkle.style.color = config.primary_color || defaultConfig.primary_color;
      });
      
      decorativeLines.forEach(line => {
        line.style.background = config.text_color || defaultConfig.text_color;
      });
      
      // Apply font
      const customFont = config.font_family || defaultConfig.font_family;
      const baseFontStack = 'Georgia, serif';
      const fontFamily = ${customFont}, ${baseFontStack};
      
      // Apply font size
      const baseSize = config.font_size || defaultConfig.font_size;
      
      const studentName = document.getElementById('student-name');
      studentName.textContent = config.student_name || defaultConfig.student_name;
      studentName.style.color = config.text_color || defaultConfig.text_color;
      studentName.style.fontFamily = fontFamily;
      studentName.style.fontSize = ${baseSize * 1.875}px;
      
      const studentSection = document.getElementById('student-section');
      studentSection.textContent = config.student_section || defaultConfig.student_section;
      studentSection.style.color = config.text_color || defaultConfig.text_color;
      studentSection.style.fontFamily = fontFamily;
      studentSection.style.fontSize = ${baseSize * 1.25}px;
      
      const mainGreeting = document.getElementById('main-greeting');
      mainGreeting.textContent = config.main_greeting || defaultConfig.main_greeting;
      mainGreeting.style.color = config.text_color || defaultConfig.text_color;
      mainGreeting.style.fontFamily = fontFamily;
      mainGreeting.style.fontSize = ${baseSize * 3.75}px;
      
      const messageLine1 = document.getElementById('message-line-1');
      messageLine1.textContent = config.message_line_1 || defaultConfig.message_line_1;
      messageLine1.style.color = config.text_color || defaultConfig.text_color;
      messageLine1.style.fontFamily = fontFamily;
      messageLine1.style.fontSize = ${baseSize * 1.5}px;
      
      const messageLine2 = document.getElementById('message-line-2');
      messageLine2.textContent = config.message_line_2 || defaultConfig.message_line_2;
      messageLine2.style.color = config.text_color || defaultConfig.text_color;
      messageLine2.style.fontFamily = fontFamily;
      messageLine2.style.fontSize = ${baseSize * 1.5}px;
      
      const closingMessage = document.getElementById('closing-message');
      closingMessage.textContent = config.closing_message || defaultConfig.closing_message;
      closingMessage.style.color = config.primary_color || defaultConfig.primary_color;
      closingMessage.style.fontFamily = fontFamily;
      closingMessage.style.fontSize = ${baseSize * 1.25}px;
    }

    function mapToCapabilities(config) {
      return {
        recolorables: [
          {
            get: () => config.background_color || defaultConfig.background_color,
            set: (value) => {
              config.background_color = value;
              window.elementSdk.setConfig({ background_color: value });
            }
          },
          {
            get: () => config.card_background || defaultConfig.card_background,
            set: (value) => {
              config.card_background = value;
              window.elementSdk.setConfig({ card_background: value });
            }
          },
          {
            get: () => config.primary_color || defaultConfig.primary_color,
            set: (value) => {
              config.primary_color = value;
              window.elementSdk.setConfig({ primary_color: value });
            }
          },
          {
            get: () => config.text_color || defaultConfig.text_color,
            set: (value) => {
              config.text_color = value;
              window.elementSdk.setConfig({ text_color: value });
            }
          }
        ],
        borderables: [],
        fontEditable: {
          get: () => config.font_family || defaultConfig.font_family,
          set: (value) => {
            config.font_family = value;
            window.elementSdk.setConfig({ font_family: value });
          }
        },
        fontSizeable: {
          get: () => config.font_size || defaultConfig.font_size,
          set: (value) => {
            config.font_size = value;
            window.elementSdk.setConfig({ font_size: value });
          }
        }
      };
    }

    function mapToEditPanelValues(config) {
      return new Map([
        ["student_name", config.student_name || defaultConfig.student_name],
        ["student_section", config.student_section || defaultConfig.student_section],
        ["main_greeting", config.main_greeting || defaultConfig.main_greeting],
        ["message_line_1", config.message_line_1 || defaultConfig.message_line_1],
        ["message_line_2", config.message_line_2 || defaultConfig.message_line_2],
        ["closing_message", config.closing_message || defaultConfig.closing_message]
      ]);
    }

    // Initialize immediately with default config
    onConfigChange(defaultConfig);
    
    window.elementSdk.init({
      defaultConfig,
      onConfigChange,
      mapToCapabilities,
      mapToEditPanelValues
    });
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9b9501a4f38edd57',t:'MTc2NzYzNzQwMi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
