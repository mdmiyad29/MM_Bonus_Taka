<!DOCTYPE html>
<html>
<head>
    <title>MM Bonus Taka</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: Arial, sans-serif; background: #e2f0d9; margin: 0; padding: 0; }
        .container { max-width: 500px; margin: 40px auto; background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.15);}
        h1 { color: #28a745; text-align: center; }
        input[type=text], input[type=number] { width: 90%; padding: 12px; margin: 15px auto; display: block; font-size: 16px; border: 1px solid #ccc; border-radius: 6px; }
        button { background: #28a745; color: white; padding: 14px 25px; margin: 10px; border: none; border-radius: 8px; cursor: pointer; font-size: 18px; width: 90%; }
        button:hover { background: #218838; }
        #points { font-size: 20px; font-weight: bold; margin-top: 15px; text-align: center; }
        #message { font-size: 16px; text-align: center; margin-top: 10px; color: #333; }
        .hide { display: none; }
        .footer { text-align: center; color: gray; margin-top: 30px; font-size: 14px; }
        .pay-info { text-align: center; margin-top: 10px; font-weight: bold; color: #155724; background: #d4edda; padding: 10px; border-radius: 8px; }
    </style>
</head>
<body>

<div class="container" id="loginScreen">
    <h1>MM Bonus Taka</h1>
    <p style="text-align:center;">Enter your username to start earning points:</p>
    <input type="text" id="username" placeholder="Enter your name">
    <button onclick="login()">Start</button>
</div>

<div class="container hide" id="mainApp">
    <h1>Welcome, <span id="userDisplay"></span>!</h1>
    
    <button onclick="spin()">🎰 Spin & Earn Points</button>
    <button onclick="scratch()">🎟 Scratch Card</button>
    
    <input type="number" id="depositAmount" placeholder="Enter points to deposit">
    <button onclick="deposit()">💰 Deposit Points</button>
    
    <div class="pay-info">Pay to this number: 01931692088 (বিকাশ/নগদ/রকেট)</div>
    
    <button onclick="withdraw()">💵 Withdraw Points</button>
    
    <div id="points">Total Points: 0</div>
    <div id="message"></div>
    
    <div class="footer">Earn 15,000 points to withdraw 100৳! Payment processed within 24 hours.</div>
</div>

<script>
    let points = 0;

    function login() {
        let username = document.getElementById('username').value.trim();
        if (username === '') {
            alert('Please enter your name.');
            return;
        }
        document.getElementById('userDisplay').innerText = username;
        document.getElementById('loginScreen').classList.add('hide');
        document.getElementById('mainApp').classList.remove('hide');
    }

    function spin() {
        let earn = Math.floor(Math.random() * 51) + 5;
        points += earn;
        updateDisplay(`You earned ${earn} points from Spin!`);
    }

    function scratch() {
        let earn = Math.floor(Math.random() * 101) + 10;
        points += earn;
        updateDisplay(`You scratched ${earn} points!`);
    }
    
    function deposit() {
        let dep = parseInt(document.getElementById('depositAmount').value);
        if (isNaN(dep) || dep <= 0) {
            alert('Please enter a valid deposit amount.');
            return;
        }
        points += dep;
        updateDisplay(`You deposited ${dep} points!`);
        document.getElementById('depositAmount').value = '';
    }

    function withdraw() {
        if(points >= 15000){
            updateDisplay('✅ Withdraw request sent! You will receive 100৳ within 24 hours.');
            points = 0;
        } else {
            updateDisplay('❌ Not enough points. Earn 15,000 points to withdraw.');
        }
    }

    function updateDisplay(message){
        document.getElementById('points').innerText = 'Total Points: ' + points;
        document.getElementById('message').innerText = message;
    }
</script>

</body>
</html>
