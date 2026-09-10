<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>房屋稅自住住宅優惠稅率資格檢核</title>

<style>
*{box-sizing:border-box}
body{
    margin:0;
    font-family:"Noto Sans TC","Microsoft JhengHei",sans-serif;
    background:linear-gradient(135deg,#eef8f2,#f7fbff);
    color:#333;
}
.container{max-width:820px;margin:30px auto;padding:16px}
.card{
    background:#fff;border-radius:28px;padding:32px;
    box-shadow:0 10px 35px rgba(0,0,0,.08);
}
.header{text-align:center}
.title{font-size:30px;font-weight:800;color:#287a57;margin:0 0 8px}
.subtitle{color:#777;margin:0 0 20px}

.deadline{
    background:#fff5df;border:1px solid #f0c46a;color:#805600;
    border-radius:16px;padding:15px 18px;line-height:1.7;
    text-align:center;margin-bottom:24px;
}
.deadline .date{font-size:21px;font-weight:800}

.progress-wrap{margin:10px 0 28px}
.progress-top{display:flex;justify-content:space-between;color:#777;font-size:14px;margin-bottom:8px}
.progress{height:9px;background:#e7efea;border-radius:20px;overflow:hidden}
.progress-bar{height:100%;background:#45a777;width:25%;transition:.3s}

.step{display:none}
.step.active{display:block}
.question{
    font-size:22px;font-weight:800;line-height:1.55;margin-bottom:22px
}
.helper{font-size:15px;color:#777;margin:-10px 0 20px;line-height:1.6}

.option{
    border:2px solid #dce8e1;border-radius:15px;padding:17px 18px;
    margin:12px 0;cursor:pointer;font-size:18px;background:#fff;
    transition:.2s;
}
.option:hover,.option.selected{
    border-color:#45a777;background:#eaf8f0;
}
.option.selected::after{content:" ✓";float:right;color:#287a57;font-weight:bold}

input[type=number]{
    width:100%;padding:16px;border:2px solid #dce8e1;
    border-radius:13px;font-size:20px;outline:none;
}
input[type=number]:focus{border-color:#45a777}

.button-area{display:flex;gap:14px;margin-top:26px}
button{
    flex:1;border:0;border-radius:13px;padding:15px;
    font-size:18px;font-weight:700;cursor:pointer;
}
.btn-prev{background:#edf1f0;color:#555}
.btn-next{background:#45a777;color:#fff}
.btn-next:hover{background:#348b61}

.result{display:none}
.result.show{display:block;text-align:center}
.result-icon{font-size:62px}
.result-title{font-size:28px;font-weight:800;margin:8px 0 16px}

.rate{
    display:inline-block;background:#eaf8f0;color:#287a57;
    border-radius:20px;padding:10px 30px;font-size:42px;
    font-weight:900;margin-bottom:18px;
}
.reason{
    text-align:left;background:#fff8eb;border-left:6px solid #efad45;
    padding:18px;border-radius:12px;line-height:1.8;margin:18px 0;
}
.success-box{
    background:#edf9f2;border:1px solid #bde4cc;color:#245e40;
    border-radius:14px;padding:16px;text-align:left;line-height:1.7;
}
.condition-box{
    text-align:left;background:#f5f8f6;border-radius:18px;
    padding:22px;margin-top:20px;
}
.condition-box h3{color:#287a57;margin:0 0 8px}
.condition{padding:11px 0;border-bottom:1px solid #ddd;line-height:1.7}
.condition:last-child{border-bottom:0}

.apply-link{
    display:block;margin-top:14px;padding:15px;border-radius:13px;
    background:#e9f4ff;color:#1769aa;text-decoration:none;
    font-size:18px;font-weight:800;border:2px solid #bfddf5;
}
.apply-link:hover{background:#dceeff}

.restart{margin-top:14px;background:#287a57;color:#fff;width:100%}

.notice{text-align:left;color:#777;font-size:14px;line-height:1.7;margin-top:18px}

@media(max-width:600px){
    .container{margin:8px auto;padding:9px}
    .card{padding:22px 18px;border-radius:22px}
    .title{font-size:25px}
    .question{font-size:20px}
    .option{font-size:16px}
    .button-area{gap:9px}
    button{font-size:16px}
}
</style>
</head>

<body>

<div class="container">
<div class="card">

<div class="header">
    <h1 class="title">🏠 房屋稅自住資格檢核</h1>
    <p class="subtitle">快速檢查您的房屋是否符合自住住宅優惠稅率</p>
</div>

<div class="deadline" id="deadlineBox"></div>

<div class="progress-wrap">
    <div class="progress-top">
        <span id="stepText">第 1 題／共 4 題</span>
        <span id="percentText">25%</span>
    </div>
    <div class="progress">
        <div class="progress-bar" id="progressBar"></div>
    </div>
</div>

<!-- 第1題 -->
<div class="step active" id="step1">
    <div class="question">① 這間房屋目前有出租或供營業使用嗎？</div>
    <div class="helper">自住住宅須供本人、配偶或直系親屬居住使用。</div>

    <div class="option" onclick="selectOption(1,'yes',this)">🏠 沒有，純粹自己居住</div>
    <div class="option" onclick="selectOption(1,'rent',this)">🏢 有出租</div>
    <div class="option" onclick="selectOption(1,'business',this)">🏪 有供營業使用</div>
</div>

<!-- 第2題 -->
<div class="step" id="step2">
    <div class="question">② 本人、配偶或直系親屬是否實際居住，並在該屋辦竣戶籍登記？</div>
    <div class="option" onclick="selectOption(2,'yes',this)">✅ 有，符合</div>
    <div class="option" onclick="selectOption(2,'no',this)">❌ 沒有</div>
</div>

<!-- 第3題 -->
<div class="step" id="step3">
    <div class="question">③ 本人、配偶及未成年子女，在全國合計有幾戶房屋？</div>
    <div class="helper">請計算全國房屋戶數，不限房屋所在地。</div>
    <input type="number" id="houseCount" min="0" max="99" placeholder="請輸入房屋戶數">
</div>

<!-- 第4題 -->
<div class="step" id="step4">
    <div class="question">④ 這間房屋是否確定作為自住使用？</div>
    <div class="option" onclick="selectOption(4,'yes',this)">✅ 是，確定供自住使用</div>
    <div class="option" onclick="selectOption(4,'no',this)">❌ 否</div>
</div>

<div class="button-area" id="navButtons">
    <button class="btn-prev" onclick="prevStep()">← 上一步</button>
    <button class="btn-next" onclick="nextStep()">下一步 →</button>
</div>

<!-- 結果 -->
<div class="result" id="result">

    <div class="result-icon" id="resultIcon">🎉</div>
    <div class="result-title" id="resultTitle">檢核完成</div>
    <div id="rateArea"></div>
    <div class="reason" id="reason"></div>

    <div id="extraCheck"></div>

    <div class="condition-box">
        <h3>📋 自住住宅優惠稅率條件</h3>

        <div class="condition">
            <strong>① 無出租或供營業使用</strong><br>
            房屋須供自住使用，不得出租或供營業使用。
        </div>

        <div class="condition">
            <strong>② 實際居住並辦竣戶籍</strong><br>
            本人、配偶或直系親屬實際居住，並於該屋辦竣戶籍登記。
        </div>

        <div class="condition">
            <strong>③ 全國合計3戶以內</strong><br>
            本人、配偶及未成年子女全國合計3戶以內。
        </div>

        <div class="condition">
            <strong>⭐ 全國單一自住</strong><br>
            全國僅持有1戶，且符合房屋現值等相關規定者，可適用1%優惠稅率。
        </div>
    </div>

    <div class="deadline" id="resultDeadline"></div>

    <div class="notice">
        ※ 本檢核器僅供資格初步判斷，實際適用情形及稅率仍以房屋所在地地方稅稽徵機關核定結果為準。
    </div>

    <a class="apply-link"
       href="https://www.etax.nat.gov.tw/etwmain/etw109w/cases/services/OLF015015/0"
       target="_blank"
       rel="noopener noreferrer">
       🌐 前往財政部稅務入口網線上申辦
    </a>

    <button class="restart" onclick="restart()">🔄 重新檢測</button>
</div>

</div>
</div>

<script>

let currentStep = 1;
let answers = {};

/* 申請期限：
   一般規則顯示每年3月22日前。
   115年特別顯示3月22日適逢假日，順延至3月23日。
*/
function getDeadlineHTML(){
    const now = new Date();
    const year = now.getFullYear() - 1911;

    if(year === 115){
        return `
            📢 <strong>申請期限提醒</strong><br>
            房屋稅自住住宅優惠稅率請於
            <span class="date">115年3月22日前</span>申請。<br>
            ※ 115年3月22日適逢假日，申請期限順延至
            <strong>115年3月23日</strong>。
        `;
    }

    return `
        📢 <strong>申請期限提醒</strong><br>
        房屋稅自住住宅優惠稅率原則上請於
        <span class="date">${year}年3月22日前</span>申請。<br>
        ※ 如遇假日或法定順延情形，請依當年度公告期限辦理。
    `;
}

function setDeadline(){
    document.getElementById("deadlineBox").innerHTML = getDeadlineHTML();
    document.getElementById("resultDeadline").innerHTML = getDeadlineHTML();
}

function selectOption(step,value,element){
    answers[step] = value;

    document.querySelectorAll("#step"+step+" .option")
        .forEach(o=>o.classList.remove("selected"));

    element.classList.add("selected");
}

function showStep(step){
    document.querySelectorAll(".step")
        .forEach(el=>el.classList.remove("active"));

    document.getElementById("step"+step)
        .classList.add("active");

    const percent = Math.round(step/4*100);

    document.getElementById("progressBar").style.width = percent+"%";
    document.getElementById("percentText").innerText = percent+"%";
    document.getElementById("stepText").innerText =
        "第 "+step+" 題／共 4 題";

    document.getElementById("navButtons").style.display = "flex";
}

function nextStep(){

    if(currentStep===1){

        if(!answers[1]){
            alert("請先選擇房屋使用情形");
            return;
        }

        if(answers[1]==="rent"){
            showResult(
                false,
                "目前不符合自住住宅優惠稅率",
                "您選擇的房屋目前有出租。<br><br>" +
                "<strong>自住住宅須無出租或供營業使用。</strong>"
            );
            return;
        }

        if(answers[1]==="business"){
            showResult(
                false,
                "目前不符合自住住宅優惠稅率",
                "您選擇的房屋目前供營業使用。<br><br>" +
                "<strong>自住住宅須無出租或供營業使用。</strong>"
            );
            return;
        }
    }

    if(currentStep===2){

        if(!answers[2]){
            alert("請先選擇戶籍登記情形");
            return;
        }

        if(answers[2]==="no"){
            showResult(
                false,
                "目前不符合自住住宅優惠稅率",
                "目前尚未符合戶籍登記條件。<br><br>" +
                "<strong>本人、配偶或直系親屬須實際居住，並於該屋辦竣戶籍登記。</strong>"
            );
            return;
        }
    }

    if(currentStep===3){

        const value=document.getElementById("houseCount").value;

        if(value===""){
            alert("請輸入房屋戶數");
            return;
        }

        const count=Number(value);

        if(count<0){
            alert("房屋戶數不能小於0");
            return;
        }

        answers[3]=count;

        if(count>3){
            showResult(
                false,
                "目前不符合一般自住住宅優惠稅率",
                "本人、配偶及未成年子女全國合計房屋超過3戶。<br><br>" +
                "<strong>一般自住住宅須符合全國合計3戶以內。</strong>"
            );
            return;
        }
    }

    if(currentStep===4){

        if(!answers[4]){
            alert("請確認房屋是否供自住使用");
            return;
        }

        if(answers[4]==="no"){
            showResult(
                false,
                "目前不符合自住住宅優惠稅率",
                "您選擇的房屋目前並非供自住使用。<br><br>" +
                "<strong>自住住宅優惠稅率適用於實際供自住使用的房屋。</strong>"
            );
            return;
        }

        calculateResult();
        return;
    }

    currentStep++;
    showStep(currentStep);
}

function prevStep(){

    if(currentStep>1){
        currentStep--;
        showStep(currentStep);
    }
}

function calculateResult(){

    const count=answers[3];

    if(count===1){

        showResult(
            true,
            "符合自住住宅優惠稅率條件！",
            "您的房屋符合自住住宅基本條件，且本人、配偶及未成年子女全國合計僅1戶。",
            "1%"
        );

        document.getElementById("extraCheck").innerHTML=`
            <div class="success-box">
                ⭐ <strong>全國單一自住提醒</strong><br>
                如要適用1%優惠稅率，還須符合房屋現值及其他相關規定。
                請依房屋所在地地方稅稽徵機關規定確認。
            </div>
        `;

    }else{

        showResult(
            true,
            "符合自住住宅優惠稅率條件！",
            "您的房屋符合自住住宅基本條件，且本人、配偶及未成年子女全國合計房屋在3戶以內。",
            "1.2%"
        );

        document.getElementById("extraCheck").innerHTML="";
    }
}

function showResult(isSuccess,title,reason,rate=""){

    document.querySelectorAll(".step")
        .forEach(el=>el.classList.remove("active"));

    document.getElementById("navButtons").style.display="none";

    document.getElementById("progressBar").style.width="100%";
    document.getElementById("percentText").innerText="完成";
    document.getElementById("stepText").innerText="檢核完成";

    document.getElementById("result").classList.add("show");

    document.getElementById("resultIcon").innerText =
        isSuccess ? "🎉" : "❌";

    document.getElementById("resultTitle").innerText=title;

    document.getElementById("reason").innerHTML =
        "<strong>🔎 判斷結果</strong><br><br>"+reason;

    document.getElementById("rateArea").innerHTML =
        rate ? "<div class='rate'>"+rate+"</div>" : "";

    document.getElementById("resultDeadline").innerHTML =
        getDeadlineHTML();
}

function restart(){

    currentStep=1;
    answers={};

    document.getElementById("houseCount").value="";

    document.getElementById("result")
        .classList.remove("show");

    document.querySelectorAll(".option")
        .forEach(o=>o.classList.remove("selected"));

    document.getElementById("extraCheck").innerHTML="";

    showStep(1);
}

setDeadline();
showStep(1);

</script>

</body>
</html>
