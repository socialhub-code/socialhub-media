
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="SOCIALHUB MEDIA — Công nghệ truyền thông, Social Media, Content, Creative, Performance và Brand Growth.">
<title>SOCIALHUB MEDIA — Communication Technology 5.0</title>
<style>
:root{
  --bg:#040610;--bg2:#080c18;--surface:#0d1322;--surface2:#111a2d;
  --text:#f5f7ff;--muted:#9ca8bf;--line:rgba(255,255,255,.10);
  --blue:#2d7cff;--violet:#7a4cff;--cyan:#26ddff;--pink:#d84dff;
  --max:1220px;--radius:24px;
}
*{box-sizing:border-box}html{scroll-behavior:smooth}
body{margin:0;background:
radial-gradient(circle at 80% 5%,rgba(86,56,255,.25),transparent 28%),
radial-gradient(circle at 10% 35%,rgba(0,204,255,.10),transparent 24%),var(--bg);
color:var(--text);font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",Arial,sans-serif}
body:before{content:"";position:fixed;inset:0;pointer-events:none;opacity:.25;background-image:linear-gradient(rgba(255,255,255,.018) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.018) 1px,transparent 1px);background-size:50px 50px}
a{text-decoration:none;color:inherit}.wrap{width:min(92%,var(--max));margin:auto}
.nav{position:fixed;z-index:50;top:0;left:0;right:0;border-bottom:1px solid var(--line);background:rgba(4,6,16,.72);backdrop-filter:blur(20px)}
.navin{height:78px;display:flex;align-items:center;justify-content:space-between;gap:24px}
.logo{display:flex;align-items:center;gap:11px;font-weight:900;letter-spacing:.03em;white-space:nowrap}
.logoMark{width:37px;height:37px;border-radius:11px;background:linear-gradient(135deg,var(--violet),var(--blue),var(--cyan));position:relative;box-shadow:0 0 35px rgba(85,75,255,.45)}
.logoMark:after{content:"";position:absolute;right:7px;bottom:7px;width:9px;height:9px;background:#fff;border-radius:3px}
.menu{display:flex;gap:25px;color:#c4cce0;font-size:14px}.menu a:hover{color:#fff}
.navBtn{padding:11px 18px;border-radius:999px;background:linear-gradient(100deg,var(--blue),var(--violet));font-weight:800;box-shadow:0 10px 30px #594cff3a}
.hero{min-height:900px;padding:155px 0 100px;display:flex;align-items:center;position:relative;overflow:hidden}
.hero:after{content:"";position:absolute;width:650px;height:650px;right:-260px;top:130px;border-radius:50%;background:linear-gradient(135deg,#4c3bff33,#00d9ff12);filter:blur(35px)}
.heroGrid{display:grid;grid-template-columns:1.02fr .98fr;gap:55px;align-items:center;position:relative;z-index:1}
.badge{display:inline-flex;align-items:center;gap:9px;border:1px solid #6f79ff3d;background:#ffffff07;border-radius:999px;padding:8px 13px;color:#bfc9ff;font-size:11px;font-weight:800;letter-spacing:.13em;text-transform:uppercase}
.dot{width:7px;height:7px;background:var(--cyan);border-radius:50%;box-shadow:0 0 15px var(--cyan)}
h1{font-size:clamp(52px,7.3vw,92px);line-height:.94;letter-spacing:-.065em;margin:24px 0}
.gradient{background:linear-gradient(95deg,#fff 20%,#6e91ff 52%,#c269ff 78%,#40e5ff);-webkit-background-clip:text;background-clip:text;color:transparent}
.heroText{font-size:19px;line-height:1.75;color:var(--muted);max-width:650px}
.actions{display:flex;gap:12px;flex-wrap:wrap;margin:30px 0}.btn{padding:14px 20px;border-radius:13px;border:1px solid var(--line);font-weight:850}.primary{border:0;background:linear-gradient(100deg,var(--blue),var(--violet));box-shadow:0 15px 40px #5b4cff35}.ghost{background:#ffffff06}
.miniStats{display:flex;gap:32px;flex-wrap:wrap;margin-top:35px}.miniStats b{font-size:27px;display:block}.miniStats span{color:#7f8ba4;font-size:12px}
.heroVisual{height:580px;display:grid;place-items:center;position:relative}
.device{width:285px;height:535px;border:8px solid #202941;border-radius:43px;background:#060912;padding:12px;transform:rotate(6deg);box-shadow:0 40px 100px #000,0 0 75px #4c60ff55;position:relative;z-index:5}
.screen{height:100%;border-radius:31px;overflow:hidden;background:linear-gradient(150deg,#111a42,#090c18 60%);padding:22px 17px;display:flex;flex-direction:column;justify-content:space-between}
.screenTop{display:flex;justify-content:space-between;color:#9ba9cf;font-size:11px}.screenLogo{font-weight:900;font-size:22px;line-height:1.05;margin-top:20px}
.screenCard{border:1px solid #ffffff14;background:#ffffff08;border-radius:17px;padding:14px}.screenCard strong{font-size:13px}.screenCard small{display:block;color:#8995ad;margin-top:5px}
.rings{position:absolute;width:500px;height:500px;border:1px solid #6072ff65;border-radius:50%;box-shadow:0 0 70px #5960ff19}.rings:before,.rings:after{content:"";position:absolute;border:1px solid #20dfff42;border-radius:50%}.rings:before{inset:50px;transform:rotate(35deg)}.rings:after{inset:-35px;transform:rotate(-30deg)}
.socialIcon{position:absolute;z-index:7;padding:14px 16px;border-radius:17px;background:#0d1427e8;border:1px solid #ffffff1d;box-shadow:0 15px 35px #0008;font-weight:900}.facebook{left:15px;top:85px;color:#5d8dff}.instagram{right:20px;top:105px;color:#ff6cc7}.tiktok{left:10px;bottom:90px}.zalo{right:0;bottom:145px;color:#45caff}.telegram{left:70px;top:245px;color:#45dcff}
.floating{position:absolute;border:1px solid #ffffff15;background:#ffffff07;border-radius:15px;padding:12px 15px;color:#9da9c1;font-size:11px;z-index:8}.float1{right:0;top:15px}.float2{left:-20px;bottom:25px}
section{padding:105px 0}.sectionHead{display:flex;justify-content:space-between;align-items:end;gap:35px;margin-bottom:38px}.kicker{color:#5c9cff;font-size:11px;font-weight:900;letter-spacing:.18em;text-transform:uppercase}.sectionHead h2{font-size:clamp(37px,5vw,62px);line-height:1.02;letter-spacing:-.05em;margin:10px 0}.sectionHead p{max-width:520px;color:var(--muted);line-height:1.75}
.serviceGrid{display:grid;grid-template-columns:repeat(4,1fr);gap:15px}.service{min-height:245px;padding:25px;border:1px solid var(--line);border-radius:21px;background:linear-gradient(150deg,#11182b,#090d18);transition:.25s;position:relative;overflow:hidden}.service:after{content:"";position:absolute;width:120px;height:120px;right:-70px;top:-70px;border-radius:50%;background:#6654ff2b;filter:blur(20px)}.service:hover{transform:translateY(-6px);border-color:#6074ff66;box-shadow:0 25px 55px #0008}
.serviceNo{color:#6b83ff;font-weight:900;font-size:12px}.service h3{font-size:19px;margin:28px 0 9px}.service p{color:#8e9ab2;font-size:13px;line-height:1.65;margin:0}.serviceLink{display:inline-block;margin-top:20px;color:#8aa6ff;font-size:12px;font-weight:800}
.platforms{display:grid;grid-template-columns:repeat(5,1fr);gap:12px}.platform{padding:22px;text-align:center;border:1px solid var(--line);border-radius:18px;background:#0c111e}.platform .picon{width:54px;height:54px;margin:0 auto 12px;border-radius:17px;display:grid;place-items:center;font-size:24px;font-weight:900}.fb{background:#1665e8;color:#fff}.ig{background:linear-gradient(135deg,#833ab4,#fd1d1d,#fcb045);color:#fff}.tt{background:#000;color:#fff;border:1px solid #ffffff22}.zl{background:#fff;color:#1677ff}.tg{background:#159eea;color:#fff}.platform b{font-size:14px}.platform span{display:block;color:#79859d;font-size:11px;margin-top:5px}
.stats{display:grid;grid-template-columns:repeat(5,1fr);border:1px solid var(--line);border-radius:23px;background:#0b101c;overflow:hidden}.stat{padding:30px 15px;text-align:center;border-right:1px solid var(--line)}.stat:last-child{border:0}.stat b{font-size:34px}.stat span{display:block;color:#8490a8;font-size:12px;margin-top:5px}
.solution{display:grid;grid-template-columns:.9fr 1.1fr;gap:18px}.solutionMain,.solutionSide{border:1px solid var(--line);border-radius:24px;background:linear-gradient(145deg,#121a31,#080c16);padding:34px}.solutionMain{min-height:440px;position:relative;overflow:hidden}.solutionMain h3{font-size:35px;line-height:1.1;margin:15px 0}.solutionMain p{color:var(--muted);max-width:550px;line-height:1.75}.solutionMain:after{content:"";position:absolute;width:330px;height:330px;border-radius:50%;right:-140px;bottom:-170px;background:#654dff44;filter:blur(45px)}
.techList{display:grid;gap:12px}.tech{padding:18px;border:1px solid var(--line);border-radius:17px;background:#ffffff05;display:grid;grid-template-columns:42px 1fr;gap:14px}.techIcon{width:42px;height:42px;border-radius:12px;background:#5b6eff1a;color:#76a4ff;display:grid;place-items:center;font-weight:900}.tech strong{font-size:14px}.tech span{display:block;color:#7e8aa2;font-size:12px;margin-top:4px}
.projects{display:grid;grid-template-columns:repeat(3,1fr);gap:15px}.project{min-height:330px;border-radius:22px;border:1px solid var(--line);padding:25px;display:flex;flex-direction:column;justify-content:end;overflow:hidden;position:relative;background:radial-gradient(circle at 75% 20%,#496eff66,transparent 25%),linear-gradient(145deg,#17265e,#090d18)}.project:nth-child(2){background:radial-gradient(circle at 75% 20%,#b14eff55,transparent 25%),linear-gradient(145deg,#351a5c,#090d18)}.project:nth-child(3){background:radial-gradient(circle at 75% 20%,#18d9c855,transparent 25%),linear-gradient(145deg,#0c4b56,#090d18)}.tag{display:inline-block;border:1px solid #ffffff1f;border-radius:999px;padding:6px 9px;font-size:10px;color:#d9e0ef;margin-right:5px}.project h3{font-size:27px;margin:10px 0 6px}.project p{color:#b7c0d3;font-size:13px;margin:0}
.steps{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}.step{padding:24px;border:1px solid var(--line);border-radius:19px;background:#0c111e}.stepNo{color:#7d86ff;font-weight:900;font-size:12px}.step h3{margin:13px 0 7px}.step p{color:#8490a8;font-size:13px;line-height:1.6;margin:0}
.cta{border:1px solid #6875ff55;border-radius:29px;padding:50px;background:linear-gradient(110deg,#13285e,#351d6c 60%,#0b1327);display:grid;grid-template-columns:1.2fr .8fr;gap:35px;position:relative;overflow:hidden}.cta:after{content:"";position:absolute;width:400px;height:400px;right:-190px;top:-180px;border-radius:50%;background:#28dfff1d;filter:blur(20px)}.cta h2{font-size:clamp(38px,5vw,60px);line-height:1;margin:10px 0}.cta p{color:#ccd3e4;line-height:1.7}.contact{display:grid;gap:12px;align-content:center;position:relative;z-index:2}.contact div{padding:15px;border:1px solid #ffffff12;background:#ffffff08;border-radius:14px}.contact small{display:block;color:#96a3bd;font-size:10px;text-transform:uppercase;letter-spacing:.1em;margin-bottom:3px}
footer{padding:35px 0;border-top:1px solid var(--line);display:flex;justify-content:space-between;color:#7f8aa0;font-size:12px}
@media(max-width:950px){.menu{display:none}.heroGrid,.solution,.cta{grid-template-columns:1fr}.heroVisual{margin-top:25px}.serviceGrid{grid-template-columns:repeat(2,1fr)}.platforms,.stats{grid-template-columns:repeat(2,1fr)}.stat{border-bottom:1px solid var(--line)}.projects,.steps{grid-template-columns:1fr 1fr}.sectionHead{display:block}.sectionHead p{margin-top:15px}}
@media(max-width:560px){.hero{padding-top:125px}.heroVisual{height:510px}.device{width:235px;height:450px}.rings{width:360px;height:360px}.socialIcon{padding:11px 12px}.serviceGrid,.platforms,.projects,.steps{grid-template-columns:1fr}.stats{grid-template-columns:1fr}.stat{border-right:0}.cta{padding:32px}.miniStats{gap:18px}footer{display:block}footer span{display:block;margin:5px 0}}
</style>
</head>
<body>
<header class="nav">
<div class="wrap navin">
<a class="logo" href="#top"><span class="logoMark"></span>SOCIALHUB MEDIA</a>
<nav class="menu"><a href="#dich-vu">Dịch vụ</a><a href="#nen-tang">Nền tảng</a><a href="#cong-nghe">Công nghệ</a><a href="#du-an">Dự án</a><a href="#lien-he">Liên hệ</a></nav>
<a class="navBtn" href="#lien-he">Tư vấn ngay</a>
</div>
</header>

<main id="top">
<section class="hero">
<div class="wrap heroGrid">
<div>
<div class="badge"><span class="dot"></span> COMMUNICATION TECHNOLOGY 5.0</div>
<h1>Kiến tạo thương hiệu<br><span class="gradient">trên kỷ nguyên số</span></h1>
<p class="heroText">SOCIALHUB MEDIA cung cấp giải pháp truyền thông và Social Media thế hệ mới — kết hợp chiến lược, sáng tạo, công nghệ, dữ liệu và AI để giúp thương hiệu nổi bật, kết nối và tăng trưởng.</p>
<div class="actions"><a class="btn primary" href="#dich-vu">Khám phá dịch vụ →</a><a class="btn ghost" href="#lien-he">Nhận tư vấn miễn phí</a></div>
<div class="miniStats"><div><b>3.2M+</b><span>Lượt tiếp cận</span></div><div><b>500+</b><span>Dự án triển khai</span></div><div><b>98%</b><span>Khách hàng hài lòng</span></div></div>
</div>
<div class="heroVisual">
<div class="rings"></div>
<div class="floating float1">● AI • DATA • SOCIAL</div><div class="floating float2">LIVE PERFORMANCE 5.0</div>
<div class="socialIcon facebook">f</div><div class="socialIcon instagram">◎</div><div class="socialIcon tiktok">♪</div><div class="socialIcon zalo">Zalo</div><div class="socialIcon telegram">➤</div>
<div class="device"><div class="screen"><div class="screenTop"><span>09:41</span><span>5G ●●●</span></div><div><div class="screenLogo">SOCIALHUB<br><span class="gradient">MEDIA</span></div><p style="color:#8f9ab1;font-size:12px;line-height:1.6">Social Strategy<br>Creative • Content • Performance</p></div><div class="screenCard"><strong>Brand Growth</strong><small>+128% social reach</small></div><div class="screenCard"><strong>AI Analytics</strong><small>Real-time performance</small></div></div></div>
</div>
</div>
</section>

<section id="dich-vu">
<div class="wrap">
<div class="sectionHead"><div><div class="kicker">01 — SOCIAL MEDIA & TRUYỀN THÔNG</div><h2>Hệ sinh thái dịch vụ<br>cho thương hiệu hiện đại</h2></div><p>Từ chiến lược truyền thông đến nội dung, quảng cáo, Creator và phân tích dữ liệu. Một đối tác cho toàn bộ hành trình Digital.</p></div>
<div class="serviceGrid">
<article class="service"><span class="serviceNo">01 / 08</span><h3>Social Media Management</h3><p>Chiến lược kênh, Content Calendar, đăng tải, quản trị cộng đồng và chăm sóc hình ảnh thương hiệu.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">02 / 08</span><h3>Content Strategy</h3><p>Content Pillar, storytelling, copywriting và hệ thống nội dung theo từng giai đoạn khách hàng.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">03 / 08</span><h3>Creative & Design</h3><p>Key Visual, Social Design, Motion, Banner và nhận diện hình ảnh đồng nhất trên mọi nền tảng.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">04 / 08</span><h3>Video & Short-form</h3><p>TikTok, Reels, Shorts, video quảng cáo, kịch bản, quay dựng và sản xuất nội dung ngắn.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">05 / 08</span><h3>Performance Advertising</h3><p>Facebook, Instagram, TikTok, Google và YouTube Ads với chiến lược testing và tối ưu theo KPI.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">06 / 08</span><h3>KOL / KOC / Creator</h3><p>Tìm kiếm, đánh giá, booking và quản lý Creator phù hợp với thương hiệu và chiến dịch.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">07 / 08</span><h3>Brand Communication</h3><p>Định vị, thông điệp, Tone of Voice và kế hoạch truyền thông giúp thương hiệu được ghi nhớ.</p><span class="serviceLink">Xem giải pháp →</span></article>
<article class="service"><span class="serviceNo">08 / 08</span><h3>Data & AI Analytics</h3><p>Dashboard, Social Listening, đo lường KPI và insight hỗ trợ ra quyết định nhanh hơn.</p><span class="serviceLink">Xem giải pháp →</span></article>
</div>
</div>
</section>

<section id="nen-tang">
<div class="wrap">
<div class="sectionHead"><div><div class="kicker">02 — MULTI-PLATFORM</div><h2>Hiện diện nơi<br>khách hàng đang ở</h2></div><p>Triển khai chiến lược nội dung và truyền thông đa nền tảng, giữ một thông điệp nhưng tối ưu cách thể hiện cho từng cộng đồng.</p></div>
<div class="platforms">
<div class="platform"><div class="picon fb">f</div><b>Facebook</b><span>Community & Ads</span></div>
<div class="platform"><div class="picon ig">◎</div><b>Instagram</b><span>Visual & Lifestyle</span></div>
<div class="platform"><div class="picon tt">♪</div><b>TikTok</b><span>Short-form & Trend</span></div>
<div class="platform"><div class="picon zl">Z</div><b>Zalo</b><span>CRM & Community</span></div>
<div class="platform"><div class="picon tg">➤</div><b>Telegram</b><span>Community & Updates</span></div>
</div>
</div>
</section>

<section id="cong-nghe">
<div class="wrap">
<div class="sectionHead"><div><div class="kicker">03 — TECHNOLOGY 5.0</div><h2>Công nghệ đứng sau<br>mỗi quyết định</h2></div><p>Kết hợp dữ liệu, tự động hóa và AI để rút ngắn thời gian triển khai, tăng chất lượng sáng tạo và tối ưu hiệu suất.</p></div>
<div class="solution">
<div class="solutionMain"><div class="kicker">SOCIALHUB INTELLIGENCE</div><h3>Creative + Data + AI<br>trong một hệ thống</h3><p>Thu thập dữ liệu từ các kênh, phân tích hiệu suất nội dung, nhận diện xu hướng và hỗ trợ đội ngũ đưa ra quyết định truyền thông nhanh, có cơ sở.</p><div class="actions"><a class="btn primary" href="#lien-he">Xây hệ thống cho tôi →</a></div></div>
<div class="solutionSide"><div class="techList">
<div class="tech"><div class="techIcon">AI</div><div><strong>AI Content Intelligence</strong><span>Hỗ trợ ý tưởng, phân nhóm nội dung và tối ưu thông điệp.</span></div></div>
<div class="tech"><div class="techIcon">↗</div><div><strong>Real-time Analytics</strong><span>Theo dõi KPI và hiệu suất chiến dịch theo thời gian thực.</span></div></div>
<div class="tech"><div class="techIcon">◎</div><div><strong>Social Listening</strong><span>Hiểu cuộc trò chuyện, phản hồi và xu hướng của cộng đồng.</span></div></div>
<div class="tech"><div class="techIcon">⚡</div><div><strong>Automation</strong><span>Chuẩn hóa quy trình và giảm thời gian cho các tác vụ lặp lại.</span></div></div>
</div></div>
</div>
</div>
</section>

<section>
<div class="wrap"><div class="stats"><div class="stat"><b>3.2M+</b><span>Reach</span></div><div class="stat"><b>1.6M+</b><span>Engagement</span></div><div class="stat"><b>500+</b><span>Dự án</span></div><div class="stat"><b>250+</b><span>Khách hàng</span></div><div class="stat"><b>5+</b><span>Năm kinh nghiệm</span></div></div></div>
</section>

<section id="du-an">
<div class="wrap">
<div class="sectionHead"><div><div class="kicker">04 — CASE STUDY</div><h2>Dự án & chiến dịch<br>tiêu biểu</h2></div><p>Những nhóm dự án mẫu để thể hiện năng lực chiến lược, sáng tạo, truyền thông và Performance.</p></div>
<div class="projects">
<article class="project"><div><span class="tag">F&B</span><span class="tag">Social + Ads</span></div><h3>The Coffee House</h3><p>Brand awareness • Community • Performance</p></article>
<article class="project"><div><span class="tag">Fashion</span><span class="tag">Creative</span></div><h3>IVY moda</h3><p>Content system • Visual identity • Campaign</p></article>
<article class="project"><div><span class="tag">Beauty</span><span class="tag">Creator</span></div><h3>Beauty Brand</h3><p>KOL/KOC • Short-form • Conversion</p></article>
</div>
</div>
</section>

<section id="quy-trinh">
<div class="wrap">
<div class="sectionHead"><div><div class="kicker">05 — WORKFLOW</div><h2>Quy trình 8 bước<br>minh bạch & hiệu quả</h2></div><p>Mỗi dự án được vận hành bằng quy trình rõ ràng, có người phụ trách, mục tiêu, KPI và báo cáo.</p></div>
<div class="steps">
<div class="step"><span class="stepNo">01</span><h3>Discovery</h3><p>Hiểu thương hiệu, mục tiêu, thị trường và khách hàng.</p></div>
<div class="step"><span class="stepNo">02</span><h3>Strategy</h3><p>Xây dựng chiến lược Social & Communication.</p></div>
<div class="step"><span class="stepNo">03</span><h3>Content Plan</h3><p>Lập hệ thống chủ đề và lịch nội dung.</p></div>
<div class="step"><span class="stepNo">04</span><h3>Creative</h3><p>Sản xuất hình ảnh, video và thông điệp.</p></div>
<div class="step"><span class="stepNo">05</span><h3>Publish</h3><p>Đăng tải và quản trị các kênh.</p></div>
<div class="step"><span class="stepNo">06</span><h3>Performance</h3><p>Triển khai quảng cáo và testing.</p></div>
<div class="step"><span class="stepNo">07</span><h3>Optimize</h3><p>Tối ưu liên tục dựa trên dữ liệu.</p></div>
<div class="step"><span class="stepNo">08</span><h3>Report</h3><p>Báo cáo insight và đề xuất giai đoạn tiếp theo.</p></div>
</div>
</div>
</section>

<section id="lien-he">
<div class="wrap">
<div class="cta"><div><div class="kicker">06 — LET'S BUILD</div><h2>Sẵn sàng đưa thương hiệu lên thế hệ Social Media 5.0?</h2><p>Hãy chia sẻ mục tiêu của bạn. SOCIALHUB MEDIA sẽ đề xuất mô hình dịch vụ phù hợp với thương hiệu, ngân sách và giai đoạn phát triển.</p><a class="btn primary" href="mailto:hello@socialhubmedia.vn">Nhận tư vấn miễn phí →</a></div>
<div class="contact">
<div><small>Hotline</small>0900 000 000</div>
<div><small>Email</small>hello@socialhubmedia.vn</div>
<div><small>Website</small>socialhubmedia.vn</div>
<div><small>Social</small>Facebook • Instagram • TikTok • Zalo • Telegram</div>
</div></div>
</div>
</section>
</main>

<footer class="wrap"><span>© 2026 SOCIALHUB MEDIA. All rights reserved.</span><span>Social Media • Communication • Technology 5.0</span></footer>
</body>
</html>
