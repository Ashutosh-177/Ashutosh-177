<div align="center">

<!-- Header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=2800&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Ashutosh+Kumar+Singh;Software+%C2%B7+Embedded+%C2%B7+Robotics;Open+Source+Contributor+%C2%B7+Patent+Holder" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashutosh-kumar-singh-255506287/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ashutoshkumarsingh1067@gmail.com)
![Views](https://komarev.com/ghpvc/?username=Ashutosh-177&color=00d4ff&style=flat-square&label=Views)

</div>

---

### About

Engineer who works across the full stack — from browser UIs to bare-metal firmware and autonomous robots.

I build **web applications** (JavaScript, PHP, Python), **embedded systems** (C/C++, ATmega, ESP32), and **robotic platforms** (ROS2, LiDAR, Jetson Nano). I care about systems that are practical, reliable, and well-engineered end-to-end.

- 🎓 B.Tech in ICT (VLSI & Embedded Systems) @ Marwadi University — CGPA 8.42
- 🔬 Research Intern @ DRDO · Published in DRDO Technology Focus (Jan 2026)
- 📜 Patent Holder — LPG Cylinder Monitoring & Leak Alert System (No. 202421033238)
- 🌐 Open source contributor to **aiohttp** and **Memori**

---

### Tech

<div align="center">

**Languages** &nbsp;&nbsp; ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Web** &nbsp;&nbsp; ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Robotics & AI** &nbsp;&nbsp; ![ROS2](https://img.shields.io/badge/-ROS2-22314E?style=flat-square&logo=ros&logoColor=white) ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Jetson](https://img.shields.io/badge/-Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white) ![ML](https://img.shields.io/badge/-ML-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Hardware** &nbsp;&nbsp; ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![RPi](https://img.shields.io/badge/-Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white) ![ESP](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![AVR](https://img.shields.io/badge/-ATmega%2FAVR-1E90FF?style=flat-square)

</div>

---

### 🌐 Open Source Contributions

> Merged pull requests fixing real bugs in widely-used Python libraries.

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">Contribution</th>
    <th align="center">Status</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/aio-libs/aiohttp/pull/12674"><b>aiohttp</b></a><br/>
      <sub>Async HTTP client/server for Python</sub>
    </td>
    <td>
      Fixed <code>ZLibDecompressor</code> silently truncating responses with concatenated
      gzip members. Implemented multi-member decompression that honors <code>max_length</code>
      across the stream, added a typed decompressor protocol and regression tests.
      <br/><sub>Fixes <a href="https://github.com/aio-libs/aiohttp/issues/7157">#7157</a></sub>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Merged-8957e5?style=flat-square&logo=github&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/MemoriLabs/Memori/pull/537"><b>Memori</b></a><br/>
      <sub>Memory engine for AI agents</sub>
    </td>
    <td>
      Fixed async API methods ignoring the configured request timeout (hardcoded 30s).
      Routed all async calls through <code>Config.request_secs_timeout</code> and added
      unit tests asserting the timeout is forwarded correctly.
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Merged-8957e5?style=flat-square&logo=github&logoColor=white"/>
    </td>
  </tr>
</table>

---

### Projects

| Project | What it does | Built with |
|:--------|:-------------|:-----------|
| **[Autonomous Mobile Robot](https://github.com/Ashutosh-177/ROS2-Maze_Robot)** | Full robotic platform — perception, navigation, sim-to-real deployment | ROS2 · Jetson Nano · LiDAR · Gazebo |
| **[ManTarang — Music Recommendation](https://github.com/Ashutosh-177/ManTarang-AI-Powered-Music-Recommendation-System)** | AI-powered song emotion recognition & recommendation over a 1M-song dataset | Python · ML · Librosa · HuggingFace |
| **[RentCollect — Rental Management](https://github.com/Ashutosh-177/Rental-Management-Application)** | Full-stack tenant platform with auth, rent tracking, and analytics | React · Node.js · MongoDB |
| **Gas Leakage Detection** *(Patented)* | Real-time embedded LPG detection with automated alerts | ESP32 · NodeMCU · Gas/Load Sensors |
| **Sound-Activated Control** | Event-driven system with IMU-based response triggered by sound | ATmega32 · MPU6050 · Embedded C |
| **RF Wireless Load Control** | Wireless electrical load switching via encoder–decoder RF | HT12E/D · 433 MHz · Relays |

---

### GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Ashutosh-177&show_icons=true&hide_border=true&title_color=00D4FF&icon_color=00D4FF&text_color=c9d1d9&bg_color=0d1117" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ashutosh-177&layout=compact&hide_border=true&title_color=00D4FF&text_color=c9d1d9&bg_color=0d1117" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Ashutosh-177&hide_border=true&background=0d1117&stroke=00D4FF&ring=00D4FF&fire=00D4FF&currStreakLabel=00D4FF&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" />

</div>

---

### Currently Working On

- Autonomous robotics — sim-to-real with ROS2 and multi-sensor fusion
- ML integration into web applications
- Embedded system design and VLSI fundamentals
- DSA and competitive programming

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashutosh-kumar-singh-255506287/)
[![Email](https://img.shields.io/badge/Get_in_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashutoshkumarsingh1067@gmail.com)

<sub>Silicon to software — building systems that work.</sub>

</div>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=Ashutosh-177&color=00d4ff&style=for-the-badge&label=PROFILE+VIEWS"/>
