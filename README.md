<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=1e293b&text=Dangel%20GitHub&fontSize=60&fontAlign=50&fontAlignY=35&desc=Malware%20Analysis%20|%20Reverse%20Engineering%20|%20Security%20Researcher&descAlign=50&descAlignY=80&fontColor=ffffff" style="max-width: 100%; height: auto;" />

<!-- 🔍 EASTER EGG #1: View page source (Ctrl+U) to see this hidden message! -->
<!-- SHA-256: e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->
<!-- MD5: d41d8cd98f00b204e9800998ecf8427e -->
<!-- Congratulations! You found the first easter egg. True analysts always read the source code. -->
<!-- "In the world of malware analysis, curiosity is your greatest weapon." - Dangel -->

```
┌──────────────────────────────────────────────────────────────────────────────┐
│ [SYSTEM] Initializing Analysis Environment...                               │
│ [SYSTEM] Loading IDA Pro v8.3... ███████████████████████ 100%              │
│ [SYSTEM] Decompiling Binary... Success                                      │
│ [SYSTEM] Sandbox Environment Initialized                                    │
│ [WARNING] Ransomware Behavior Detected!                                     │
│ [INFO] Extracting Strings from Memory...                                    │
│ [INFO] Anti-VM Check: PASSED                                               │
│ [SUCCESS] Decrypting Payload... Complete                                    │
│ [INFO] Analyzing API Calls... CreateMutexW, RegSetValueExW                 │
│ [SUCCESS] Generating YARA Rule... Done                                      │
└──────────────────────────────────────────────────────────────────────────────┘
```

**[ANALYSIS_REPORT]** `Threat_Level: CRITICAL` | `IOC: 0xDEADC0DE`

**Indicators:** Strings: "Anti-VM", "Persistence", "ScheduledTask" | Behavior: Keylogger, Screenshot

