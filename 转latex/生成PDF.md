
  
---
puppeteer:
  format: A4
  margin:
    top: 2.0cm
    bottom: 1.8cm
    left: 2cm
    right: 2cm
  displayHeaderFooter: true
  printBackground: true
  timeout: 3000
  headerTemplate: |
    <div style="width: 100%; padding: 0 40px; box-sizing: border-box;">
      <div style="width: 100%; border-bottom: 1px solid #777;"></div>
    </div>
  footerTemplate: |
    <div style="width: 100%; box-sizing: border-box; font-size: 11px; font-family: 'Times New Roman', serif; text-align: center; color: #444;">
      <span class="pageNumber"></span>
    </div>
---
<style>
:root {
  --report-red: #9d1d1d;
  --report-ink: #222;
  --report-rule: #777;
}

@page {
  size: A4;
  margin: 2.6cm 2.2cm 2.4cm 2.2cm;
}

body,
.markdown-preview.markdown-preview {
  font-family: "SimSun", "STSong", "Times New Roman", serif;
  font-size: 12pt;
  line-height: 1.8;
  color: var(--report-ink);
}

h1,
h2,
h3,
h4 {
  font-family: "SimSun", "STSong", "Times New Roman", serif;
  font-weight: 700;
  color: var(--report-ink);
}

h1 {
  margin: 0 0 1.8em;
  text-align: center;
  font-size: 22pt;
  letter-spacing: 0.12em;
}

h2 {
  margin: 2em 0 0.9em;
  padding-left: 0.7em;
  border-left: 4px solid var(--report-red);
  font-size: 16pt;
}

p {
  margin: 0.55em 0;
  text-align: justify;
  text-indent: 2em;
}

li p,
blockquote p {
  text-indent: 0;
}

hr {
  width: 72%;
  margin: 2.4em auto;
  border: 0;
  border-top: 1px solid #999;
}

.page-break {
  break-after: page;
  page-break-after: always;
}

.report-cover {
  min-height: 246mm;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.report-cover-mark {
  margin-top: 22mm;
  width: 72px;
  height: 72px;
  border: 2px solid var(--report-red);
  border-radius: 50%;
  color: var(--report-red);
  font-size: 26px;
  font-weight: 700;
  line-height: 68px;
  letter-spacing: 0.08em;
}

.report-cover-university-cn {
  margin-top: 8mm;
  color: var(--report-red);
  font-size: 28pt;
  font-weight: 700;
  letter-spacing: 0.1em;
}

.report-cover-university-en {
  margin-top: 3mm;
  color: var(--report-red);
  font-size: 14pt;
  letter-spacing: 0.08em;
}

.report-cover-title {
  margin-top: 34mm;
  font-size: 24pt;
  font-weight: 700;
  letter-spacing: 0.12em;
}

.report-cover-subtitle {
  margin-top: 8mm;
  font-size: 14pt;
  letter-spacing: 0.06em;
}

.report-cover-meta {
  width: 58%;
  margin-top: 30mm;
  border-collapse: collapse;
  font-size: 14pt;
}

.report-cover-meta td {
  padding: 10px 0;
}

.report-cover-meta td.label {
  width: 28%;
  text-align: left;
}

.report-cover-meta td.value {
  width: 72%;
  text-align: center;
  border-bottom: 1px solid var(--report-rule);
}

.report-cover-date {
  margin-top: auto;
  margin-bottom: 18mm;
  font-size: 13pt;
  letter-spacing: 0.2em;
}
</style>

<div class="report-cover">
  <div class="report-cover-mark">SDU</div>
  <div class="report-cover-university-cn">山东大学</div>
  <div class="report-cover-university-en">SHANDONG UNIVERSITY</div>

  <div class="report-cover-title">高等线性代数课程报告</div>
  <div class="report-cover-subtitle">主题：泛性质</div>

  <table class="report-cover-meta">
    <tr>
      <td class="label">班级</td>
      <td class="value">请填写</td>
    </tr>
    <tr>
      <td class="label">学号</td>
      <td class="value">请填写</td>
    </tr>
    <tr>
      <td class="label">姓名</td>
      <td class="value">请填写</td>
    </tr>
  </table>

  <div class="report-cover-date">2026 年 5 月 22 日</div>
</div>

<div class="page-break"></div>