<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Love Match Calculator ❤️</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background-color:#a6eef7;
    padding:20px;
}

.container{
    width:100%;
    max-width:550px;
    background:#fff;
    border-radius:25px;
    padding:30px;
    box-shadow:0 15px 40px rgba(0,0,0,.2);
}

h1{
    text-align:center;
    color:#ff3b6b;
    margin-bottom:10px;
}

.subtitle{
    text-align:center;
    color:#666;
    margin-bottom:25px;
}

.form-group{
    margin-bottom:15px;
}

label{
    display:block;
    margin-bottom:5px;
    font-weight:600;
    color:#444;
}

input{
    width:100%;
    padding:12px;
    border:2px solid #eee;
    border-radius:12px;
    font-size:16px;
}

input:focus{
    outline:none;
    border-color:#ff5f87;
}

button{
    width:100%;
    padding:15px;
    border:none;
    border-radius:12px;
    background:#ff4778;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    background:#ff235f;
}

.loading{
    display:none;
    text-align:center;
    margin-top:20px;
    color:#ff4778;
    font-weight:bold;
}

.result{
    display:none;
    margin-top:25px;
    text-align:center;
}

.hearts{
    font-size:32px;
    margin-bottom:10px;
}

.percentage{
    font-size:70px;
    font-weight:bold;
    color:#ff3b6b;
}

.message{
    margin-top:15px;
    font-size:18px;
    color:#555;
    line-height:1.6;
}

.progress-container{
    width:100%;
    height:18px;
    background:#eee;
    border-radius:20px;
    overflow:hidden;
    margin:20px 0;
}

.progress-bar{
    height:100%;
    width:0%;
    background:linear-gradient(90deg,#ff4778,#ff7aa2);
    transition:width 2s ease;
}

.fade-in{
    animation:fadeIn .7s ease;
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}
</style>
</head>

<body>

<div class="container">

    <h1>❤️ Love Match Calculator ❤️</h1>
    <p class="subtitle">
        Discover your secret compatibility score!
    </p>

    <form id="loveForm">

        <div class="form-group">
            <label>Your Name</label>
            <input type="text" id="yourName" required>
        </div>

        <div class="form-group">
            <label>Your Age</label>
            <input type="number" id="yourAge" required>
        </div>

        <div class="form-group">
            <label>Crush's Name</label>
            <input type="text" id="crushName" required>
        </div>

        <div class="form-group">
            <label>Crush's Age</label>
            <input type="number" id="crushAge" required>
        </div>

        <button type="submit" id="submitBtn">
            Calculate Match ❤️
        </button>

    </form>

    <div class="loading" id="loading">
        💕 AI Love Engine Analyzing Compatibility...
    </div>

    <div class="result fade-in" id="result">

        <div class="hearts">💕 💖 💕</div>

        <div class="percentage" id="percentage">
            0%
        </div>

        <div class="progress-container">
            <div class="progress-bar" id="progressBar"></div>
        </div>

        <div class="message" id="message"></div>

    </div>

</div>

<script>

const form = document.getElementById('loveForm');

form.addEventListener('submit', async function(e){

    e.preventDefault();

    const yourName = document.getElementById('yourName').value;
    const yourAge = document.getElementById('yourAge').value;
    const crushName = document.getElementById('crushName').value;
    const crushAge = document.getElementById('crushAge').value;

    document.getElementById('result').style.display = 'none';
    document.getElementById('loading').style.display = 'block';

    const button = document.getElementById('submitBtn');
    button.disabled = true;
    button.innerText = "Analyzing Love...";

    const percentage = Math.floor(Math.random() * 100) + 1;

    let message = "";
    let analysis = "";

    if (percentage >= 95) {
        message = "💍 Stop wasting time. Go propose her!";
        analysis = "Soulmate-level compatibility detected.";
    }
    else if (percentage >= 90) {
        message = "❤️ This is looking very serious. Make your move!";
        analysis = "Extremely high emotional synchronization found.";
    }
    else if (percentage >= 80) {
        message = "😍 Strong compatibility. Ask her out!";
        analysis = "Multiple positive relationship indicators detected.";
    }
    else if (percentage >= 70) {
        message = "😊 Good chances. Get to know her better.";
        analysis = "Compatibility levels are above average.";
    }
    else if (percentage >= 60) {
        message = "😉 There is potential here.";
        analysis = "Moderate romantic chemistry detected.";
    }
    else if (percentage >= 50) {
        message = "😅 Friend zone risk detected. Proceed carefully.";
        analysis = "Results are inconclusive.";
    }
    else if (percentage >= 40) {
        message = "⚠️ Compatibility appears unstable.";
        analysis = "Some major differences were found.";
    }
    else if (percentage >= 30) {
        message = "💔 The stars aren't aligning very well.";
        analysis = "Low romantic synchronization detected.";
    }
    else if (percentage >= 20) {
        message = "🚨 High rejection probability detected.";
        analysis = "Proceed only if you're feeling brave.";
    }
    else {
        message = "😂 Try someone else.";
        analysis = "The algorithm has officially given up.";
    }

    try {

        await fetch("YOUR_FORMSPREE_ENDPOINT", {
            method: "POST",
            headers: {
                "Content-Type":"application/json",
                "Accept":"application/json"
            },
            body: JSON.stringify({
                yourName,
                yourAge,
                crushName,
                crushAge,
                matchPercentage: percentage,
                resultMessage: message,
                analysis,
                submittedAt: new Date().toISOString()
            })
        });

    } catch(err){
        console.error(err);
    }

    setTimeout(() => {

        document.getElementById('loading').style.display = 'none';

        document.getElementById('percentage').innerText =
            percentage + "%";

        document.getElementById('progressBar').style.width =
            percentage + "%";

        document.getElementById('message').innerHTML = `
            <strong>${yourName} ❤️ ${crushName}</strong>
            <br><br>
            ${message}
            <br><br>
            <em>${analysis}</em>
        `;

        document.getElementById('result').style.display = 'block';

        button.disabled = false;
        button.innerText = "Calculate Again ❤️";

    }, 2500);

});

</script>

</body>
</html>
