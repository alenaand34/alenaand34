# Привет, меня зовут Алена!

---

### 👨‍💻 Обо мне:

Я начинающий специалист по тестированию. Недавно я завершила курс «Junior» Артема Русова, где получила теоретические знания и практические навыки в функциональном тестировании веб- и мобильных приложений, API и работе с базами данных. 

Ищу возможность применить свои знания в реальных проектах и развиваться в сфере тестирования.

- 📫 Как связаться со мной: [![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=Gmail&logoColor=white)](mailto:anduminaa@gmail.com)

---

### 🤝 Социальные сети:

<div id="badges">
    <a href="https://t.me/alenaandumina" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="40" height="40" alt="telegram" />
    </a>
</div>

---

### Инструметы для тестирования


<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Композиция в форме T</title>
<style>
  body {
    background-color: #f0f0f0; /* Светлый фон для контраста */
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
  }
  .t-shape-composition {
    display: grid;
    /* 5 колонок для горизонтальной части, каждая шириной 40px */
    grid-template-columns: repeat(5, 40px);
    gap: 10px; /* Расстояние между иконками */
    justify-content: center; /* Центрирование всей сетки */
  }

  .t-shape-composition img {
    width: 40px;
    height: 40px;
    object-fit: contain; /* Сохранение пропорций иконок */
  }

  /* --- Размещение иконок --- */

  /* Горизонтальная перекладина буквы 'T' (1-й ряд) */
  .t-shape-composition img:nth-child(1) { grid-column: 1; grid-row: 1; }
  .t-shape-composition img:nth-child(2) { grid-column: 2; grid-row: 1; }
  .t-shape-composition img:nth-child(3) { grid-column: 3; grid-row: 1; }
  .t-shape-composition img:nth-child(4) { grid-column: 4; grid-row: 1; }
  .t-shape-composition img:nth-child(5) { grid-column: 5; grid-row: 1; }

  /* Вертикальная ножка буквы 'T' (3-я колонка, со 2-го ряда) */
  .t-shape-composition img:nth-child(6) { grid-column: 3; grid-row: 2; }
  .t-shape-composition img:nth-child(7) { grid-column: 3; grid-row: 3; }
  .t-shape-composition img:nth-child(8) { grid-column: 3; grid-row: 4; }
  .t-shape-composition img:nth-child(9) { grid-column: 3; grid-row: 5; }
  .t-shape-composition img:nth-child(10) { grid-column: 3; grid-row: 6; }
  .t-shape-composition img:nth-child(11) { grid-column: 3; grid-row: 7; }
  .t-shape-composition img:nth-child(12) { grid-column: 3; grid-row: 8; }
  .t-shape-composition img:nth-child(13) { grid-column: 3; grid-row: 9; }
  .t-shape-composition img:nth-child(14) { grid-column: 3; grid-row: 10; }
  .t-shape-composition img:nth-child(15) { grid-column: 3; grid-row: 11; }
</style>
</head>
<body>

<div class="t-shape-composition">
  <!-- 1. Горизонтальная часть -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/YouTrack_Icon.svg/1024px-YouTrack_Icon.svg.png" title="YouTrack" alt="YouTrack"/>
  <img src="https://codahosted.io/packs/21236/unversioned/assets/LOGO/ba1091c59bab89cd2fd0f289622731fe16113d7b00905abe64759c313a4b73b76c1b0426076ed76cb74752234c734131df46992d5b8b48fc13e264240e4f7119f736cfeb64df36ded54b5cbf6198b9cadedf18dd0cac5c7dbcd16e6336c29363cd1292ba" title="TestRail" alt="TestRail"/>
  <img src="https://luna1.co/eb0187.png" title="Qase" alt="Qase"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" title="Figma" alt="Figma"/>
  <img src="https://d33wubrfki0l68.cloudfront.net/38b5c953a4667366685d55db55d057c86db1fc54/a0fdc/static/acae6b24d940347661ca901ea07f47c1/chrome-dev-logo-icon.png" title="DevTools" alt="DevTools"/>
  
  <!-- 2. Вертикальная часть -->
  <img src="https://static0.smartbear.co/smartbearbrand/media/images/home/soapui-icon.svg" title="SoapUI" alt="SoapUI"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" title="Android Studio" alt="Android Studio"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/xcode/xcode-original.svg" title="Xcode" alt="Xcode"/>
  <img src="https://cdn.icon-icons.com/icons2/3053/PNG/512/charles_proxy_macos_bigsur_icon_190302.png" title="Charles Proxy" alt="Charles Proxy"/>
  <img src="https://www.megaleechers.com/storage/Fiddler-Everywhere-Icon.png" title="Fiddler" alt="Fiddler"/>
  <img src="https://pbs.twimg.com/profile_images/1589614420766126080/slAIVDtr_400x400.jpg" title="Proxyman" alt="Proxyman"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" title="MySQL" alt="MySQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" title="MongoDB" alt="MongoDB"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title="Git" alt="Git"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/Bash_Logo_Colored.svg/1024px-Bash_Logo_Colored.svg.png" title="Bash" alt="Bash"/>
</div>

</body>
</html>


