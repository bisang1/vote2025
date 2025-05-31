
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>제21대 대통령선거 투표 안내</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/remixicon@4.6.0/fonts/remixicon.css">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;700&display=swap" rel="stylesheet">
<style>
:root {
  --main-blue: #1a56db;
  --light-blue: #eaf1fb;
  --dark-blue: #143688;
  --border-blue: #d2e2fc;
  --gray-bg: #f8fafc;
  --box-radius: 15px;
  --sub-head-grad: linear-gradient(93deg,#a6d0ff 2%, #eef3fc 97%);
  --h2-shadow: 0 4px 18px #1a56db20;
}
.vote2025-app * { box-sizing:border-box; }
.vote2025-app { font-family:'Noto Sans KR',Arial,sans-serif; color:#222; background:var(--gray-bg);}
.vote2025-app main { max-width:480px; margin:0 auto; padding:16px 0 84px 0; }
.vote2025-app .app-header {
  position:fixed; top:0; left:0; width:100vw; height:58px;
  background:var(--main-blue); color:#fff; z-index:100;
  display:flex; align-items:center; justify-content:space-between; padding:0 20px;
  box-shadow:0 2px 10px #1440a61d;
}
.vote2025-app .app-header .logo {font-weight:900; font-size:1.15rem; font-family:'Pacifico',cursive;letter-spacing:-1px;}
.vote2025-app .app-header .caption {font-size:.98em; margin-left:8px;}
.vote2025-app .app-header .menu {font-size:1.6em; cursor:pointer;}
/* section box */
.vote2025-app-section {background:#fff; border-radius:var(--box-radius); margin:20px 0; padding:22px 16px 18px 16px; box-shadow:0 2.5px 12px #1a56db12;}
/* ==== [소제목, 부제목 스타일 업그레이드] ==== */
.vote2025-app h2, .vote2025-app h3 {
  position:relative; display:flex; align-items:center; font-weight:900;
  margin:0 0 18px 0; letter-spacing:-.5px; 
  border-radius:12px; 
  padding:11px 22px 11px 17px; 
  box-shadow:var(--h2-shadow);
}
.vote2025-app h2 {
  font-size:1.22rem; 
  background: var(--sub-head-grad);
  color: var(--main-blue);
  border-left: 6px solid var(--main-blue);
  border-bottom: 1.7px solid #b0d3fd;
  text-shadow:0 1.5px 6px #c0e3ff3f;
  margin-bottom:18px;
}
.vote2025-app h2:before {
  content:'\f0a6';
  font-family:"remixicon";
  font-size:1.26em;
  color:#fcbe43;
  margin-right:11px;
  text-shadow:0 2px 8px #fff2c34b;
  opacity:0.98;
}
.vote2025-app h3 {
  font-size:1.07rem; 
  background:linear-gradient(90deg,#f8fafc 60%, #eaf1fb 100%);
  color: var(--dark-blue);
  border-left:4px solid #5c9bfd;
  border-bottom:1.1px solid #d6e6fc;
  margin-top:13px;
  margin-bottom:12px;
  text-shadow:0 1px 3px #b2bbd93d;
}
.vote2025-app h3:before {
  content:'\efb3';
  font-family:"remixicon";
  font-size:1.12em;
  color:var(--main-blue);
  margin-right:8px;
  opacity:0.82;
}
@media (max-width:700px) {
  .vote2025-app main { padding:12px 0 61px 0; }
  .vote2025-app-section { padding:14px 4vw 13px 4vw;}
  .vote2025-app h2 { font-size:1.08rem; }
  .vote2025-app h3 { font-size:.97rem; }
}
/* 이하 동일, 기존 스타일 유지 */
.vote2025-app .date-row {display:flex;align-items:center;justify-content:center;font-size:1.13em;margin:0 0 9px 0;}
.vote2025-app .date-row i {margin-right:7px;}
.vote2025-app .vote-time {background:var(--light-blue); border-radius:10px; display:inline-block; margin:7px 0 0 0; padding:9px 19px; color:var(--main-blue); font-weight:700;}
.vote2025-app .find-card {background:var(--light-blue); border-radius:12px; display:flex;align-items:center;padding:13px 12px;margin-bottom:12px;}
.vote2025-app .find-card .icon {background:var(--main-blue); color:#fff; border-radius:50%; width:38px; height:38px;display:flex;align-items:center;justify-content:center;font-size:1.3em;}
.vote2025-app .find-card .txt {margin-left:11px;flex:1;}
.vote2025-app .find-card .txt p {margin:0;font-weight:700;}
.vote2025-app .find-card .txt span {font-size:.97em; color:#567;}
.vote2025-app .find-card .arrow {margin-left:auto;font-size:1.5em;color:var(--main-blue);}
.vote2025-app .find-card:hover {background:#d7e9fd;}
.vote2025-app .btn-main {
  display:flex;align-items:center;justify-content:center;gap:6px;width:100%;max-width:300px;margin:9px auto 0 auto;padding:13px 0;
  background:var(--main-blue); color:#fff;font-weight:700;font-size:1.08em;border:none;border-radius:8px;box-shadow:0 2px 8px #1a56db1a;cursor:pointer;
  transition:filter .17s;
}
.vote2025-app .btn-main:hover {filter:brightness(1.09);}
.vote2025-app .btn-main i {font-size:1.1em;}
.vote2025-app .adbox {
  background:var(--light-blue);border-radius:8px;padding:10px;text-align:center;color:#1a56db;font-size:.98em;margin:12px 0;
  border:1.5px dashed var(--border-blue);
}
.vote2025-app .id-list {list-style:none;margin:0;padding:0;}
.vote2025-app .id-list li {display:flex;align-items:center;margin:7px 0;}
.vote2025-app .id-list li i {color:var(--main-blue);margin-right:9px;}
.vote2025-app .mobile-id-grid {display:grid;grid-template-columns:1fr 1fr 1fr;gap:7px;}
.vote2025-app .mobile-id-grid .mobile-id-card {
  background:#fff;border-radius:9px;padding:12px 0;text-align:center;box-shadow:0 2px 6px #1a56db13;
}
.vote2025-app .mobile-id-grid i {font-size:1.45em;color:var(--main-blue);}
.vote2025-app .mobile-id-grid p {margin:7px 0 0 0;font-size:.97em;}
.vote2025-app .steps {margin-top:6px;}
.vote2025-app .step-row {display:flex;align-items:center;margin:11px 0;}
.vote2025-app .step-circle {
  width:33px; height:33px; background:var(--main-blue); color:#fff; font-size:.98em; font-weight:900;
  border-radius:50%; display:flex; align-items:center; justify-content:center; margin-right:12px;
}
.vote2025-app .step-desc {flex:1;}
.vote2025-app .step-title {font-weight:700;color:var(--main-blue);}
.vote2025-app .step-info {font-size:.97em;color:#587;}
.vote2025-app .faq-q {cursor:pointer;user-select:none;font-weight:600;display:flex;align-items:center;justify-content:space-between;font-size:1.06em;margin:17px 0 3px 0;}
.vote2025-app .faq-q i{transition:transform .27s;}
.vote2025-app .faq-q.active i {transform:rotate(180deg);}
.vote2025-app .faq-q.active { color:var(--main-blue);}
.vote2025-app .faq-a {display:none;font-size:0.97em;margin:0 0 0 3px;color:#7a7a8c;}
.vote2025-app .faq-a.active {display:block;}
.vote2025-app .contact-row {display:flex;align-items:center;margin:7px 0;}
.vote2025-app .contact-row .cicon {width:36px;height:36px;border-radius:50%;background:var(--light-blue);display:flex;align-items:center;justify-content:center;font-size:1.28em;color:var(--main-blue);}
.vote2025-app .contact-row .ctxt {margin-left:11px;}
.vote2025-app .contact-row .ctxt span {font-size:.99em;color:#6b6d7c;}
.vote2025-app .tabbar {
  position:fixed; left:0; bottom:0; width:100vw; background:#fff; box-shadow:0 -2px 10px #1440a61a; border-top:1.5px solid #e9eef3;
  display:flex; z-index:99; height:55px;
}
.vote2025-app .tabbar a {
  flex:1; text-align:center; font-size:.98em; color:var(--main-blue); text-decoration:none;
  display:flex; flex-direction:column; align-items:center; justify-content:center; font-weight:700;
  transition:color 0.13s;
}
.vote2025-app .tabbar a i { font-size:1.28em; margin-bottom:2px;}
.vote2025-app .tabbar a.active, .vote2025-app .tabbar a:hover { color:#1a56db; }
</style>
</head>
<body>
<div class="vote2025-app">
  <!-- 상단 헤더 -->
  <div class="app-header">
    <span class="logo">logo</span>
    <span class="caption">소중한 한표로 대한민국을 바꿉니다</span>
    <span class="menu"><i class="ri-menu-line"></i></span>
  </div>
  <main style="margin-top:65px;">
    <!-- 안내 -->
    <section class="vote2025-app-section" style="text-align:center;">
      <h1>제21대 대통령선거</h1>
      <div class="date-row">
        <i class="ri-calendar-line"></i>
        <span>2025년 6월 3일 (화)</span>
      </div>
      <div class="vote-time">투표 시간: 오전 6시 ~ 오후 6시</div>
    </section>
    <!-- 투표소 찾기 -->
    <section class="vote2025-app-section">
      <h2>투표소 찾기</h2>
      <a href="http://info.nec.go.kr/main/showDocument.xhtml?electionId=0020250603&topMenuId=BI&secondMenuId=BIPP01" class="find-card" >
        <span class="icon"><i class="ri-map-pin-line"></i></span>
        <span class="txt">
          <p>투표소 찾기</p>
          <span>가까운 투표소를 확인하세요</span>
        </span>
        <span class="arrow"><i class="ri-arrow-right-s-line"></i></span>
      </a>
      <div class="adbox">Advertisement Area 1</div>
      <a href="https://si.nec.go.kr/" class="btn-main" >
        <i class="ri-search-line"></i> 선거인명부 열람하기
      </a>
      <div style="font-size:0.98em;color:#69758b;text-align:center;margin-top:5px;">선거인명부에서 본인의 투표소를 확인할 수 있습니다</div>
    </section>
    <!-- 준비물 안내 -->
    <section class="vote2025-app-section">
      <h2>투표 준비물</h2>
      <div class="find-card" style="background:#f3f7fd;">
        <span class="icon" style="background:#eaf1fb;color:var(--main-blue);"><i class="ri-id-card-line"></i></span>
        <span class="txt">
          <p>신분증 필수 지참</p>
          <span>본인 확인을 위한 신분증을 반드시 지참하세요</span>
        </span>
      </div>
      <h3>허용되는 신분증 종류</h3>
      <ul class="id-list">
        <li><i class="ri-checkbox-circle-line"></i>주민등록증</li>
        <li><i class="ri-checkbox-circle-line"></i>운전면허증</li>
        <li><i class="ri-checkbox-circle-line"></i>여권</li>
        <li><i class="ri-checkbox-circle-line"></i>공무원증</li>
        <li><i class="ri-checkbox-circle-line"></i>국가유공자증</li>
        <li><i class="ri-checkbox-circle-line"></i>장애인등록증</li>
      </ul>
      <h3>모바일신분증 사용 가이드 <span style="background:#eaf1fb;color:#1a56db;border-radius:7px;padding:2px 8px 2px 7px;font-size:0.9em;margin-left:6px;">신규</span></h3>
      <div class="mobile-id-grid" style="margin-bottom:10px;">
        <div class="mobile-id-card">
          <i class="ri-download-2-line"></i>
          <p>앱 설치</p>
        </div>
        <div class="mobile-id-card">
          <i class="ri-user-add-line"></i>
          <p>신분증 발급</p>
        </div>
        <div class="mobile-id-card">
          <i class="ri-qr-code-line"></i>
          <p>QR 인증</p>
        </div>
      </div>
      <div style="font-size:.98em;color:#444;margin-bottom:3px;"><b>주의사항:</b></div>
      <ul style="font-size:.98em;color:#607090;margin-bottom:8px;">
        <li style="margin-bottom:2px;"><i class="ri-information-line"></i> 모바일신분증 앱 사전 설치 및 발급 필요</li>
        <li style="margin-bottom:2px;"><i class="ri-information-line"></i> 스마트폰 배터리 충분히 충전</li>
        <li><i class="ri-information-line"></i> 인터넷 연결 상태 확인</li>
      </ul>
      <a href="https://www.mobileid.go.kr/mip/hps/issuReqstGuidance/issuReqstGuidanceMrc.do" class="btn-main">
        <i class="ri-download-line"></i> 모바일신분증 앱 다운로드
      </a>
      <div class="adbox">Advertisement Area 2</div>
    </section>
    <!-- 투표 절차 -->
    <section class="vote2025-app-section">
      <h2>투표 절차</h2>
      <div class="steps">
        <div class="step-row"><span class="step-circle">1</span><div class="step-desc"><span class="step-title">신분증 제시</span><div class="step-info">투표소 입구에서 신분증 제시</div></div></div>
        <div class="step-row"><span class="step-circle">2</span><div class="step-desc"><span class="step-title">선거인명부 확인</span><div class="step-info">본인 정보 확인</div></div></div>
        <div class="step-row"><span class="step-circle">3</span><div class="step-desc"><span class="step-title">투표용지 수령</span><div class="step-info">관리위원에게 투표용지 받기</div></div></div>
        <div class="step-row"><span class="step-circle">4</span><div class="step-desc"><span class="step-title">기표</span><div class="step-info">기표소에서 후보 기표</div></div></div>
        <div class="step-row"><span class="step-circle">5</span><div class="step-desc"><span class="step-title">투표함 투입</span><div class="step-info">용지 접어 투표함에 넣기</div></div></div>
      </div>
      <div class="adbox">Advertisement Area 3</div>
      <div style="background:#fefbe7;border-radius:9px;padding:11px 15px;margin-top:13px;color:#a08a12;font-size:.98em;">
        <i class="ri-lightbulb-line"></i> <b>투표 시 유의사항</b><br>
        - 투표용지에 기표 도장만 사용<br>
        - 기표소 내 사진 촬영 금지<br>
        - 투표용지를 접을 때 기표 부분이 보이지 않도록!
      </div>
    </section>
    <!-- FAQ -->
    <section class="vote2025-app-section">
      <h2>자주 묻는 질문 (FAQ)</h2>
      <div>
        <div class="faq-q"><span>투표 시간은 언제인가요?</span> <i class="ri-arrow-down-s-line"></i></div>
        <div class="faq-a">오전 6시 ~ 오후 6시, 6시 정각까지 투표소 도착자 투표 가능.</div>
        <div class="faq-q"><span>신분증을 안 가져가면?</span> <i class="ri-arrow-down-s-line"></i></div>
        <div class="faq-a">신분증(실물/모바일)은 필수. 없으면 투표 불가. 미리 준비!</div>
        <div class="faq-q"><span>투표용지 잘못 기표하면?</span> <i class="ri-arrow-down-s-line"></i></div>
        <div class="faq-a">투표함에 넣기 전 관리관에 반납 → 재교부 1회 가능.</div>
        <div class="faq-q"><span>장애인 지원은?</span> <i class="ri-arrow-down-s-line"></i></div>
        <div class="faq-a">점자용지·확대경·기표대·동행인 등 지원. 현장 문의.</div>
      </div>
      <div class="adbox">Advertisement Area 4</div>
    </section>
    <!-- 선거법 안내 -->
    <section class="vote2025-app-section">
      <h2>선거법 주요 안내사항</h2>
      <ul class="id-list">
        <li><i class="ri-close-circle-line" style="color:#f14d4d"></i>투표소 내 촬영 금지 (비밀 보장)</li>
        <li><i class="ri-close-circle-line" style="color:#f14d4d"></i>투표소 100m 이내 선거운동 금지</li>
        <li><i class="ri-close-circle-line" style="color:#f14d4d"></i>특정 후보·정당 복장 착용 금지</li>
        <li><i class="ri-close-circle-line" style="color:#f14d4d"></i>기표 내용 노출 인증샷 금지</li>
      </ul>
      <div style="background:#eaf1fb;border-radius:9px;padding:10px 15px;margin-top:11px;color:#1750a6;font-size:.98em;">
        <i class="ri-check-double-line"></i> <b>투표 시 안내에 협조</b> — 신중하게 한 표 행사!
      </div>
    </section>
    <!-- 문의 안내 -->
    <section class="vote2025-app-section">
      <h2>문의 안내 & 실시간 개표현황</h2>
      <div class="contact-row">
        <span class="cicon"><i class="ri-phone-line"></i></span>
        <span class="ctxt"><span>선거 문의</span><br><b>1390</b></span>
      </div>
      <div class="contact-row">
        <span class="cicon"><i class="ri-alarm-warning-line"></i></span>
        <span class="ctxt"><span>선거법 위반 신고</span><br><b>1390</b></span>
      </div>
      <div class="contact-row">
        <span class="cicon"><i class="ri-global-line"></i></span>
        <span class="ctxt"><span>중앙선거관리위원회</span><br><a href="https://www.nec.go.kr/" style="color:#1a56db;">www.nec.go.kr</a></span>
      </div>
      <a href="https://www.nec.go.kr/site/vt/main.do" class="btn-main" style="margin-top:13px;">
        <i class="ri-bar-chart-line"></i> 실시간 개표현황
      </a>
    </section>
  </main>
  <!-- 하단 탭바 -->
  <nav class="tabbar">
    <a href="https://www.nec.go.kr/site/vt/main.do" class="active"><i class="ri-home-5-fill"></i>홈</a>
    <a href="http://info.nec.go.kr/main/showDocument.xhtml?electionId=0020250603&topMenuId=BI&secondMenuId=BIPP01"><i class="ri-map-pin-line"></i>투표소</a>
    <a href="https://policy.nec.go.kr/"><i class="ri-user-3-line"></i>후보자</a>
    <a href="https://www.nec.go.kr/site/vt/main.do"><i class="ri-bar-chart-line"></i>개표</a>
    <a href="https://www.nec.go.kr/site/vt/ex/bbs/List.do?cbIdx=1620"><i class="ri-question-answer-line"></i>FAQ</a>
  </nav>
</div>
<script>
(function(){
  var qs=document.querySelectorAll('.vote2025-app .faq-q'),as=document.querySelectorAll('.vote2025-app .faq-a');
  for(let i=0;i<qs.length;i++) qs[i].onclick=function(){
    let isActive=qs[i].classList.contains('active');
    for(let j=0;j<qs.length;j++) {qs[j].classList.remove('active');as[j].classList.remove('active');}
    if(!isActive){qs[i].classList.add('active');as[i].classList.add('active');}
  }
})();
</script>
<!-- 🔒 코드 도난 완전 차단 스크립트 (모든 브라우저에서 감지 후 종료) -->
<script>
  // 키보드 차단: F12, Ctrl+Shift+I, Ctrl+U, Ctrl+S
  document.addEventListener("keydown", function (e) {
    if (
      e.key === "F12" || e.keyCode === 123 || 
      (e.ctrlKey && e.shiftKey && e.key.toLowerCase() === "i") || 
      (e.ctrlKey && e.key.toLowerCase() === "u") ||
      (e.ctrlKey && e.key.toLowerCase() === "s")
    ) {
      blockPage("🚫 보안 경고: 개발자 도구 사용이 차단되었습니다.");
    }
  });

  // 우클릭 차단
  document.addEventListener("contextmenu", function (e) {
    e.preventDefault();
    alert("🖱️ 마우스 우클릭은 제한되어 있습니다.");
  });

  // 개발자 도구 감지 (크기 기반 탐지)
  let devtoolsTriggered = false;
  setInterval(() => {
    const widthThreshold = window.outerWidth - window.innerWidth > 160;
    const heightThreshold = window.outerHeight - window.innerHeight > 160;

    if ((widthThreshold || heightThreshold) && !devtoolsTriggered) {
      devtoolsTriggered = true;
      blockPage("⚠️ 개발자 도구가 감지되어 페이지를 종료합니다.");
    }
  }, 800);

  // 콘솔 열림 감지 (toString 변조 방식)
  const element = new Image();
  Object.defineProperty(element, 'id', {
    get: function () {
      blockPage("🚨 콘솔 접근이 감지되었습니다.");
    }
  });
  console.log(element);

  // 차단 함수: 알림 → 페이지 제거 → 이동
  function blockPage(message) {
    alert(message);
    document.body.innerHTML = "";
    location.href = "https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2F20150826_78%2Fdnjswnsdl90_1440597104192UBq0N_JPEG%2FNaverBlog_20150826_225143_00.jpg&type=sc960_832 "; // 또는 지정된 보안 페이지
  }
</script>

</body>

