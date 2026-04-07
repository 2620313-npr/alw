<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>우승연 / alway go -- 몰입을 설계하는 시간관리</title>
  <link rel="stylesheet" href="css" />
</head>
<body>
  <!-- 파스텔 그라데이션 고정 배경 -->
  <div class="bg-layer"></div>

  <!-- 상단 로고만 있는 헤더 -->
  <header class="site-header">
    <div class="logo"> ⏱ ALWAYS GO </div>
  </header>

  <main>
    <!-- ========== 1. 히어로(처음 보이는 화면) ========== -->
    <section class="hero">
      <div class="hero-text">
        <p class="hero-eyebrow"> STUDY · WORK · LIFE BALANCE</p>
        <h1>
          늘고인으로써, <br/>
          우리는 <span class="hero-highlight">언제나 간다</span>
        </h1>
        <p class="hero-sub">
          'always go'는 해야 할 일을 <strong>시간 블록</strong>으로 쪼개서, <br/>
          <strong>한 번에 하나</strong>에만 집중하게 도와주는
          <strong>시간 설계 도구</strong>입니다.
        </p>

        <div class="hero-cta-row">
          <button class="btn primary">있어보이는 버튼1</button>
          <button class="btn ghost">있어보이는 버튼2</button>
        </div>

        <div class="hero-small-text">
          솔직히 이건 개발자인 나도 인정한다 <strong>10215우승연</strong>의 생기부용 작품
        </div>
      </div>

      <!-- 오른쪽: 가짜 앱 미리보기(HTML/CSS로만 만든 썸네일) -->
      <div class="hero-preview">
        <div class="preview-window">
          <div class="preview-topbar">
            <div class="dots">
              <span></span><span></span><span></span>
            </div>
            <div class="preview-title">오늘 흐름</div>
            <div class="preview-tag">기본형식</div>
          </div>

          <div class="preview-body">
            <!-- 좌: 오늘 타임블록 리스트 -->
            <div class="preview-column left">
              <div class="preview-label">오늘 블록</div>
              
              <!-- 등교시간-->
              <div class="preview-block focus">
                <div class="preview-block-main">
                  <span class="pill">등교 시간</span>
                  <span class="time">15분</span>
                </div>
                <p>영어 - 1지문 영단어 2회독</p>
                <div class="bar-bg">
                  <div class="bar-fill"></div>
                </div>
              </div>
              
              <!-- 자습시간-->
              <div class="preview-block soft">
                <div class="preview-block-main">
                  <span class="pill pill-yellow"> 자습 시간</span>
                  <span class="time">50분</span>
                </div>
                <p> 수학 - 학원숙제 워크북 <br/> 과학 - 자이스토리 심화문제</p>
              </div>

              <!-- 자기전 10분-->
              
              <div class="preview-block soft">
                <div class="preview-block-main">
                  <span class="pill pill-green"> 자기전 10분</span>
                  <span class="time">15분</span>
                </div>
                <p>기타 - 내일 타임블록 미리 설계 <br/> 기타 - 일기쓰기 </p>
              </div>
            </div>

            <!-- 우: 타이머 + 오늘 통계 -->
            <div class="preview-column right">
              <div class="preview-timer-card">
                <div class="timer-circle">
                  <div class="timer-inner">
                    <span class="timer-label">현재 포커스</span>
                    <span class="timer-time">0:12:15</span>
                    <span class="timer-task"> 영단어 복습중 </span>
                  </div>
                </div>
                <div class="timer-actions">
                  <span class="timer-pill"> 간단하게 </span>
                  <span class="timer-pill light">비행기모드</span>
                </div>
              </div>

              <div class="preview-metrics">
                <div class="metric">
                  <span class="metric-label">오늘 최대 집중 시간</span>
                  <span class="metric-value">0시간 12분</span>
                  <div class="metric-bar">
                    <div class="metric-fill" style="--val: 0.6;"></div>
                  </div>
                </div>
                <div class="metric">
                  <span class="metric-label">완료한 블록</span>
                  <span class="metric-value"> 1 / 5</span>
                  <div class="metric-bar">
                    <div class="metric-fill purple" style="--val: 0.5;"></div>
                  </div>
                </div>
              </div>

              <div class="preview-quote">
                "오늘의 밀도있게 쓴 <strong>1시간</strong>이, <br/> 시험 3일 전의
                <strong>불안</strong>보다 강하다."
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ========== 2. 서비스 / 가격 / 문의 패널 ========== -->
    <section class="info-section">
      <div class="info-header">
        <h2>AWALYS, 어떤 서비스인가요?</h2>
        <p>시험삼아 만든건데 은근 마음에들어서 급하게 퀄리티 높이고 생기부용으로 바꾼 프로젝트</p>
      </div>

      <div class="info-grid">
        <article class="info-card">
          <h3> 서비스(아마) </h3>
          <p>
            해야 할 일을 <strong>시간 블록</strong>으로 쪼개고, <br/>
            블록마다 <strong>해야할것</strong>을 설정하는 웹.
          </p>
          <ul>
            <li> 내게 주어진 시간 → 타임블록으로 변환</li>
            <li> 각 블록마다 집중 타이머</li>
            <li> 하루를 타임블록 시각화</li>
          </ul>
        </article>

        <article class="info-card">
          <h3>가격</h3>
          <p>
            <strong>완전 무료</strong> <br/>
            왜냐구요? 진짜 서비스가 아니거든요.
          </p>
          <ul>
            <li>학생 플랜 (솔직히 여기까진 해볼만함)</li>
            <li>직장인 플랜 (시간 있으면 시도할거임)</li>
            <li>백수 플랜 (시간 있어도 귀찮아서 안할듯)</li>
          </ul>
        </article>

        <article class="info-card">
          <h3>문의 · 피드백</h3>
          <p>
            아직은 완전 초기형! <br/> 어떤기능이 있으면 좋을지 의견받아요!
          </p>
          <ul>
            <li>"모의고사 전용 모드" 어떨지?</li>
            <li>"폰 사용량 같이 보여주기" 아이디어</li>
            <li>나중에 실제로 웹 연결하기 좋은 위치</li>
          </ul>
        </article>
      </div>
    </section>

    <!-- ========== 3. 로그인 & 회원가입 패널 (스크롤해서 보는 구역) ========== -->
    <section class="auth-section" id="auth">
      <div class="auth-header">
        <h2>내 하루를 설계해볼까요?</h2>
        <p> 데이터베이스 만드는중... </p>
      </div>

      <div class="auth-panels">
        <!-- 로그인 패널 -->
        <div class="auth-card">
          <div class="auth-badge">로그인</div>
          <h3>이미 AWALYS GO을 쓰고 있다면</h3>
          <p class="auth-desc">
            자주 쓰는 기기라면 <strong>자동 로그인</strong> 하기
          </p>
          <form class="auth-form">
            <input type="email" placeholder="아이디" />
            <input type="password" placeholder="비밀번호" />
            <button type="button" class="btn primary full">로그인</button>
          </form>
        </div>

        <!-- 회원가입 패널 -->
        <div class="auth-card signup">
          <div class="auth-badge badge-green">회원가입</div>
          <h3>처음 시작하는 사람이라면</h3>
          <p class="auth-desc">
            입력이 가능하긴 함...! 출력이 안될뿐.
          </p>
          <form class="auth-form">
            <input type="text" placeholder="아이디" />
            <input type="email" placeholder="비밀번호" />
            <input type="password" placeholder="비밀번호 확인" />
            <button type="button" class="btn ghost full">회원가입</button>
          </form>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    HTML 와 CSS 만 구성해둔 상태. JS는 나중에 배우면...! 해볼수도?
  </footer>
</body>
</html>
