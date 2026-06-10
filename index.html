<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MyPortal — Login & Register</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=DM+Sans:wght@400;500&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: #f4f3f0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 2rem 1rem;
    }

    .card {
      background: #ffffff;
      border: 1px solid #e5e4e0;
      border-radius: 16px;
      padding: 2.5rem 2rem;
      width: 100%;
      max-width: 400px;
      box-shadow: 0 4px 24px rgba(0,0,0,0.06);
    }

    .logo {
      font-family: 'Playfair Display', serif;
      font-size: 24px;
      font-weight: 600;
      color: #1a1a1a;
      margin-bottom: 0.25rem;
    }

    .subtitle {
      font-size: 13px;
      color: #888;
      margin-bottom: 2rem;
    }

    .tabs {
      display: flex;
      border: 1px solid #e5e4e0;
      border-radius: 10px;
      overflow: hidden;
      margin-bottom: 1.75rem;
    }

    .tab {
      flex: 1;
      padding: 0.55rem;
      font-size: 14px;
      font-weight: 500;
      background: transparent;
      border: none;
      cursor: pointer;
      color: #888;
      font-family: 'DM Sans', sans-serif;
      transition: all 0.2s;
    }

    .tab.active {
      background: #EBF3FC;
      color: #185FA5;
    }

    label {
      font-size: 13px;
      color: #666;
      display: block;
      margin-bottom: 0.35rem;
      margin-top: 1rem;
    }

    input {
      width: 100%;
      padding: 0.6rem 0.75rem;
      border: 1px solid #d5d4d0;
      border-radius: 8px;
      font-size: 14px;
      font-family: 'DM Sans', sans-serif;
      background: #fff;
      color: #1a1a1a;
      outline: none;
      transition: border 0.2s, box-shadow 0.2s;
    }

    input:focus {
      border-color: #378ADD;
      box-shadow: 0 0 0 3px rgba(55,138,221,0.1);
    }

    .btn {
      width: 100%;
      margin-top: 1.5rem;
      padding: 0.7rem;
      background: #185FA5;
      color: #fff;
      border: none;
      border-radius: 8px;
      font-size: 14px;
      font-weight: 500;
      font-family: 'DM Sans', sans-serif;
      cursor: pointer;
      transition: opacity 0.2s;
    }

    .btn:hover { opacity: 0.88; }

    .err {
      font-size: 12px;
      color: #A32D2D;
      margin-top: 0.5rem;
      display: none;
      background: #FCEBEB;
      padding: 6px 10px;
      border-radius: 6px;
    }

    /* Sections */
    .section { display: none; }
    .section.active { display: block; }

    /* Welcome screen */
    .welcome { text-align: center; padding: 1rem 0; }

    .avatar {
      width: 64px;
      height: 64px;
      border-radius: 50%;
      background: #EBF3FC;
      color: #185FA5;
      font-size: 26px;
      font-weight: 600;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 1.25rem;
      font-family: 'Playfair Display', serif;
    }

    .welcome-name {
      font-family: 'Playfair Display', serif;
      font-size: 22px;
      color: #1a1a1a;
      margin-bottom: 0.5rem;
    }

    .welcome-msg {
      font-size: 14px;
      color: #888;
      line-height: 1.6;
      margin-bottom: 1.25rem;
    }

    .badge {
      display: inline-block;
      font-size: 12px;
      padding: 4px 14px;
      background: #EAF3DE;
      color: #3B6D11;
      border-radius: 20px;
      margin-bottom: 1.25rem;
      font-weight: 500;
    }

    .logout {
      width: 100%;
      padding: 0.55rem;
      background: transparent;
      border: 1px solid #d5d4d0;
      border-radius: 8px;
      font-size: 13px;
      color: #888;
      cursor: pointer;
      font-family: 'DM Sans', sans-serif;
      margin-top: 0.75rem;
      transition: background 0.2s;
    }

    .logout:hover { background: #f4f3f0; }

    .users-list {
      margin-top: 1.25rem;
      padding-top: 1.25rem;
      border-top: 1px solid #e5e4e0;
      text-align: left;
    }

    .users-title {
      font-size: 12px;
      color: #aaa;
      margin-bottom: 0.75rem;
    }

    .user-row {
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 6px 0;
      border-bottom: 1px solid #f0efeb;
    }

    .user-row:last-child { border: none; }

    .user-dot {
      width: 28px;
      height: 28px;
      border-radius: 50%;
      background: #f0efeb;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 11px;
      font-weight: 500;
      color: #666;
    }

    .user-info { font-size: 13px; color: #1a1a1a; }
    .user-time { font-size: 11px; color: #aaa; margin-left: auto; }
  </style>
</head>
<body>

<div class="card">
  <div class="logo">MyPortal</div>
  <div class="subtitle">Your personal space — log in or create an account</div>

  <div class="tabs" id="tabs">
    <button class="tab active" onclick="switchTab('login')">Log in</button>
    <button class="tab" onclick="switchTab('register')">Register</button>
  </div>

  <!-- Login Section -->
  <div class="section active" id="sec-login">
    <label for="l-email">Email</label>
    <input type="email" id="l-email" placeholder="you@example.com" />

    <label for="l-pass">Password</label>
    <input type="password" id="l-pass" placeholder="••••••••" />

    <div class="err" id="l-err">Incorrect email or password. Please try again.</div>
    <button class="btn" onclick="doLogin()">Log in</button>
  </div>

  <!-- Register Section -->
  <div class="section" id="sec-register">
    <label for="r-name">Full name</label>
    <input type="text" id="r-name" placeholder="Jane Doe" />

    <label for="r-email">Email</label>
    <input type="email" id="r-email" placeholder="you@example.com" />

    <label for="r-pass">Password</label>
    <input type="password" id="r-pass" placeholder="Min. 6 characters" />

    <div class="err" id="r-err">Please fill in all fields (password min. 6 characters).</div>
    <div class="err" id="r-dup">This email is already registered.</div>
    <button class="btn" onclick="doRegister()">Create account</button>
  </div>

  <!-- Welcome Section -->
  <div class="section" id="sec-welcome">
    <div class="welcome">
      <div class="avatar" id="w-avatar">?</div>
      <div class="badge" id="w-badge">✓ Logged in</div>
      <div class="welcome-name" id="w-name">Welcome!</div>
      <div class="welcome-msg" id="w-msg">Great to have you here.</div>
      <div class="users-list" id="users-list"></div>
      <button class="logout" onclick="doLogout()">Sign out</button>
    </div>
  </div>
</div>

<script>
  // Load saved users from localStorage
  let users = JSON.parse(localStorage.getItem('mp_users') || '[]');
  let currentUser = null;

  function switchTab(t) {
    const isLogin = t === 'login';
    document.querySelectorAll('.tab').forEach((el, i) => el.classList.toggle('active', i === (isLogin ? 0 : 1)));
    document.getElementById('sec-login').classList.toggle('active', isLogin);
    document.getElementById('sec-register').classList.toggle('active', !isLogin);
    document.getElementById('l-err').style.display = 'none';
    document.getElementById('r-err').style.display = 'none';
    document.getElementById('r-dup').style.display = 'none';
  }

  function showWelcome(user, isNew) {
    document.getElementById('tabs').style.display = 'none';
    document.getElementById('sec-login').classList.remove('active');
    document.getElementById('sec-register').classList.remove('active');
    document.getElementById('sec-welcome').classList.add('active');

    document.getElementById('w-avatar').textContent = user.name.charAt(0).toUpperCase();
    document.getElementById('w-name').textContent = 'Welcome, ' + user.name.split(' ')[0] + '!';
    document.getElementById('w-badge').textContent = isNew ? '✓ Account created' : '✓ Logged in';
    document.getElementById('w-msg').textContent = isNew
      ? 'Your account has been created successfully. You are all set to go!'
      : 'Good to see you back. Everything looks great on your end.';

    const list = document.getElementById('users-list');
    if (users.length > 1) {
      list.innerHTML = '<div class="users-title">Registered members (' + users.length + ')</div>';
      users.forEach(u => {
        const d = document.createElement('div');
        d.className = 'user-row';
        d.innerHTML = '<div class="user-dot">' + u.name.charAt(0).toUpperCase() + '</div>'
          + '<span class="user-info">' + u.name + '</span>'
          + '<span class="user-time">' + u.joined + '</span>';
        list.appendChild(d);
      });
    } else {
      list.innerHTML = '';
    }
  }

  function doLogin() {
    const email = document.getElementById('l-email').value.trim();
    const pass  = document.getElementById('l-pass').value;
    const user  = users.find(u => u.email === email && u.password === pass);
    document.getElementById('l-err').style.display = user ? 'none' : 'block';
    if (user) { currentUser = user; showWelcome(user, false); }
  }

  function doRegister() {
    const name  = document.getElementById('r-name').value.trim();
    const email = document.getElementById('r-email').value.trim();
    const pass  = document.getElementById('r-pass').value;

    document.getElementById('r-err').style.display = 'none';
    document.getElementById('r-dup').style.display = 'none';

    if (!name || !email || pass.length < 6) {
      document.getElementById('r-err').style.display = 'block';
      return;
    }
    if (users.find(u => u.email === email)) {
      document.getElementById('r-dup').style.display = 'block';
      return;
    }

    const joined = new Date().toLocaleDateString('en-GB', { day: 'numeric', month: 'short' });
    const user = { name, email, password: pass, joined };
    users.push(user);
    localStorage.setItem('mp_users', JSON.stringify(users));
    currentUser = user;
    showWelcome(user, true);
  }

  function doLogout() {
    currentUser = null;
    document.getElementById('tabs').style.display = 'flex';
    document.getElementById('sec-welcome').classList.remove('active');
    document.getElementById('sec-login').classList.add('active');
    document.querySelectorAll('.tab').forEach((el, i) => el.classList.toggle('active', i === 0));
    document.getElementById('l-email').value = '';
    document.getElementById('l-pass').value = '';
  }
</script>

</body>
</html>