<details>
<summary>🔍 Click to reveal hidden analysis data (Easter Egg #2)</summary>

<br>

```diff
! ═══════════════════════════════════════════════════════════════════
! CLASSIFIED MALWARE ANALYSIS REPORT - ANALYST EYES ONLY
! ═══════════════════════════════════════════════════════════════════
+ File Hash (SHA-256):
+ e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
! 
+ File Hash (MD5): 
+ d41d8cd98f00b204e9800998ecf8427e
! 
- Detection Rate: 47/71 Vendors (VirusTotal)
- First Seen: 2026-01-29 10:47:05 UTC
! 
+ YARA Rule Match: Dangel_Ransomware_v2
+ C2 Server: 45.67.89.123:8080
+ Encryption: AES-256-CBC + RSA-2048
! 
! ═══════════════════════════════════════════════════════════════════
+ 🎯 Congratulations! You found Easter Egg #2!
+ You are a true analyst. Keep digging deeper...
! ═══════════════════════════════════════════════════════════════════
```

**Persistence Mechanism:**
```registry
HKCU\Software\Microsoft\Windows\CurrentVersion\Run
Value: "SecurityUpdate" = "C:\Users\Public\svchost.exe"
```

**Network Indicators:**
- C2 Domain: `malicious-c2-server[.]onion`
- User-Agent: `Mozilla/5.0 (Windows NT 10.0; Win64; x64) DangelBot/1.0`

**MITRE ATT&CK Techniques:**
- T1486: Data Encrypted for Impact
- T1547.001: Registry Run Keys / Startup Folder
- T1071.001: Application Layer Protocol: Web Protocols

</details>

<sub>💡 **Analyst Tip:** Try viewing the page source (Ctrl+U) for more hidden messages...</sub>

---

  <h2>🛠️ Tech Stack</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 5px;">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
    <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
    <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
    <img src="https://img.shields.io/badge/Haxe-EA8220?style=for-the-badge&logo=haxe&logoColor=white"/>
    <img src="https://img.shields.io/badge/Web_Hacking-4CAF50?style=for-the-badge"/>
  </div>

  <h2>🏆 Awards</h2>
  <table style="width: 100%; max-width: 850px; border-collapse: collapse; text-align: left; background-color: #0d1117; color: #c9d1d9; border: 1px solid #30363d;">
    <thead>
      <tr style="border-bottom: 2px solid #30363d; background-color: #161b22;">
        <th style="padding: 12px; width: 10%;">Date</th>
        <th style="padding: 12px; width: 25%;">Award Name</th>
        <th style="padding: 12px; width: 20%;">Team</th>
        <th style="padding: 12px; width: 20%;">Item</th>
        <th style="padding: 12px; width: 15%;">Result</th>
        <th style="padding: 12px; width: 10%; text-align: center;">Evidence</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px;">2025.12</td>
        <td style="padding: 12px;"><b>2025 직업계고 창업아이템 공모전 (전국)</b></td>
        <td style="padding: 12px;">FUN FUN한 녀석들</td>
        <td style="padding: 12px; color: #58a6ff;">자율주행 잔디깎기</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/1st-최우수-FFD700?style=flat-square&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center;"><img src="https://github.com/user-attachments/assets/b8c328f7-c2b0-4b83-9187-3be0d3e8ba66" width="45" style="border-radius: 3px;" /></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px;">2025.11</td>
        <td style="padding: 12px;"><b>2025년 전주 IP 마이스터 대회</b></td>
        <td style="padding: 12px;">JTHS_makes</td>
        <td style="padding: 12px; color: #58a6ff;">커피 씨앗컵 시뮬레이터</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/Award-참가상-gray?style=flat-square&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center;"><img src="https://github.com/user-attachments/assets/0fd52b6b-46a8-45a8-bcda-09afb4a63027" width="45" style="border-radius: 3px;" /></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px;">2025.10</td>
        <td style="padding: 12px;"><b>전주 사회적 기업 박람회</b></td>
        <td style="padding: 12px;">FUN FUN한 녀석들</td>
        <td style="padding: 12px; color: #58a6ff;">자율주행 잔디깎기</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/2nd-우수-C0C0C0?style=flat-square&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.2em;"><a href="https://www.eroun.net/news/articleView.html?idxno=65595" style="text-decoration: none;">📰</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px;">2025</td>
        <td style="padding: 12px;"><b>프로그래밍 교과 우수상</b><br/><span style="color: #8b949e; font-size: 0.8em;">전주공업고등학교</span></td>
        <td style="padding: 12px;">-</td>
        <td style="padding: 12px; color: #8b949e;">-</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/Academic-Excellence-58a6ff?style=flat-square&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center;">-</td>
      </tr>
    </tbody>
  </table>

  <h2>🚀 Projects</h2>
  <h3>🏅 Competition Project</h3>
  <table style="width: 100%; max-width: 850px; border-collapse: collapse; text-align: left; background-color: #0d1117; color: #c9d1d9; border: 1px solid #30363d;">
    <thead>
      <tr style="border-bottom: 2px solid #30363d; background-color: #161b22;">
        <th style="padding: 12px; width: 25%;">Project Name</th>
        <th style="padding: 12px; width: 35%;">Short Summary</th>
        <th style="padding: 12px; width: 20%;">Tech Stack</th>
        <th style="padding: 12px; width: 10%; text-align: center;">Code</th>
        <th style="padding: 12px; width: 10%; text-align: center;">View</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">🚜 자율주행 잔디깎기 자동차</td>
        <td style="padding: 12px; font-size: 0.9em;">초음파/적외선 센서 기반 장애물 인식 및 임베디드 시스템 설계</td>
        <td style="padding: 12px;">
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
          <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white"/>
        </td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://github.com/Dangel165/Raspberry-Pi-autonomous-lawn-mower" style="text-decoration: none;">📁</a></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224139940765" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">🏎️ 자율주행 자동차 시뮬레이션</td>
        <td style="padding: 12px; font-size: 0.9em;">A* 알고리즘을 활용한 최적 경로 탐색 및 장애물 회피 로직 구현</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://github.com/Dangel165/AI-autonomous-driving-simulator" style="text-decoration: none;">📁</a></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224143139997" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">🌱 커피 씨앗컵 시뮬레이터</td>
        <td style="padding: 12px; font-size: 0.9em;">친환경 커피 씨앗컵 메커니즘 설명을 위한 시뮬레이션 환경 구축</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://github.com/Dangel165/Biodegradable-Coffee-Cup-Seed-Growth-Simulation-Hackathon-competition-" style="text-decoration: none;">📁</a></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;">-</td>
      </tr>
    </tbody>
  </table>

  <h3>💡 General Projects</h3>
  <table style="width: 100%; max-width: 850px; border-collapse: collapse; text-align: left; background-color: #0d1117; color: #c9d1d9; border: 1px solid #30363d;">
    <thead>
      <tr style="border-bottom: 2px solid #30363d; background-color: #161b22;">
        <th style="padding: 12px; width: 25%;">Project Name</th>
        <th style="padding: 12px; width: 35%;">Short Summary</th>
        <th style="padding: 12px; width: 20%;">Tech Stack</th>
        <th style="padding: 12px; width: 10%; text-align: center;">Code</th>
        <th style="padding: 12px; width: 10%; text-align: center;">View</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">🎮 [JavaScript] AI 술래잡기</td>
        <td style="padding: 12px; font-size: 0.9em;">진화 DNA 기반의 도망자-술래 협력 및 생존 시뮬레이션 시스템 구현</td>
        <td style="padding: 12px;">
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/><br/>
          <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
        </td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://github.com/Dangel165/AI-playing-tag" style="text-decoration: none;">📁</a></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224148370659" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">🧩 백준 문제풀이 해설</td>
        <td style="padding: 12px; font-size: 0.9em;">다양한 알고리즘 유형 분석 및 자료구조를 활용한 최적화 풀이 기록</td>
        <td style="padding: 12px;">
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
          <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/><br/>
          <img src="https://img.shields.io/badge/Haxe-EA8220?style=flat-square&logo=haxe&logoColor=white"/>
        </td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;">-</td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224138618178" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">🤖 산업용 협동로봇 코딩</td>
        <td style="padding: 12px; font-size: 0.9em;">레인보우로보틱스 협동로봇 연동 및 동작 제어 시나리오 구현</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 0.8em; color: #8b949e;">Private</td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;">-</td>
      </tr>
    </tbody>
  </table>

  <h2>🔍 Malware Analysis</h2>
  <table style="width: 100%; max-width: 850px; border-collapse: collapse; text-align: left; background-color: #0d1117; color: #c9d1d9; border: 1px solid #30363d;">
    <thead>
      <tr style="border-bottom: 2px solid #30363d; background-color: #161b22;">
        <th style="padding: 12px; width: 30%;">Title</th>
        <th style="padding: 12px; width: 40%;">Summary</th>
        <th style="padding: 12px; width: 18%;">Tech Stack</th>
        <th style="padding: 12px; width: 12%; text-align: center;">View</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">[Python 악성코드 분석] Discord RAT 분석</td>
        <td style="padding: 12px; font-size: 0.9em;">PySilon 기반 RAT의 동작 원리 및 디스코드 봇 제어 위협 분석</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224145653930" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">[C# 악성코드 분석] RSA-2048 하이브리드 암호화 분석</td>
        <td style="padding: 12px; font-size: 0.9em;">디스코드 토큰 추출 및 AES-RSA 하이브리드 암호화 체계 분석</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224134443176" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">[C# 악성코드 분석] 마인크래프트 위장 랜섬웨어 (1, 2편)</td>
        <td style="padding: 12px; font-size: 0.9em;">사회 공학 기법 기반 랜섬웨어 침투 과정 분석 및 복구 툴 제작 원리 연구</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224137239220" style="text-decoration: none;">📝</a></td>
      </tr>
    </tbody>
  </table>

  <h2>🛡️ Security Program Development</h2>
  <table style="width: 100%; max-width: 850px; border-collapse: collapse; text-align: left; background-color: #0d1117; color: #c9d1d9; border: 1px solid #30363d;">
    <thead>
      <tr style="border-bottom: 2px solid #30363d; background-color: #161b22;">
        <th style="padding: 12px; width: 30%;">Title</th>
        <th style="padding: 12px; width: 40%;">Summary</th>
        <th style="padding: 12px; width: 10%;">Tech Stack</th>
        <th style="padding: 12px; width: 10%; text-align: center;">Code</th>
        <th style="padding: 12px; width: 10%; text-align: center;">View</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">[C++,Python] 백신 프로그램 (InfraRed)</td>
        <td style="padding: 12px; font-size: 0.9em;">정교한 탐지 로직을 갖춘 자체 백신 엔진 설계 및 구현</td>
        <td style="padding: 12px;">
          <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/><br/>
          <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        </td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://github.com/Dangel165/InfraRed-V2.0" style="text-decoration: none;">📁</a></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224149617921" style="text-decoration: none;">📝</a></td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 12px; font-weight: bold; color: #58a6ff;">[Python] YARA 자동 생성기</td>
        <td style="padding: 12px; font-size: 0.9em;">악성코드 샘플 분석 및 탐지 효율화를 위한 자동화 툴 개발</td>
        <td style="padding: 12px;"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://github.com/Dangel165/YARA-automatic-generator" style="text-decoration: none;">📁</a></td>
        <td style="padding: 12px; text-align: center; font-size: 1.5em;"><a href="https://blog.naver.com/dangel798/224147017227" style="text-decoration: none;">📝</a></td>
      </tr>
    </tbody>
  </table>

  <h2>🏢 Organizations</h2>
  <table style="width: 100%; max-width: 850px; border-collapse: collapse; text-align: left; background-color: #0d1117; color: #c9d1d9; border: 1px solid #30363d;">
    <tbody>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 15px;">
          <b style="color: #58a6ff; font-size: 1.1em;">🚀 메이커 스페이스 창업 동아리</b> (2024.05 ~ 2025.12)<br/>
          <span style="font-size: 0.9em; color: #8b949e;">전주공업고등학교 | 시제품 제작 및 기술 창업 활동</span>
        </td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 15px;">
          <b style="color: #58a6ff; font-size: 1.1em;">🦾 레인보우로보틱스 산학 협력</b> (2025.03 ~ 2025.11)<br/>
          <span style="font-size: 0.9em; color: #8b949e;">산업용 협동로봇 제어 기술 교육 이수</span>
        </td>
      </tr>
      <tr style="border-bottom: 1px solid #30363d;">
        <td style="padding: 15px;">
          <b style="color: #58a6ff; font-size: 1.1em;">💻 전주교육대학교 영재교육원</b> (2018.03 ~ 2018.10)<br/>
          <span style="font-size: 0.9em; color: #8b949e;">소프트웨어 영재 과정 수료</span>
        </td>
      </tr>
    </tbody>
  </table>

  <h2>📖 Studies</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 5px;">
    <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
    <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white"/>
    <img src="https://img.shields.io/badge/Assembly-2E3A59?style=for-the-badge&logo=assemblyscript&logoColor=white"/>
    <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
    <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
    <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
    <img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white"/>
    <img src="https://img.shields.io/badge/Cryptography-9C27B0?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Forensics-00BCD4?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/Reversing-FF5722?style=for-the-badge"/>
  </div>

  <h2>🧰 Tools </h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 5px;">
    <img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white"/>
    <img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
    <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white"/>
    <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white"/>
    <img src="https://img.shields.io/badge/RustRover-000000?style=for-the-badge&logo=rustrover&logoColor=white"/>
    <img src="https://img.shields.io/badge/CLion-000000?style=for-the-badge&logo=clion&logoColor=white"/>
    <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/>
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
    <img src="https://img.shields.io/badge/Open MV-E8314F?style=for-the-badge&logo=openmv&logoColor=white"/>
  </div>

  <h2>🖥️ Linux & 📟 Embedded</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 5px;">
    <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white"/>
    <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>
    <img src="https://img.shields.io/badge/Raspbian-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white"/>
    <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
    <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  </div>

  <h2>📊 Statistics</h2>
  <div style="display: flex; justify-content: center; align-items: flex-start; gap: 10px;">
    <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Dangel165&layout=compact&theme=algolia" alt="Top Langs" height="165" />
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=fff20ok" alt="Solved.ac Badge" height="165" />
  </div>

  <h2>🔗 Links</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 5px;">
    <a href="https://blog.naver.com/dangel798"><img src="https://img.shields.io/badge/Naver_Blog-03C75A?style=for-the-badge&logo=naver&logoColor=white"/></a>
    <a href="https://dreamhack.io/users/88375"><img src="https://img.shields.io/badge/Dreamhack-FFC107?style=for-the-badge&logo=target&logoColor=black"/></a>
    <a href="https://solved.ac/profile/fff20ok"><img src="https://img.shields.io/badge/Baekjoon-0076BA?style=for-the-badge&logo=notion&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/moonbird6748-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
    <a href="https://instagram.com/dangel3190"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
  </div>
</div>
