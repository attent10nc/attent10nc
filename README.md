<p align="center">
  <img src="assets/header.svg" alt="attent10nc" width="100%">
</p>

<p align="center">
  <a href="https://github.com/attent10nc/YMusicMod"><img src="https://img.shields.io/badge/флагман-YMusicMod-ff2f7a?style=flat-square&labelColor=1a0d10" alt="YMusicMod"></a>
  <a href="https://attent10nc.github.io/YMusicMod/"><img src="https://img.shields.io/badge/сайт-attent10nc.github.io-a14dff?style=flat-square&labelColor=1a0d10" alt="site"></a>
  <img src="https://komarev.com/ghpvc/?username=attent10nc&style=flat-square&color=ff5a4e&label=просмотры" alt="views">
</p>

### Привет 👋

Делаю софт, который хочется поставить себе: моды для десктопных приложений, Telegram-ботов и мини-аппы, игры в Roblox, инструменты для Dota 2.
Довожу до релиза: установщик в один клик, автосборка в CI, обновления без ручной возни.

- 🎧 Сейчас развиваю **YMusicMod**, кастомизацию Яндекс Музыки для Windows
- 🎮 Веду живую игру в Roblox, **SMILE: CHAOS TYCOON**
- 🤖 Пишу Telegram-ботов на aiogram, от простых рассылок до Mini App с бэкендом на Django
- 🛠 Интересно всё, где нужно залезть внутрь чужого приложения и аккуратно его улучшить

---

## ⭐ YMusicMod

<a href="https://github.com/attent10nc/YMusicMod">
  <img src="https://raw.githubusercontent.com/attent10nc/YMusicMod/main/docs/img/banner.png" alt="YMusicMod" width="100%">
</a>

<p>
  <a href="https://github.com/attent10nc/YMusicMod/releases/latest"><img src="https://img.shields.io/github/v/release/attent10nc/YMusicMod?style=for-the-badge&color=ff2f7a&labelColor=1a0d10&label=%D1%80%D0%B5%D0%BB%D0%B8%D0%B7" alt="release"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-a14dff?style=for-the-badge&labelColor=1a0d10&logo=windows11&logoColor=white" alt="windows">
  <img src="https://img.shields.io/badge/Electron-asar%20patch-ff5a4e?style=for-the-badge&labelColor=1a0d10&logo=electron&logoColor=white" alt="electron">
</p>

Видео-обои, цвет интерфейса из обложки, визуализатор под бит, мини-плеер поверх игр и статус в Discord.
Ставится одним `Setup.exe` и сам возвращается после обновлений Яндекс Музыки.

**Под капотом:** патч `app.asar` без привязки к версии приложения, свой протокол для мини-плеера, перехват аудио через `captureStream()` для анализа спектра, установщик на C# с фоновым сторожем обновлений, сборка exe в GitHub Actions.

[**Скачать**](https://github.com/attent10nc/YMusicMod/releases/latest) · [Сайт проекта](https://attent10nc.github.io/YMusicMod/) · [Исходники](https://github.com/attent10nc/YMusicMod)

---

## 🧩 Другие проекты

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>😁 SMILE: CHAOS TYCOON</h3>
      <p>Тайкун в Roblox с бэкрумс-районами, бейджами, геймпассами и рефералками. Переведён на 13 языков, открыт для всех.</p>
      <p>
        <img src="https://img.shields.io/badge/Luau-00A2FF?style=flat-square&logo=roblox&logoColor=white" alt="Luau">
        <img src="https://img.shields.io/badge/Rojo-1a0d10?style=flat-square" alt="Rojo">
      </p>
      <a href="https://www.roblox.com/games/123213847310833"><b>Играть →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>📊 Tukowka Tracker</h3>
      <p>Telegram Mini App для разбора матчей Dota 2: статистика, графики, советы по игре. Бэкенд, фронт и бот покрыты тестами (260+).</p>
      <p>
        <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
        <img src="https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
        <img src="https://img.shields.io/badge/aiogram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="aiogram">
      </p>
      <i>Приватный репозиторий</i>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📡 ThreatRadar</h3>
      <p>Мониторинг сетевых угроз: захват пакетов, оценка рисков и дашборд с картой сети.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/Scapy-1a0d10?style=flat-square" alt="Scapy">
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
      </p>
      <a href="https://github.com/attent10nc/ThreatRadar"><b>Репозиторий →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🔎 Network Audit Tool</h3>
      <p>Обёртка над Nmap: шесть режимов сканирования, понятные отчёты, интерфейс на русском и английском.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/Nmap-1a0d10?style=flat-square" alt="Nmap">
      </p>
      <a href="https://github.com/attent10nc/network-audit-tool"><b>Репозиторий →</b></a>
    </td>
  </tr>
</table>

---

## 🛠 Стек

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/JavaScript-1a0d10?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Luau-00A2FF?style=for-the-badge&logo=roblox&logoColor=white" alt="Luau">
</p>
<p>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron">
  <img src="https://img.shields.io/badge/aiogram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="aiogram">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
</p>
<p>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux%20%2F%20systemd-1a0d10?style=for-the-badge&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/Roblox%20Studio-00A2FF?style=for-the-badge&logo=roblox&logoColor=white" alt="Roblox Studio">
</p>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/attent10nc/attent10nc/output/snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/attent10nc/attent10nc/output/snake.svg">
    <img alt="змейка по контрибуциям" src="https://raw.githubusercontent.com/attent10nc/attent10nc/output/snake-dark.svg">
  </picture>
</p>
