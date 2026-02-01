# transcript
<html lang="en">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>Academic Transcript — Fall 2025</title>

<style>
:root{
  --green:#005239;
  --gold:#FFC733;
  --ink:#0b1220;
  --line:#d9dee7;
  --soft:#f6f8fb;
}

body{
  margin:0;
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial;
  background:#f3f6f5;
}

/* paper */
.sheet{
  max-width:1000px;
  margin:30px auto;
  background:white;
  border-radius:14px;
  box-shadow:0 20px 60px rgba(0,0,0,.08);
  overflow:hidden;
  position:relative;
}

/* watermark */
.sheet::before{
  content:"";
  position:absolute;
  inset:0;
  background:url("https://upload.wikimedia.org/wikipedia/commons/8/8b/George_Mason_University_logo.svg") center 45%/520px no-repeat;
  opacity:.05;
  pointer-events:none;
}

/* header */
.header{
  background:linear-gradient(90deg,var(--green),#0a7a3c);
  color:white;
  padding:18px 24px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.header img{
  height:44px;
}

.header h1{
  margin:0;
  font-size:18px;
}

.header small{
  opacity:.9;
}

button{
  background:rgba(255,255,255,.15);
  border:1px solid rgba(255,255,255,.25);
  color:white;
  padding:8px 12px;
  border-radius:8px;
  cursor:pointer;
}

/* content */
.content{
  padding:22px;
}

.section-title{
  font-weight:700;
  margin:16px 0 8px;
}

/* student grid */
.grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:10px;
  margin-bottom:20px;
}

.box{
  border:1px solid var(--line);
  border-radius:10px;
  padding:10px;
  background:var(--soft);
}

.k{font-size:12px;color:#666}
.v{font-weight:700}

/* table */
table{
  width:100%;
  border-collapse:collapse;
}

th,td{
  padding:12px;
  border-bottom:1px solid var(--line);
  text-align:left;
  font-size:14px;
}

th{
  background:#eef2f7;
}

.grade{
  font-weight:700;
}

.A{color:#16a34a}
.Aminus{color:#22c55e}
.Bplus{color:#2563eb}

.footer{
  font-size:12px;
  color:#666;
  margin-top:14px;
}

@media print{
  button{display:none}
  body{background:white}
}
</style>
</head>

<body>

<div class="sheet">

  <div class="header">
    <div style="display:flex;align-items:center;gap:12px">
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/George_Mason_University_logo.svg">
      <div>
        <h1>George Mason University</h1>
        <small>Office of the Registrar • Academic Transcript (Unofficial Copy)</small>
      </div>
    </div>
    <button onclick="window.print()">Print / Save PDF</button>
  </div>

  <div class="content">

    <!-- Student Info -->
    <div class="section-title">Student Information</div>
    <div class="grid">
      <div class="box"><div class="k">Name</div><div class="v">Junjie Song</div></div>
      <div class="box"><div class="k">G-Number</div><div class="v">G086619</div></div>
      <div class="box"><div class="k">College</div><div class="v">CEC – College of Engineering and Computing</div></div>

      <div class="box"><div class="k">Major</div><div class="v">Computer Science</div></div>
      <div class="box"><div class="k">Track</div><div class="v">Cybersecurity</div></div>
      <div class="box"><div class="k">Term</div><div class="v">Fall 2025</div></div>
    </div>

    <!-- GPA Summary -->
    <div class="section-title">Term Summary</div>
    <div class="grid">
      <div class="box"><div class="k">Term GPA (4.0)</div><div class="v">3.67</div></div>
      <div class="box"><div class="k">Credits Earned</div><div class="v">18</div></div>
      <div class="box"><div class="k">Courses</div><div class="v">6</div></div>
    </div>

    <!-- Courses -->
    <div class="section-title">Coursework</div>
    <table>
      <thead>
        <tr>
          <th>Course</th>
          <th>Credits</th>
          <th>Grade</th>
          <th>Quality Points</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>ENGH 302</td><td>3</td><td class="grade Aminus">A-</td><td>11.1</td></tr>
        <tr><td>CS 362</td><td>3</td><td class="grade A">A</td><td>12.0</td></tr>
        <tr><td>CS 405</td><td>3</td><td class="grade A">A</td><td>12.0</td></tr>
        <tr><td>CS 302</td><td>3</td><td class="grade Bplus">B+</td><td>9.9</td></tr>
        <tr><td>MATH 401</td><td>3</td><td class="grade Aminus">A-</td><td>11.1</td></tr>
        <tr><td>IT 309</td><td>3</td><td class="grade Bplus">B+</td><td>9.9</td></tr>
      </tbody>
    </table>

    <div class="footer">
      This webpage is a personal, unofficial transcript-style view for private use only.
    </div>

  </div>
</div>

</body>
</html>
