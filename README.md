<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Birmingham Systems</title>
<style>
    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
        background: linear-gradient(135deg, #0a0a0a, #8b0000);
        color: #fff;
    }

    header {
        text-align: center;
        padding: 20px;
        font-size: 32px;
        font-weight: bold;
        background: linear-gradient(90deg, #000, #b30000);
        border-bottom: 2px solid #ff0000;
    }

    .tabs {
        display: flex;
        justify-content: center;
        background: #111;
    }

    .tab {
        padding: 15px 25px;
        cursor: pointer;
        color: #ccc;
        border-bottom: 3px solid transparent;
    }

    .tab.active {
        color: #fff;
        border-bottom: 3px solid red;
        background: #1a1a1a;
    }

    .content {
        display: none;
        padding: 25px;
        max-width: 1000px;
        margin: auto;
    }

    .content.active {
        display: block;
    }

    .reason-box {
        margin-bottom: 20px;
    }

    input {
        width: 100%;
        padding: 10px;
        border-radius: 6px;
        border: none;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .box {
        background: linear-gradient(145deg, #111, #1f0000);
        border: 1px solid #ff0000;
        border-radius: 10px;
        padding: 15px;
        margin-bottom: 15px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 15px;
    }

    .text {
        flex: 1;
        white-space: pre-wrap;
    }

    button {
        background: red;
        color: #fff;
        border: none;
        border-radius: 6px;
        padding: 8px 14px;
        cursor: pointer;
        font-weight: bold;
    }

    button:hover {
        background: darkred;
    }

    table {
        width: 100%;
        border-collapse: collapse;
    }

    th, td {
        border: 1px solid red;
        padding: 10px;
        text-align: left;
        color: #fff;
    }

    th {
        background: #300000;
    }

</style>
</head>
<body>

<header>Birmingham Systems</header>

<div class="tabs">
    <div class="tab active" onclick="openTab(0)">Moderation</div>
    <div class="tab" onclick="openTab(1)">H & M Commands</div>
    <div class="tab" onclick="openTab(2)">Official Punishment Guide</div>
</div>

<!-- MODERATION TAB -->
<div class="content active">

<h2>Moderation</h2>

<!-- Editable Name and Rank -->
<h3>Set out like this: Hello, i am Flop a Trial moderator Here at UKBRUM. (If i am late say "Late" or "Void")</h3>
<input type="text" id="staffNameRank" placeholder="Enter your name and rank...">

<!-- GENERAL MESSAGES -->
<div class="box">
    <div class="text" id="greetingMessage">
        Hello, I am Name a Rank here at UKBRUM. (If i am late say "Late" or "Void")
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

<div class="box">
    <div class="text">Do you have any video evidence?</div>
    <button onclick="copyText(this)">Copy</button>
</div>

<div class="box">
    <div class="text">Can you please send the video evidence into "Ingame-proof" so I can review it.</div>
    <button onclick="copyText(this)">Copy</button>
</div>

<div class="box">
    <div class="text">I am sorry without any video evidence I cannot hand out any disciplinary action.</div>
    <button onclick="copyText(this)">Copy</button>
</div>

<div class="box">
    <div class="text">Do you require any more assistance?</div>
    <button onclick="copyText(this)">Copy</button>
</div>

<div class="box">
    <div class="text">
        Thank you for using our help service! Leave a review if you would like via "staff-feedback".
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

<hr style="border-color:red; margin:30px 0;">

<!-- WARNING -->
<h3>Warning</h3>
<input type="text" id="warnReason" placeholder="Enter Warning Reason...">

<div class="box">
    <div class="text" id="warnText" data-template="You are going to be receiving a warning for [Reason], appeal via communication server UKBRUM.">
        You are going to be receiving a warning for Reason, appeal via communication server UKBRUM.
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

<!-- KICK -->
<h3>Kick</h3>
<input type="text" id="kickReason" placeholder="Enter Kick Reason...">

<div class="box">
    <div class="text" id="kickText" data-template="You are going to be receiving a Kick for [Reason] do not join back for 20 minutes or you will be banned, appeal via communication server UKBRUM.">
        You are going to be receiving a Kick for Reason do not join back for 20 minutes or you will be banned, appeal via communication server UKBRUM.
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

<!-- BAN -->
<h3>Ban</h3>
<input type="text" id="banReason" placeholder="Enter Ban Reason...">

<div class="box">
    <div class="text" id="banText" data-template="You are going to be receiving a Ban for [Reason] appeal via communication server UKBRUM.">
        You are going to be receiving a Ban for Reason appeal via communication server UKBRUM.
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

</div>

<!-- H & M COMMANDS -->
<div class="content">
<h2>H / M Commands</h2>
<p style="color:#ffb3b3;">Props to Alfie_Alb for providing this information!</p>

<h3>:h Commands</h3>
<div class="box"><div class="text">:h ⚠️ No excuse for abuse. We do not tolerate any player disrespecting others in our community — action will be taken if seen.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚨 Step into the action – Realistic roleplay, endless possibilities! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚙 Please do not leave your car unattended in the middle of the road unless roleplaying. Disrupting other roleplays is not allowed!</div><button onclick="copyText(this)">Copy</button></div>
<!-- Continue all other H/M commands as in your original script... -->
</div>

<!-- PUNISHMENT GUIDE -->
<div class="content">

<h2 style="text-align:center; margin-bottom:20px;">
IN-GAME PUNISHMENT GUIDEBOOK
</h2>

<table>
<tr>
    <th>Offences</th>
    <th>Action</th>
    <th>Side Action</th>
</tr>
<tr><td>Unrealistic avatar</td><td>Warning</td><td>Load/Refresh</td></tr>
<tr><td>Interrupting scenes</td><td>Warning</td><td>Load/Refresh</td></tr>
<tr><td>RDM / VDM</td><td>Warning</td><td>No Side Actions</td></tr>
<tr><td>Cop Baiting / Metagaming</td><td>Warning</td><td>Load/Refresh</td></tr>
<tr><td>FRP</td><td>Warning</td><td>Load/Refresh</td></tr>
<tr><td>GTA Driving</td><td>Warning</td><td>Load/Refresh</td></tr>
<tr><td>No permissions</td><td>Warning</td><td>Refresh</td></tr>
<tr><td>Disrespect</td><td>Kick</td><td>No Side Actions</td></tr>
<tr><td>NLR</td><td>Warning</td><td>Refresh</td></tr>
<tr><td>Not Trained</td><td>Warning</td><td>Jail/Wanted</td></tr>
<tr><td>Breaking Priority</td><td>Kick</td><td>No Side Actions</td></tr>
<tr><td>Breaking Safezones</td><td>Kick</td><td>No Side Actions</td></tr>
<tr><td>Staff Evasion / VDM / RDM</td><td>Kick</td><td>No Side Actions</td></tr>
<tr><td>Car Blockage</td><td>Warning</td><td>Jail/Wanted</td></tr>
<tr><td>Staff Impersonation</td><td>Instant Ban</td><td>No Side Actions</td></tr>
<tr><td>Breaking TOS</td><td>Instant Ban</td><td>No Side Actions</td></tr>
<tr><td>Major Events</td><td>Instant Ban</td><td>No Side Actions</td></tr>
<tr><td>L-Tap / NITRP</td><td>Instant Ban</td><td>No Side Actions</td></tr>
<tr><td>Raiding</td><td>Instant Ban</td><td>No Side Actions</td></tr>
</table>

<p style="margin-top:15px; text-align:center; color:#ffb3b3;">
Notice: This Website was made by "Panther_cattreats", If there are any issues reach out via DMs!
</p>

</div>

<script>
function openTab(index) {
    document.querySelectorAll('.tab').forEach((t,i)=>t.classList.toggle('active', i===index));
    document.querySelectorAll('.content').forEach((c,i)=>c.classList.toggle('active', i===index));
}

function copyText(btn) {
    const text = btn.parentElement.querySelector('.text').innerText;
    navigator.clipboard.writeText(text);
}

// Update greeting message for staff name/rank input
const staffInput = document.getElementById('staffNameRank');
const greetingMessage = document.getElementById('greetingMessage');
staffInput.addEventListener('input', () => {
    const val = staffInput.value.trim() || 'Name a Rank';
    greetingMessage.innerText = `Hello, I am ${val} here at UKBRUM. (If i am late say "Late" or "Void")`;
});

// Function to update individual reason messages
function updateReason(inputId, textId) {
    const input = document.getElementById(inputId);
    const textEl = document.getElementById(textId);
    const template = textEl.getAttribute('data-template');
    input.addEventListener('input', () => {
        const reason = input.value.trim() || 'Reason';
        textEl.innerText = template.replace('[Reason]', reason);
    });
}

// Initialize all reason inputs
updateReason('warnReason', 'warnText');
updateReason('kickReason', 'kickText');
updateReason('banReason', 'banText');

</script>

</body>
</html>
