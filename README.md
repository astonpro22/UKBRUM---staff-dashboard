
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

<!-- GENERAL MESSAGES -->
<h3>General Moderation Messages</h3>

<div class="box">
    <div class="text">Hello, i am Name a Rank here at UKBRUM. (If i am late say "Late" or "Void")</div>
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
    <div class="text" id="warnText">
        You are going to be receiving a warning for Reason, appeal via communication server UKBRUM.
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

<!-- KICK -->
<h3>Kick</h3>
<input type="text" id="kickReason" placeholder="Enter Kick Reason...">

<div class="box">
    <div class="text" id="kickText">
        You are going to be receiving a Kick for Reason do not join back for 20 minutes or you will be banned, appeal via communication server UKBRUM.
    </div>
    <button onclick="copyText(this)">Copy</button>
</div>

<!-- BAN -->
<h3>Ban</h3>
<input type="text" id="banReason" placeholder="Enter Ban Reason...">

<div class="box">
    <div class="text" id="banText">
        You are going to be receiving a Ban for Reason appeal via communication server UKBRUM.
    </div>
    <button onclick="copyText(this)">Copy</button>
	

</div>

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
<div class="box"><div class="text">:h 🚨 Unsatisfied with staff performance? Report them via our communications server! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 📬 Need assistance? Call !mod or !help to get staff attention!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ☀️ Leave a review about staff members in our communications! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚗 Please note: we drive according to the map layout (right-hand side).</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ⚠️ We aim for realistic roleplay. Failing to roleplay properly will result in staff action!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚙 Please clear (area)! Failing to do so within the next few minutes may result in being removed from the scene!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚓 A police checkpoint is being hosted at the police station. Please ensure you have the correct gear to pass through!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🤿 Dive into immersive roleplay with us! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🎯 Birmingham Roleplay offers a unique roleplaying experience. Start with us! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ✋ Seen a rule breaker? Call !mod or !help to alert staff.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ⭐️ Start your roleplay journey with Birmingham Roleplay! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>

<h3>Jobs</h3>

<div class="box"><div class="text">:h 🚖 Looking for a ride? There is a luxurious limousine ready to take you anywhere you want!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚖 Looking for a ride? Well the taxi company is now open! Call them.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚖 Looking for a ride? Well the Metro Bus is now active. Wait at a bus stop to hop on!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🏀 There is a basketball game happening at the basketball court! Come on over to play!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ⛽ River City Gas-N-Go is now open get some gas and food for the road trip.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🔫 River City Guns and Ammo is now open. Get some weapons and use them properly though.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🏦 Bank of River City is now open. Head over there to deposit some money.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🚗 The Mod Shop in River City is now open! Head over there to get an oil change, new paint job, and rims or just repair your car.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🧰 The Tool Store is now open. Grab some tools.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🏥 Need a check-up or need medicine? The hospital is currently open for all of those things!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 📱 Want a new phone? The Gadget Shack is open!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🍔 Three Guys is now open. Head over there for some delicious food.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🌮 La Mesa is now open. Head over there for some Mexican food.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ☕ Liberty Cafe is now open. Head over there for some coffee and more.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 💎 The Jewelry Store Is now open! Get yourself something nice!</div><button onclick="copyText(this)">Copy</button></div>

<h3>Staff Applications</h3>

<div class="box"><div class="text">:h 🛑 Step Up and Make a Difference — Staff Wanted! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🔊 Be the Voice Behind the Server’s Success! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ⚒️ Staff Wanted: Make Moves, Make Impact! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🌍 Many Roles, One Goal — Staff Together! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h ✨ Be the Change, Be Our Staff! Join us today, Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 💪 Strong Communities, Need Strong Staff! Apply Today! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 🔧 Help Players, Solve Problems, Make Change! Apply Today! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:h 💼 Staff Applications are Open! Take your chance today and unlock a world of opportunities! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>

<h3>:m Commands</h3>

<div class="box"><div class="text">:m 🎮 We value your roleplay experience! Avoid unnecessary issues to help keep things realistic.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🤔 WAIT! Have you joined our communications server? Enjoy a wide range of new experiences! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🎲 We have more options than a dice roll. Choose us today! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 👋 Take your roleplay to the next level! Join our communications today! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 📬 We’re hiring staff members! Start your career with us. Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🚓 Interested in policing and realistic departments? Apply via our communications! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 📌 It’s not about the quantity of roleplays — it’s about quality! Join us today. Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 👮 Explore a wide range of departments to grow your career in! Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🍔 Three Guys is now open! Want fries? Come down to Three Guys!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m ☕ Liberty Cafe is now open! Come down for a warm hot chocolate!</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🌯 LaMesa is now open! Come down for the best tacos in Birmingham.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 👀 Style your avatar with Birmingham Roleplay merch! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🫵 We value our community — be part of the journey with us! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🚓 Help protect the streets of Birmingham by applying to become whitelisted! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🔫 Armed Response Unit applications are now open! Join the team before applications close. Communications Code: UKBRUM.</div><button onclick="copyText(this)">Copy</button></div>
<div class="box"><div class="text">:m 🤿 Dive into immersive roleplay with us! Communications Code: UKBRUM</div><button onclick="copyText(this)">Copy</button></div>

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
Notice: This Website was made by "Panther_cattreats", If they any issues reach out via DMs!
</p>

</div>

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

function updateReasons() {
    const reason = document.getElementById('reasonInput').value || "Reason";
    document.querySelectorAll('[data-template]').forEach(el=>{
        el.innerText = el.dataset.template.replace('[Reason]', reason);
    });
}

document.getElementById('reasonInput').addEventListener('input', updateReasons);
updateReasons();
</script>

</body>
</html>
 
