<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FitPilot - Premium</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
    :root {
        --bg: #09090b;
        --surface: #18181b;
        --surface-hover: #27272a;
        --primary: #a3e635; /* Neon green */
        --primary-hover: #bef264;
        --text: #fafafa;
        --text-muted: #a1a1aa;
        --danger: #ef4444;
        --border: #3f3f46;
    }
    
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
    
    body {
        background-color: var(--bg);
        color: var(--text);
        padding-bottom: 80px; /* Space for nav */
        -webkit-font-smoothing: antialiased;
    }

    .header {
        background: linear-gradient(135deg, #18181b 0%, #09090b 100%);
        padding: 24px 20px;
        text-align: center;
        border-bottom: 1px solid var(--border);
        position: sticky;
        top: 0;
        z-index: 10;
        backdrop-filter: blur(10px);
    }
    
    .header h1 {
        font-size: 28px;
        font-weight: 800;
        background: -webkit-linear-gradient(0deg, var(--primary), #4ade80);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        letter-spacing: -1px;
    }

    .container {
        padding: 20px;
        max-width: 600px;
        margin: auto;
        animation: fadeIn 0.4s ease-out;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(10px); }
        to { opacity: 1; transform: translateY(0); }
    }

    .section-title {
        font-size: 18px;
        font-weight: 600;
        margin: 32px 0 16px;
        color: var(--text);
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .calendar-container {
        background: var(--surface);
        padding: 20px;
        border-radius: 20px;
        border: 1px solid var(--border);
        box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }

    .weekdays {
        display: grid;
        grid-template-columns: repeat(7, 1fr);
        gap: 8px;
        margin-bottom: 10px;
        text-align: center;
        font-size: 12px;
        color: var(--text-muted);
        font-weight: 600;
    }

    .calendar {
        display: grid;
        grid-template-columns: repeat(7, 1fr);
        gap: 8px;
    }

    .day {
        aspect-ratio: 1;
        background: var(--surface-hover);
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 12px;
        cursor: pointer;
        font-size: 14px;
        font-weight: 500;
        transition: all 0.2s;
        border: 1px solid transparent;
        user-select: none;
    }

    .day:hover { border-color: var(--primary); transform: translateY(-2px); }

    .day.active {
        background: var(--primary);
        color: var(--bg);
        box-shadow: 0 0 15px rgba(163, 230, 53, 0.4);
        border-color: var(--primary);
    }

    .card {
        background: var(--surface);
        padding: 18px;
        border-radius: 16px;
        margin-bottom: 12px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        border: 1px solid var(--border);
        transition: transform 0.2s;
    }
    
    .card:hover { transform: scale(1.02); border-color: #3f3f46; }

    .card-title { font-weight: 600; font-size: 16px; }
    .card-meta { color: var(--text-muted); font-size: 14px; background: var(--surface-hover); padding: 4px 10px; border-radius: 20px; }

    button {
        background: var(--primary);
        color: var(--bg);
        font-weight: 700;
        border: none;
        padding: 14px 20px;
        border-radius: 12px;
        cursor: pointer;
        font-size: 15px;
        width: 100%;
        transition: all 0.2s;
        box-shadow: 0 4px 14px rgba(163, 230, 53, 0.2);
    }

    button:hover {
        background: var(--primary-hover);
        transform: translateY(-2px);
    }

    button:active { transform: translateY(0); }

    .input-group {
        display: flex;
        gap: 10px;
        margin-bottom: 12px;
    }

    input {
        flex: 1;
        background: var(--surface);
        color: var(--text);
        padding: 14px;
        border-radius: 12px;
        border: 1px solid var(--border);
        font-size: 15px;
        outline: none;
        transition: border-color 0.2s;
    }

    input:focus { border-color: var(--primary); }

    .input-group button { width: auto; padding: 14px 24px; }

    .progress-card {
        background: linear-gradient(145deg, var(--surface) 0%, #111 100%);
        padding: 24px;
        border-radius: 20px;
        border: 1px solid var(--border);
        text-align: center;
        position: relative;
        overflow: hidden;
    }

    .streak-number {
        font-size: 48px;
        font-weight: 800;
        color: var(--primary);
        line-height: 1;
        margin: 10px 0;
        transition: transform 0.2s, color 0.2s;
    }

    .bar-bg {
        height: 8px;
        background: var(--surface-hover);
        border-radius: 4px;
        margin-top: 15px;
        overflow: hidden;
    }

    .bar {
        height: 100%;
        background: var(--primary);
        width: 0%;
        border-radius: 4px;
        transition: width 0.5s ease-out;
        box-shadow: 0 0 10px var(--primary);
    }

    .exercise-list {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 12px;
    }

    .exercise-pill {
        background: var(--surface);
        padding: 12px;
        border-radius: 12px;
        text-align: center;
        border: 1px solid var(--border);
        font-size: 14px;
        font-weight: 500;
        cursor: pointer;
        transition: all 0.2s;
    }
    
    .exercise-pill:hover {
        background: var(--surface-hover);
        border-color: var(--primary);
        color: var(--primary);
    }

    .nav {
        position: fixed;
        bottom: 0;
        left: 0;
        width: 100%;
        background: rgba(24, 24, 27, 0.85);
        backdrop-filter: blur(12px);
        border-top: 1px solid var(--border);
        display: flex;
        justify-content: space-around;
        padding: 12px 20px 24px;
        z-index: 100;
    }

    .nav-btn {
        background: none;
        color: var(--text-muted);
        box-shadow: none;
        width: auto;
        padding: 8px 16px;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 4px;
        font-size: 12px;
        font-weight: 500;
    }

    .nav-btn:hover { background: none; transform: none; color: var(--text); }
    
    .nav-btn.active { color: var(--primary); }
    
    .nav-btn svg { width: 24px; height: 24px; fill: currentColor; }

    #routine { min-height: 200px; }
    
    .empty-state { text-align: center; color: var(--text-muted); padding: 40px 0; font-size: 14px; }
</style>
</head>
<body>

<header class="header">
    <h1>FitPilot</h1>
</header>

<main class="container" id="home">
    <div class="progress-card">
        <div style="font-size: 14px; font-weight: 600; color: var(--text-muted); text-transform: uppercase; letter-spacing: 1px;">Current Streak</div>
        <div class="streak-number" id="streak">0</div>
        <div style="color: var(--text-muted); font-size: 14px;">Days in a row</div>
        <div class="bar-bg">
            <div class="bar" id="progressBar"></div>
        </div>
    </div>

    <div class="section-title">
        Gym Calendar
        <span style="font-size: 12px; color: var(--primary); font-weight: normal; cursor: pointer;" onclick="resetCalendar()">Reset</span>
    </div>
    <div class="calendar-container">
        <div class="weekdays">
            <span>S</span><span>M</span><span>T</span><span>W</span><span>T</span><span>F</span><span>S</span>
        </div>
        <div class="calendar" id="calendar"></div>
    </div>

    <div class="section-title">
        Today's Routine
        <span style="font-size: 20px; cursor: pointer; color: var(--primary);" onclick="generateRoutine()" title="Generate Routine">⟳</span>
    </div>
    <div id="routine">
        <div class="empty-state">No routine set. Click the refresh icon to generate or add exercises below.</div>
    </div>

    <div class="section-title">Add Exercise</div>
    <div class="input-group">
        <input type="text" id="exerciseName" placeholder="Exercise name..." autocomplete="off">
        <input type="number" id="exerciseTime" placeholder="Min" style="max-width: 90px;" min="1" autocomplete="off">
        <button onclick="addExercise()">Add</button>
    </div>
</main>

<main class="container" id="exercises" style="display:none">
    <div class="section-title">Exercise Library</div>
    <div class="exercise-list" id="exerciseLibrary"></div>
</main>

<nav class="nav">
    <button class="nav-btn active" id="nav-home" onclick="showPage('home')">
        <svg viewBox="0 0 24 24"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/></svg>
        Home
    </button>
    <button class="nav-btn" id="nav-exercises" onclick="showPage('exercises')">
        <svg viewBox="0 0 24 24"><path d="M20.57 14.86L22 13.43 20.57 12 17 15.57 8.43 7 12 3.43 10.57 2 9.14 3.43 7.71 2 5.57 4.14 4.14 2.71 2.71 4.14l1.43 1.43L2 7.71l1.43 1.43L2 10.57 3.43 12 7 8.43 15.57 17 12 20.57 13.43 22l1.43-1.43L16.29 22l2.14-2.14 1.43 1.43 1.43-1.43-1.43-1.43L22 16.29l-1.43-1.43z"/></svg>
        Library
    </button>
</nav>

<script>
    // State
    let streak = 0;
    const calendar = document.getElementById("calendar");
    const routineDiv = document.getElementById("routine");

    // Initialize Calendar (simulating 30 days starting on a random weekday)
    const emptyDays = 2; // Offset for visually realistic calendar
    for (let i = 0; i < emptyDays; i++) {
        let empty = document.createElement("div");
        calendar.appendChild(empty);
    }

    for (let i = 1; i <= 30; i++) {
        let day = document.createElement("div");
        day.className = "day";
        day.innerText = i;
        
        day.onclick = () => {
            if (day.classList.contains("active")) {
                day.classList.remove("active");
                streak = Math.max(0, streak - 1);
            } else {
                day.classList.add("active");
                streak++;
            }
            updateProgress();
        };
        calendar.appendChild(day);
    }

    function resetCalendar() {
        document.querySelectorAll('.day.active').forEach(d => d.classList.remove('active'));
        streak = 0;
        updateProgress();
    }

    function updateProgress() {
        // Animate streak counter
        const streakEl = document.getElementById("streak");
        streakEl.style.transform = "scale(1.2)";
        streakEl.style.color = "#fff";
        setTimeout(() => {
            streakEl.style.transform = "scale(1)";
            streakEl.style.color = "var(--primary)";
        }, 200);
        
        streakEl.innerText = streak;
        
        // Max realistic streak width is ~ 30 for this demo
        let percent = Math.min((streak / 30) * 100, 100);
        document.getElementById("progressBar").style.width = percent + "%";
    }

    const routines = [
        ["Bench Press", 45], ["Squats", 40], ["Deadlift", 35], 
        ["Pull Ups", 20], ["Shoulder Press", 30], ["Plank", 10], 
        ["Lunges", 20], ["Bicep Curls", 15], ["Tricep Dips", 15], 
        ["Leg Raises", 15]
    ];

    function generateRoutine() {
        routineDiv.innerHTML = "";
        
        // Pick 4 unique exercises
        let shuffled = [...routines].sort(() => 0.5 - Math.random());
        let selected = shuffled.slice(0, 4);

        selected.forEach((pick, index) => {
            createCard(pick[0], pick[1], index * 100);
        });
    }

    function addExercise() {
        let nameInput = document.getElementById("exerciseName");
        let timeInput = document.getElementById("exerciseTime");
        
        let name = nameInput.value.trim();
        let time = timeInput.value || 10;
        
        if (name === "") return;

        // Remove empty state if present
        if(routineDiv.querySelector('.empty-state')) {
            routineDiv.innerHTML = "";
        }

        createCard(name, time, 0);
        
        // Clear inputs
        nameInput.value = "";
        timeInput.value = "";
        nameInput.focus();
    }

    function createCard(name, time, delay) {
        let card = document.createElement("div");
        card.className = "card";
        card.style.animation = `fadeIn 0.3s ease-out ${delay}ms backwards`;
        card.innerHTML = `
            <span class="card-title">${name}</span>
            <span class="card-meta">${time} min</span>
        `;
        routineDiv.appendChild(card);
    }

    const library = [
        "Bench Press", "Squats", "Deadlift", "Pull Ups", "Push Ups", 
        "Plank", "Lunges", "Leg Press", "Shoulder Press", "Bicep Curls", 
        "Tricep Dips", "Russian Twists", "Mountain Climbers", "Burpees", 
        "Jump Rope", "Leg Raises", "Chest Fly", "Lat Pulldown", "Hip Thrust", "Calf Raises"
    ];

    const libraryDiv = document.getElementById("exerciseLibrary");

    library.forEach(e => {
        let item = document.createElement("div");
        item.className = "exercise-pill";
        item.innerText = e;
        item.onclick = () => {
            document.getElementById("exerciseName").value = e;
            showPage('home');
            window.scrollTo({top: document.body.scrollHeight, behavior: 'smooth'});
        };
        libraryDiv.appendChild(item);
    });

    function showPage(page) {
        document.getElementById("home").style.display = "none";
        document.getElementById("exercises").style.display = "none";
        document.getElementById(page).style.display = "block";
        
        // Update nav active state
        document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.remove('active'));
        document.getElementById('nav-' + page).classList.add('active');
        
        window.scrollTo(0, 0);
    }
</script>

</body>
</html>
