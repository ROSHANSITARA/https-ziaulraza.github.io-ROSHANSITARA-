# https-ziaulraza.github.io-ROSHANSITARA-
ROSHAN SITARA 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🌟 ROSHAN SITARA Family Tree</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- OrgChart JS CDN -->
  <script src="https://balkangraph.com/js/latest/OrgChart.js"></script>
  <style>
    html, body { height: 100%; margin:0; padding:0; background: #f7f9fa; }
    #tree { width: 100%; height: 92vh; }
    #heading { text-align:center; margin: 1rem 0 0.5rem 0; }
    #lang { margin: 1rem; font-size: 1rem; }
    .boc-name { font-weight: bold; }
    .boc-spouse { color: #6a1b9a; }
    .boc-prophet { color: #1565c0; }
    .boc-hasani { color: #388e3c; }
    .boc-recent { color: #c62828; }
  </style>
</head>
<body>
  <h2 id="heading">🌟 ROSHAN SITARA Family Tree (Hasani ~ Husaini Nasab)</h2>
  <div style="text-align:center;">
    <label for="lang">Language / भाषा / زبان:</label>
    <select id="lang">
      <option value="en">English</option>
      <option value="hi">हिंदी</option>
      <option value="ur">اردو</option>
    </select>
  </div>
  <div id="tree"></div>
<script>
const dataAll = {
en: [
  { id: 1, name: "Prophet Adam (A.S.)", tags:["prophet"] },
  { id: 2, pid: 1, name: "Prophet Shees (A.S.)", tags:["prophet"] },
  { id: 3, pid: 2, name: "Prophet Idris (A.S.)", tags:["prophet"] },
  { id: 4, pid: 3, name: "Prophet Nuh (A.S.)", tags:["prophet"] },
  { id: 5, pid: 4, name: "Sam bin Nuh" },
  { id: 6, pid: 5, name: "Arfakhshad" },
  { id: 7, pid: 6, name: "Shalih" },
  { id: 8, pid: 7, name: "Aabir" },
  { id: 9, pid: 8, name: "Falij" },
  { id: 10, pid: 9, name: "Rawu" },
  { id: 11, pid: 10, name: "Sarugh" },
  { id: 12, pid: 11, name: "Nahur" },
  { id: 13, pid: 12, name: "Tarakh" },
  { id: 14, pid: 13, name: "Prophet Ibrahim Khalilullah (A.S.)", tags:["prophet"] },
  { id: 15, pid: 14, name: "Prophet Ismail (A.S.)", tags:["prophet"] },
  { id: 16, pid: 15, name: "Naz" },
  { id: 17, pid: 16, name: "Ma'ad" },
  { id: 18, pid: 17, name: "Nazar" },
  { id: 19, pid: 18, name: "Kinana" },
  { id: 20, pid: 19, name: "Khuzaymah" },
  { id: 21, pid: 20, name: "Mudar" },
  { id: 22, pid: 21, name: "Ilyas" },
  { id: 23, pid: 22, name: "Muzar" },
  { id: 24, pid: 23, name: "Nazar bin Muzar" },
  { id: 25, pid: 24, name: "Malik" },
  { id: 26, pid: 25, name: "Fihr" },
  { id: 27, pid: 26, name: "Ghalib" },
  { id: 28, pid: 27, name: "Lu'ayy" },
  { id: 29, pid: 28, name: "Ka'b" },
  { id: 30, pid: 29, name: "Murrah" },
  { id: 31, pid: 30, name: "Kilab" },
  { id: 32, pid: 31, name: "Qurb" },
  { id: 33, pid: 32, name: "Hashim" },
  { id: 34, pid: 33, name: "Abdul Muttalib" },
  { id: 35, pid: 34, name: "Abdullah" },
  { id: 36, pid: 35, name: "Prophet Muhammad ﷺ", tags:["prophet"] },
  { id: 101, pid: 36, name: "Imam Hasan (A.S.)", tags:["hasani"] },
  { id: 102, pid: 101, name: "Hasan Muthanna" },
  { id: 103, pid: 102, name: "Musa al-Jawn" },
  { id: 104, pid: 103, name: "Abdullah" },
  { id: 105, pid: 104, name: "Sulaiman" },
  { id: 106, pid: 105, name: "Ismail" },
  { id: 107, pid: 106, name: "Yusuf" },
  { id: 108, pid: 107, name: "Abdur Razzaq" },
  { id: 109, pid: 108, name: "Abdul Qadir Jilani (R.A.)" },
  { id: 110, pid: 109, name: "Abdur Razzaq Shani" },
  { id: 111, pid: 110, name: "Hamid Ganjbakhsh" },
  { id: 112, pid: 111, name: "Khalilullah" },
  { id: 113, pid: 112, name: "Muhammad Shaak (Diwan)" },
  { id: 114, pid: 113, name: "Musa" },
  { id: 115, pid: 114, name: "Abdullah" },
  { id: 116, pid: 115, name: "Muhammad Ali" },
  { id: 117, pid: 116, name: "Habibullah (Jawad)" },
  { id: 118, pid: 117, name: "Ahmadullah" },
  { id: 119, pid: 118, name: "Qadir Bakhsh" },
  { id: 120, pid: 119, name: "Waziruddin" },
  { id: 121, pid: 120, name: "Ilahi Bakhsh" },
  { id: 122, pid: 121, name: "Anwar Ali (dau: Nanni Begum)" },
  { id: 123, pid: 122, name: "Muhammad Bakhsh" },
  { id: 124, pid: 123, name: "Musharraf Ali" },
  { id: 125, pid: 124, name: "Muzaffar Ali" },
  { id: 126, pid: 125, name: "Iqbal Ali" },
  { id: 127, pid: 126, name: "Ismail Ali" },
  { id: 128, pid: 127, name: "Ghulam Rasool" },
  { id: 129, pid: 128, name: "Muhammad Shafi" },
  { id: 130, pid: 129, name: "Muhammad Gayyur Ali", tags: ["recent"] },
  { id: 201, pid: 130, name: "Sayyida Fatima Begum", tags:["spouse","recent"] },
  { id: 202, pid: 130, name: "Sayyid Ayyub Ali", tags:["recent"] },
  { id: 203, pid: 130, name: "Shamina Begum", tags:["spouse","recent"] },
  { id: 204, pid: 130, name: "Arshad", tags:["recent"] },
  { id: 205, pid: 130, name: "Wasim Raza", tags:["recent"] },
  { id: 206, pid: 130, name: "Nadeem Ayyub", tags:["
