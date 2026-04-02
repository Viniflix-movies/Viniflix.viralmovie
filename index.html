<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Viniflix 🔥 - Premium Movie Streaming</title>

<!-- Google AdSense/AdMob SDK -->
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6353438920437702" crossorigin="anonymous"></script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #0a0a0a;
  color: #ffffff;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  overflow-x: hidden;
  padding-bottom: 130px;
}

/* Loading Overlay */
#loadingOverlay {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0,0,0,0.9);
  display: none;
  justify-content: center;
  align-items: center;
  z-index: 9999;
}

.spinner {
  width: 50px;
  height: 50px;
  border: 5px solid #333;
  border-top-color: #ff0000;
  border-radius: 50%;
  animation: spin 1s linear infinite;
}

@keyframes spin {
  to { transform: rotate(360deg); }
}

/* Toast Notification */
.toast {
  position: fixed;
  bottom: 130px;
  left: 50%;
  transform: translateX(-50%);
  background: rgba(0,0,0,0.95);
  color: white;
  padding: 12px 24px;
  border-radius: 50px;
  z-index: 9998;
  animation: slideUp 0.3s ease;
  border-left: 4px solid #ff0000;
  font-size: 14px;
  white-space: nowrap;
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

@keyframes slideUp {
  from {
    transform: translateX(-50%) translateY(100px);
    opacity: 0;
  }
  to {
    transform: translateX(-50%) translateY(0);
    opacity: 1;
  }
}

/* Ad Modal */
.ad-modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0,0,0,0.95);
  z-index: 10000;
  justify-content: center;
  align-items: center;
  animation: fadeIn 0.3s ease;
}

.ad-modal-content {
  background: linear-gradient(135deg, #1a1a1a, #0a0a0a);
  border-radius: 20px;
  max-width: 350px;
  width: 90%;
  padding: 25px;
  text-align: center;
  border: 2px solid #ff0000;
}

.ad-video-container {
  background: #000;
  border-radius: 12px;
  overflow: hidden;
  margin: 15px 0;
  min-height: 180px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.ad-video {
  width: 100%;
  max-height: 250px;
  object-fit: cover;
}

.ad-timer {
  font-size: 48px;
  font-weight: bold;
  color: #ff0000;
  margin: 10px 0;
}

.ad-progress {
  width: 100%;
  height: 4px;
  background: #333;
  border-radius: 2px;
  overflow: hidden;
  margin: 10px 0;
}

.ad-progress-bar {
  height: 100%;
  background: linear-gradient(90deg, #ff0000, #ff6b6b);
  width: 0%;
  transition: width 0.1s linear;
}

.ad-claim-btn {
  background: #ff0000;
  color: white;
  border: none;
  padding: 12px 24px;
  border-radius: 25px;
  font-weight: bold;
  cursor: pointer;
  opacity: 0.5;
  pointer-events: none;
}

.ad-claim-btn.active {
  opacity: 1;
  pointer-events: auto;
}

/* Banner Carousel */
.banner-carousel {
  position: relative;
  width: calc(100% - 20px);
  margin: 10px auto;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

.carousel-container {
  position: relative;
  width: 100%;
  overflow: hidden;
}

.carousel-slides {
  display: flex;
  transition: transform 0.5s ease-in-out;
}

.carousel-slide {
  min-width: 100%;
  flex-shrink: 0;
  position: relative;
  background-size: cover;
  background-position: center;
  min-height: 200px;
  display: flex;
  align-items: flex-end;
  justify-content: flex-start;
}

.carousel-slide::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0,0,0,0.4);
}

.carousel-slide .slide-content {
  position: relative;
  z-index: 2;
  background: linear-gradient(to top, rgba(0,0,0,0.85), transparent);
  width: 100%;
  padding: 20px;
}

.carousel-slide .slide-title {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 5px;
  color: #ffffff;
}

.carousel-slide .slide-message {
  font-size: 14px;
  opacity: 0.95;
  color: #ffffff;
  margin-bottom: 8px;
}

.carousel-slide .slide-link {
  display: inline-block;
  margin-top: 8px;
  background: linear-gradient(45deg, #ff0000, #cc0000);
  padding: 6px 20px;
  border-radius: 20px;
  font-size: 12px;
  font-weight: bold;
  cursor: pointer;
  transition: transform 0.2s;
  border: none;
  color: white;
}

.carousel-slide .slide-link:active {
  transform: scale(0.95);
}

.carousel-prev,
.carousel-next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.5);
  color: white;
  border: none;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  cursor: pointer;
  z-index: 10;
  font-size: 20px;
  transition: all 0.3s;
}

.carousel-prev:hover,
.carousel-next:hover {
  background: rgba(255,0,0,0.7);
}

.carousel-prev {
  left: 10px;
}

.carousel-next {
  right: 10px;
}

.carousel-dots {
  position: absolute;
  bottom: 10px;
  left: 0;
  right: 0;
  display: flex;
  justify-content: center;
  gap: 8px;
  z-index: 10;
}

.carousel-dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: rgba(255,255,255,0.5);
  cursor: pointer;
  transition: all 0.3s;
}

.carousel-dot.active {
  background: #ff0000;
  width: 20px;
  border-radius: 10px;
}

/* Login Page */
#loginPage {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 40px 20px;
  background: linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%);
  overflow-y: auto;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: center;
}

.login-container {
  max-width: 400px;
  margin: 0 auto;
  width: 100%;
}

.logo {
  text-align: center;
  margin-bottom: 40px;
}

.logo h1 {
  font-size: 2.5em;
  background: linear-gradient(45deg, #ff0000, #ff6b6b);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.logo p {
  color: #888;
  margin-top: 10px;
}

.input-group {
  margin-bottom: 15px;
}

.input-group input {
  width: 100%;
  padding: 15px;
  border-radius: 12px;
  border: 2px solid #333;
  background: #1a1a1a;
  color: white;
  font-size: 16px;
}

.input-group input:focus {
  outline: none;
  border-color: #ff0000;
}

.btn-primary {
  width: 100%;
  padding: 15px;
  border-radius: 12px;
  border: none;
  background: linear-gradient(45deg, #ff0000, #cc0000);
  color: white;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  margin-top: 10px;
}

.btn-primary:active {
  transform: scale(0.98);
}

.btn-secondary {
  width: 100%;
  padding: 15px;
  border-radius: 12px;
  border: 2px solid #ff0000;
  background: transparent;
  color: #ff0000;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  margin-top: 10px;
}

.divider {
  text-align: center;
  margin: 20px 0;
  color: #666;
  position: relative;
}

.divider::before,
.divider::after {
  content: '';
  position: absolute;
  top: 50%;
  width: 45%;
  height: 1px;
  background: #333;
}

.refer-code-input {
  margin-top: 20px;
  padding: 15px;
  background: rgba(255,255,255,0.05);
  border-radius: 12px;
  border: 1px solid #333;
}

.refer-code-input label {
  font-size: 14px;
  color: #ffaa00;
  display: block;
  margin-bottom: 8px;
}

/* Download App Button */
.download-btn {
  background: linear-gradient(45deg, #25D366, #128C7E);
  color: white;
  text-align: center;
  padding: 14px;
  border-radius: 30px;
  margin: 15px 0;
  font-weight: bold;
  cursor: pointer;
  font-size: 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  border: none;
  width: 100%;
  transition: transform 0.2s;
}

.download-btn:active {
  transform: scale(0.98);
}

/* Pages */
.page {
  display: none;
  padding-bottom: 70px;
  min-height: 100vh;
  background: #0a0a0a;
}

/* Navbar */
.nav {
  position: fixed;
  bottom: 0;
  width: 100%;
  display: flex;
  background: rgba(17,17,17,0.95);
  backdrop-filter: blur(10px);
  border-top: 1px solid #333;
  z-index: 100;
}

.nav button {
  flex: 1;
  background: none;
  color: #888;
  border: none;
  padding: 12px;
  font-size: 14px;
  font-weight: bold;
  cursor: pointer;
  transition: all 0.3s;
}

.nav button.active {
  color: #ff0000;
}

/* Header */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px;
  background: rgba(0,0,0,0.8);
  backdrop-filter: blur(10px);
  position: sticky;
  top: 0;
  z-index: 99;
  border-bottom: 1px solid #333;
}

.header h2 {
  font-size: 18px;
  background: linear-gradient(45deg, #ff0000, #ff6b6b);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.logout-btn {
  background: rgba(255,0,0,0.2);
  border: 1px solid #ff0000;
  color: #ff0000;
  padding: 8px 16px;
  border-radius: 20px;
  cursor: pointer;
  font-size: 14px;
}

/* Search Bar */
.search-container {
  padding: 15px;
}

.search-box {
  display: flex;
  gap: 10px;
  background: #1a1a1a;
  border-radius: 25px;
  padding: 5px 15px;
  border: 1px solid #333;
}

.search-box input {
  flex: 1;
  background: transparent;
  border: none;
  padding: 12px;
  color: white;
  font-size: 16px;
  outline: none;
}

.search-box button {
  background: #ff0000;
  border: none;
  border-radius: 20px;
  padding: 8px 20px;
  color: white;
  font-weight: bold;
  cursor: pointer;
}

/* Movies Grid */
.movies-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
  gap: 15px;
  padding: 15px;
}

.movie-card {
  background: linear-gradient(135deg, #1a1a1a, #0f0f0f);
  border-radius: 12px;
  overflow: hidden;
  cursor: pointer;
  transition: transform 0.3s;
  border: 1px solid #333;
}

.movie-card:active {
  transform: scale(0.98);
}

.movie-card:hover {
  transform: translateY(-5px);
  border-color: #ff0000;
}

.movie-poster {
  width: 100%;
  height: 200px;
  background: linear-gradient(135deg, #2a2a2a, #1a1a1a);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 48px;
  overflow: hidden;
}

.movie-poster img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.movie-info {
  padding: 10px;
}

.movie-title {
  font-weight: bold;
  font-size: 14px;
  margin-bottom: 5px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.movie-year {
  font-size: 11px;
  color: #888;
}

.watch-btn {
  width: 100%;
  margin-top: 8px;
  padding: 6px;
  background: linear-gradient(45deg, #ff0000, #cc0000);
  border: none;
  border-radius: 6px;
  color: white;
  font-weight: bold;
  font-size: 11px;
  cursor: pointer;
}

/* Section Headers */
.section-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 15px;
}

.section-header h3 {
  font-size: 18px;
}

.view-all {
  color: #ff0000;
  font-size: 14px;
  cursor: pointer;
}

/* Coins Badge */
.coins-badge {
  text-align: center;
  margin: 15px;
  padding: 20px;
  background: linear-gradient(135deg, #ff0000, #cc0000);
  border-radius: 15px;
}

.coins-badge .coins-amount {
  font-size: 48px;
  font-weight: bold;
  margin: 10px 0;
}

/* Daily Bonus */
.daily-bonus {
  background: linear-gradient(135deg, #ff0000, #cc0000);
  margin: 15px;
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  cursor: pointer;
}

/* Ad Options */
.ad-options {
  display: flex;
  flex-direction: column;
  gap: 12px;
  margin-top: 15px;
}

.ad-option {
  background: linear-gradient(135deg, #2a2a2a, #1a1a1a);
  border-radius: 12px;
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  cursor: pointer;
  border: 1px solid #333;
}

/* Spin Wheel */
.spin-container {
  text-align: center;
  margin: 20px 0;
}

.spin-wheel-wrapper {
  position: relative;
  width: 260px;
  height: 260px;
  margin: 0 auto;
}

.spin-wheel {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  position: relative;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  transition: transform 4s cubic-bezier(0.2, 0.8, 0.3, 1);
}

.spin-wheel .segment {
  position: absolute;
  width: 50%;
  height: 50%;
  transform-origin: 100% 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  font-size: 12px;
  color: white;
  text-shadow: 1px 1px 0 rgba(0,0,0,0.5);
}

.spin-wheel .segment span {
  transform: rotate(45deg);
  display: inline-block;
  margin-left: 30px;
  margin-bottom: 30px;
}

.spin-pointer {
  position: absolute;
  top: -15px;
  left: 50%;
  transform: translateX(-50%);
  width: 0;
  height: 0;
  border-left: 12px solid transparent;
  border-right: 12px solid transparent;
  border-top: 25px solid #ff0000;
  z-index: 10;
}

.spin-wheel.spinning {
  animation: spinWheel 4s cubic-bezier(0.2, 0.8, 0.3, 1);
}

@keyframes spinWheel {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(1440deg); }
}

.spin-btn {
  margin-top: 20px;
  padding: 12px 30px;
  background: linear-gradient(45deg, #ff0000, #cc0000);
  border: none;
  border-radius: 25px;
  color: white;
  font-weight: bold;
  cursor: pointer;
}

.spin-reward {
  text-align: center;
  margin-top: 15px;
  font-size: 16px;
  font-weight: bold;
  color: #ffaa00;
}

.spin-timer {
  text-align: center;
  margin-top: 10px;
  font-size: 12px;
  color: #888;
}

/* Invite Section */
.invite-section {
  background: linear-gradient(135deg, #2a2a2a 0%, #1a1a1a 100%);
  margin: 15px;
  padding: 20px;
  border-radius: 15px;
  border: 2px solid #ff0000;
  text-align: center;
}

.invite-code-box {
  background: rgba(0,0,0,0.5);
  padding: 15px;
  border-radius: 12px;
  margin: 15px 0;
}

.invite-code-box .code {
  font-size: 28px;
  font-weight: bold;
  letter-spacing: 4px;
  background: #000;
  padding: 10px 20px;
  border-radius: 12px;
  display: inline-block;
  margin: 10px 0;
  cursor: pointer;
  font-family: monospace;
  user-select: all;
}

.invite-code-box .code:active {
  background: #ff0000;
  transform: scale(0.98);
}

.share-buttons {
  display: flex;
  gap: 10px;
  justify-content: center;
  margin-top: 15px;
}

.share-whatsapp { background: #25D366; color: white; padding: 10px 20px; border-radius: 10px; cursor: pointer; border: none; font-weight: bold; }
.share-telegram { background: #0088cc; color: white; padding: 10px 20px; border-radius: 10px; cursor: pointer; border: none; font-weight: bold; }
.share-copy { background: #4CAF50; color: white; padding: 10px 20px; border-radius: 10px; cursor: pointer; border: none; font-weight: bold; }

.invite-stats {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
  padding-top: 15px;
  border-top: 1px solid #333;
}

.stat-value {
  font-size: 24px;
  font-weight: bold;
  color: #ff0000;
}

.stat-label {
  font-size: 12px;
  color: #888;
}

/* Withdraw Page */
.card {
  background: linear-gradient(135deg, #1a1a1a 0%, #0f0f0f 100%);
  margin: 15px;
  padding: 20px;
  border-radius: 15px;
  border: 1px solid #333;
}

.input-field {
  width: 100%;
  padding: 12px;
  border-radius: 10px;
  border: 2px solid #333;
  background: #0a0a0a;
  color: white;
  margin: 10px 0;
}

.withdraw-info {
  background: rgba(255,0,0,0.1);
  padding: 15px;
  border-radius: 12px;
  margin: 15px 0;
  text-align: center;
}

.withdraw-item {
  background: #0a0a0a;
  padding: 12px;
  border-radius: 8px;
  margin-bottom: 10px;
}

.withdraw-header {
  display: flex;
  justify-content: space-between;
  margin-bottom: 5px;
}

.withdraw-amount {
  font-size: 16px;
  font-weight: bold;
}

.withdraw-status {
  font-size: 12px;
  font-weight: bold;
}

.status-pending { color: #ffaa00; }
.status-completed { color: #00ff00; }
.status-failed { color: #ff0000; }

.loading-more {
  text-align: center;
  padding: 20px;
  color: #888;
}

.loading-more .spinner-small {
  width: 30px;
  height: 30px;
  border: 3px solid #333;
  border-top-color: #ff0000;
  border-radius: 50%;
  animation: spin 1s linear infinite;
  margin: 0 auto 10px;
}

.no-results {
  text-align: center;
  padding: 50px 20px;
  color: #888;
}

.info-text {
  font-size: 12px;
  color: #888;
  text-align: center;
  margin-top: 10px;
}

/* Ad Containers */
.ad-container {
  background: linear-gradient(135deg, #1a1a1a, #0f0f0f);
  margin: 10px;
  padding: 10px;
  border-radius: 12px;
  text-align: center;
  border: 1px solid #333;
}

.ad-label {
  font-size: 10px;
  color: #888;
  margin-bottom: 5px;
  text-transform: uppercase;
}

.banner-ad {
  min-height: 60px;
  background: #000;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.banner-ad ins {
  display: block;
}

/* Ad Counter Badge */
.ad-counter {
  position: fixed;
  bottom: 80px;
  right: 10px;
  background: rgba(0,0,0,0.8);
  padding: 5px 10px;
  border-radius: 20px;
  font-size: 11px;
  color: #ff0000;
  z-index: 999;
  font-weight: bold;
}

/* Floating Download Button */
.floating-download {
  position: fixed;
  bottom: 90px;
  left: 10px;
  background: linear-gradient(45deg, #25D366, #128C7E);
  padding: 10px 15px;
  border-radius: 30px;
  font-size: 12px;
  font-weight: bold;
  z-index: 999;
  cursor: pointer;
  box-shadow: 0 2px 10px rgba(0,0,0,0.3);
  display: flex;
  align-items: center;
  gap: 5px;
}

@media (max-width: 480px) {
  .movies-grid {
    grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
    gap: 10px;
  }
  .movie-poster { height: 180px; }
  .coins-badge .coins-amount { font-size: 36px; }
  .spin-wheel-wrapper { width: 220px; height: 220px; }
  .carousel-prev, .carousel-next { width: 30px; height: 30px; font-size: 16px; }
  .carousel-slide .slide-title { font-size: 14px; }
  .carousel-slide .slide-message { font-size: 11px; }
  .carousel-slide .slide-link { padding: 4px 12px; font-size: 10px; }
  body { padding-bottom: 150px; }
}
</style>
</head>
<body>

<!-- Loading Overlay -->
<div id="loadingOverlay">
  <div class="spinner"></div>
</div>

<!-- Ad Modal -->
<div id="adModal" class="ad-modal">
  <div class="ad-modal-content">
    <h3 style="color: #ff0000;" id="adTitle">🎬 Watch Ad to Continue</h3>
    <div class="ad-video-container">
      <video id="adVideo" class="ad-video" autoplay muted playsinline>
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      </video>
      <div id="adTimer" class="ad-timer">5</div>
    </div>
    <div class="ad-progress">
      <div id="adProgress" class="ad-progress-bar"></div>
    </div>
    <p style="color: #888; font-size: 12px; margin: 10px 0;" id="adInstruction">
      Watch full ad to watch movie!
    </p>
    <button id="adClaimBtn" class="ad-claim-btn" onclick="completeAdAndPlay()">Continue to Movie</button>
  </div>
</div>

<!-- Floating Download Button -->
<div class="floating-download" onclick="downloadApp()">
  📲 Download App
</div>

<!-- Ad Counter Badge -->
<div class="ad-counter" id="adCounter">🎬 Ready to Watch</div>

<!-- Login Page -->
<div id="loginPage">
  <div class="login-container">
    <div class="logo">
      <h1>Viniflix 🔥</h1>
      <p>Watch Movies, Earn Coins, Win Big!</p>
    </div>
    
    <div class="input-group">
      <input id="emailInput" placeholder="Email Address" type="email">
    </div>
    <div class="input-group">
      <input id="passwordInput" type="password" placeholder="Password">
    </div>
    
    <button class="btn-primary" onclick="login()">Login</button>
    
    <div class="refer-code-input" id="referCodeSection" style="display: none;">
      <label>🎁 Have a Referral Code?</label>
      <input type="text" id="referCodeInput" placeholder="Enter invite code (optional)">
      <small>Enter a friend's invite code to get +5000 bonus coins!</small>
    </div>
    
    <div class="divider">or</div>
    
    <button class="btn-secondary" onclick="showSignup()">Create New Account</button>
    
    <!-- Download Button on Login Page -->
    <button class="download-btn" onclick="downloadApp()">
      📲 Download Viniflix App
    </button>
  </div>
</div>

<!-- Home Page -->
<div id="homePage" class="page">
  <div class="header">
    <h2>Viniflix 🔥</h2>
    <button class="logout-btn" onclick="logout()">Logout</button>
  </div>
  
  <!-- Banner Ad 1 - Top -->
  <div class="ad-container">
    <div class="ad-label">Advertisement</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="6412796497"></ins>
    </div>
  </div>
  
  <div class="banner-carousel" id="bannerCarousel">
    <div class="carousel-container">
      <div class="carousel-slides" id="carouselSlides"></div>
    </div>
    <button class="carousel-prev" id="carouselPrev">❮</button>
    <button class="carousel-next" id="carouselNext">❯</button>
    <div class="carousel-dots" id="carouselDots"></div>
  </div>
  
  <!-- Banner Ad 2 - Middle -->
  <div class="ad-container">
    <div class="ad-label">Advertisement</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="7997340904"></ins>
    </div>
  </div>
  
  <div class="search-container">
    <div class="search-box">
      <input type="text" id="searchInput" placeholder="🔍 Search movies..." onkeyup="searchMovies()">
      <button onclick="searchMovies()">Search</button>
    </div>
  </div>
  
  <div class="section-header">
    <h3>🎬 All Movies</h3>
    <span class="view-all" onclick="resetSearch()">Show All →</span>
  </div>
  
  <div id="moviesContainer">
    <div class="movies-grid" id="moviesGrid"></div>
    <div id="loadingMore" class="loading-more" style="display: none;">
      <div class="spinner-small"></div>
      <p>Loading more movies...</p>
    </div>
  </div>
  
  <!-- Banner Ad 3 - Bottom -->
  <div class="ad-container">
    <div class="ad-label">Advertisement</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="9529914423"></ins>
    </div>
  </div>
</div>

<!-- Earn Page -->
<div id="earnPage" class="page">
  <div class="header">
    <h2>Earn Coins 💰</h2>
    <button class="logout-btn" onclick="logout()">Logout</button>
  </div>
  
  <!-- Banner Ad 1 - Earn Page Top -->
  <div class="ad-container">
    <div class="ad-label">Earn More - Watch Ads</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="6412796497"></ins>
    </div>
  </div>
  
  <div class="coins-badge">
    <h2>💰 Your Balance</h2>
    <div class="coins-amount" id="coins">0</div>
    <p>100,000 coins = ₹100</p>
  </div>
  
  <div class="daily-bonus" onclick="claimDailyBonus()">
    <h3>📅 Daily Bonus</h3>
    <div class="bonus-amount" id="dailyBonusAmount">+50 Coins</div>
    <div class="bonus-timer" id="dailyBonusTimer">Claim Now!</div>
  </div>
  
  <!-- Banner Ad 2 - Earn Page Middle -->
  <div class="ad-container">
    <div class="ad-label">Special Offer</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="7997340904"></ins>
    </div>
  </div>
  
  <div class="card">
    <h3>🎬 Watch & Earn</h3>
    <p>Watch rewarded ads to earn free coins instantly!</p>
    
    <div class="ad-options">
      <div class="ad-option" onclick="showRewardedAd(10, 'Standard', 5)">
        <div class="ad-info"><h4>📺 Standard Ad</h4><p>5 seconds video</p></div>
        <div class="ad-reward">+10 Coins</div>
      </div>
      <div class="ad-option" onclick="showRewardedAd(25, 'Premium', 15)">
        <div class="ad-info"><h4>⭐ Premium Ad</h4><p>15 seconds video</p></div>
        <div class="ad-reward">+25 Coins</div>
      </div>
      <div class="ad-option" onclick="showRewardedAd(50, 'Bonus', 30)">
        <div class="ad-info"><h4>💎 Bonus Ad</h4><p>30 seconds video</p></div>
        <div class="ad-reward">+50 Coins</div>
      </div>
    </div>
  </div>
  
  <!-- Banner Ad 3 - Earn Page Bottom -->
  <div class="ad-container">
    <div class="ad-label">Limited Time Offer</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="9529914423"></ins>
    </div>
  </div>
  
  <div class="card">
    <h3>🎡 Lucky Spin Wheel</h3>
    <p>Spin daily to win amazing prizes!</p>
    
    <div class="spin-container">
      <div class="spin-wheel-wrapper">
        <div class="spin-pointer"></div>
        <div class="spin-wheel" id="spinWheel"></div>
      </div>
      <button class="spin-btn" onclick="spinWheel()" id="spinBtn">🎲 SPIN NOW</button>
      <div class="spin-reward" id="spinReward"></div>
      <div class="spin-timer" id="spinTimer"></div>
    </div>
  </div>
  
  <div class="invite-section">
    <h3>🎁 Invite Friends & Earn 🎁</h3>
    <p style="color: #ffaa00; font-size: 14px; margin: 10px 0;">
      🔥 Per Refer = 5000 Coins! 🔥<br>
      Share your code! When friends sign up, you both get +5000 coins!
    </p>
    
    <div class="invite-code-box">
      <label>📱 YOUR INVITE CODE</label>
      <div class="code" id="myCode" onclick="copyInviteCode()">LOADING...</div>
      <small>⬆️ Click to copy code ⬆️</small>
    </div>
    
    <div class="share-buttons">
      <button class="share-whatsapp" onclick="shareViaWhatsApp()">📱 WhatsApp</button>
      <button class="share-telegram" onclick="shareViaTelegram()">✈️ Telegram</button>
      <button class="share-copy" onclick="shareViaCopy()">🔗 Copy Link</button>
    </div>
    
    <div class="invite-stats">
      <div>
        <div class="stat-value" id="totalInvites">0</div>
        <div class="stat-label">Total Invites</div>
      </div>
      <div>
        <div class="stat-value" id="totalBonus">0</div>
        <div class="stat-label">Bonus Earned</div>
      </div>
    </div>
    
    <button class="btn-secondary" onclick="redeemInvite()" style="margin-top: 15px; width: 100%;">
      🔄 Use Someone's Code
    </button>
    
    <!-- Download Button on Earn Page -->
    <button class="download-btn" onclick="downloadApp()" style="margin-top: 15px;">
      📲 Download Viniflix App
    </button>
  </div>
</div>

<!-- Withdraw Page -->
<div id="withdrawPage" class="page">
  <div class="header">
    <h2>Withdraw 💸</h2>
    <button class="logout-btn" onclick="logout()">Logout</button>
  </div>
  
  <!-- Banner Ad 1 - Withdraw Page Top -->
  <div class="ad-container">
    <div class="ad-label">Withdraw Your Earnings</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="6412796497"></ins>
    </div>
  </div>
  
  <div class="coins-badge">
    <h2>💰 Available Balance</h2>
    <div class="coins-amount" id="coinsWithdraw">0</div>
    <p>100,000 coins = ₹100</p>
  </div>
  
  <!-- Banner Ad 2 - Withdraw Page Middle -->
  <div class="ad-container">
    <div class="ad-label">Fast Withdrawals</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="7997340904"></ins>
    </div>
  </div>
  
  <div class="card">
    <h3>💸 Withdraw Money</h3>
    <div class="withdraw-info">
      <p>Minimum Withdrawal: <strong>100,000 coins (₹100)</strong></p>
      <p>Processing Time: 24-48 hours</p>
    </div>
    
    <input type="text" id="upiInput" class="input-field" placeholder="Enter UPI ID (example@okhdfcbank)">
    <button class="btn-primary" onclick="withdraw()">Request Withdrawal</button>
    <p class="info-text">⚠️ Withdrawal requests are processed within 48 hours</p>
  </div>
  
  <!-- Banner Ad 3 - Withdraw Page Bottom -->
  <div class="ad-container">
    <div class="ad-label">Instant Withdrawals Coming Soon</div>
    <div class="banner-ad">
      <ins class="adsbygoogle"
           style="display:inline-block;width:320px;height:50px"
           data-ad-client="ca-pub-6353438920437702"
           data-ad-slot="9529914423"></ins>
    </div>
  </div>
  
  <div class="card">
    <h3>📊 Withdrawal History</h3>
    <div id="withdrawHistory"></div>
  </div>
</div>

<!-- Navbar -->
<div class="nav">
  <button onclick="showPage('homePage')" id="navHome">🏠 Home</button>
  <button onclick="showPage('earnPage')" id="navEarn">💰 Earn</button>
  <button onclick="showPage('withdrawPage')" id="navWallet">💸 Wallet</button>
</div>

<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword, onAuthStateChanged, signOut, setPersistence, browserLocalPersistence } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-auth.js";
import { getDatabase, ref, set, get, update, push } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-database.js";

// Firebase Config
const firebaseConfig = {
  apiKey: "AIzaSyBlSMSOzq-lu_3e6pVPsVn5POZ7PhWDJ7g",
  authDomain: "viniflix-moviex.firebaseapp.com",
  databaseURL: "https://viniflix-moviex-default-rtdb.asia-southeast1.firebasedatabase.app",
  projectId: "viniflix-moviex",
  storageBucket: "viniflix-moviex.firebasestorage.app",
  messagingSenderId: "699982713036",
  appId: "1:699982713036:web:82bc5b89fbd87ea45fb269"
};

const app = initializeApp(firebaseConfig);
const auth = getAuth(app);
const db = getDatabase(app);

// Set persistence to LOCAL so user stays logged in after refresh
setPersistence(auth, browserLocalPersistence)
  .then(() => console.log("✅ Firebase persistence set to LOCAL"))
  .catch((e) => console.error("Persistence error:", e));

// ===========================================
// ✅ APK DOWNLOAD LINK - WORKING
// ===========================================
const APK_DOWNLOAD_URL = "https://drive.google.com/file/d/1HOnPhk-Aefsx6eIwDkv8L7PF_fWhiJ3H/view?usp=drivesdk";

// Download App Function
window.downloadApp = function() {
  showToast("📲 Downloading Viniflix App...", false);
  window.open(APK_DOWNLOAD_URL, '_blank');
};

// DOM Elements
const emailInput = document.getElementById("emailInput");
const passwordInput = document.getElementById("passwordInput");
const referCodeInput = document.getElementById("referCodeInput");
const referCodeSection = document.getElementById("referCodeSection");
const coinsEl = document.getElementById("coins");
const coinsWithdrawEl = document.getElementById("coinsWithdraw");
const myCodeEl = document.getElementById("myCode");
const upiInput = document.getElementById("upiInput");
const loadingOverlay = document.getElementById("loadingOverlay");
const moviesGrid = document.getElementById("moviesGrid");
const loadingMore = document.getElementById("loadingMore");

let allMovies = [];
let displayedMovies = [];
let currentPage = 1;
let isLoading = false;
let hasMore = true;
const MOVIES_PER_PAGE = 20;
let pendingMovieLink = null;
let pendingMovieTitle = null;
let isAdPlaying = false;

// Sample Movies
const sampleMovies = [
  { title: "Action Movie 1", year: "2024", genre: "Action", icon: "🎬", link: "https://www.youtube.com/watch?v=dQw4w9WgXcQ", posterUrl: "" },
  { title: "Action Movie 2", year: "2024", genre: "Action", icon: "🎬", link: "https://www.youtube.com/watch?v=dQw4w9WgXcQ", posterUrl: "" },
  { title: "Action Movie 3", year: "2023", genre: "Action", icon: "🎬", link: "https://www.youtube.com/watch?v=dQw4w9WgXcQ", posterUrl: "" },
];

function loadBannerAds() {
  try {
    const banners = document.querySelectorAll('.adsbygoogle');
    for (let banner of banners) {
      if (banner && !banner.getAttribute('data-adsbygoogle-status')) {
        (adsbygoogle = window.adsbygoogle || []).push({});
      }
    }
  } catch (err) {
    console.error("Banner ad error:", err);
  }
}

async function showMandatoryAd(link, title) {
  return new Promise((resolve) => {
    pendingMovieLink = link;
    pendingMovieTitle = title;
    
    const modal = document.getElementById('adModal');
    const video = document.getElementById('adVideo');
    const timer = document.getElementById('adTimer');
    const progress = document.getElementById('adProgress');
    const claimBtn = document.getElementById('adClaimBtn');
    const titleEl = document.getElementById('adTitle');
    const instruction = document.getElementById('adInstruction');
    
    titleEl.innerHTML = `🎬 Watch Ad to Watch "${title}"`;
    instruction.innerHTML = `Watch for 5 seconds to watch your movie!`;
    
    let timeLeft = 5;
    timer.textContent = timeLeft;
    progress.style.width = '0%';
    claimBtn.classList.remove('active');
    claimBtn.textContent = 'Continue to Movie';
    
    const adVideos = [
      'https://www.w3schools.com/html/mov_bbb.mp4',
      'https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4'
    ];
    video.src = adVideos[Math.floor(Math.random() * adVideos.length)];
    video.load();
    video.play().catch(e => console.log('Autoplay blocked'));
    modal.style.display = 'flex';
    
    let adCompleted = false;
    const adTimerInterval = setInterval(() => {
      timeLeft--;
      timer.textContent = timeLeft;
      progress.style.width = `${((5 - timeLeft) / 5) * 100}%`;
      if (timeLeft <= 0) {
        clearInterval(adTimerInterval);
        adCompleted = true;
        claimBtn.classList.add('active');
        claimBtn.textContent = '✓ Watch Movie Now';
        instruction.innerHTML = `Ad completed! Click to watch "${title}" now.`;
        
        const adCounter = document.getElementById('adCounter');
        if (adCounter) {
          adCounter.innerHTML = '✅ Ad Watched!';
          setTimeout(() => {
            adCounter.innerHTML = '🎬 Ready to Watch';
          }, 3000);
        }
      }
    }, 1000);
    
    window.completeAdAndPlay = function() {
      if (!adCompleted) {
        showToast('Please watch the full ad first!', true);
        return;
      }
      clearInterval(adTimerInterval);
      modal.style.display = 'none';
      video.pause();
      video.currentTime = 0;
      
      if (pendingMovieLink && pendingMovieLink !== '#') {
        showToast(`Now playing: ${pendingMovieTitle} 🎬`, false);
        window.open(pendingMovieLink, '_blank');
      } else {
        showToast('No video link available!', true);
      }
      
      pendingMovieLink = null;
      pendingMovieTitle = null;
      resolve(true);
    };
  });
}

function showToast(msg, isError = false) {
  const toast = document.createElement('div');
  toast.className = 'toast';
  toast.textContent = msg;
  toast.style.borderLeftColor = isError ? '#ff0000' : '#00ff00';
  document.body.appendChild(toast);
  setTimeout(() => toast.remove(), 3000);
}

function showLoading(show) {
  loadingOverlay.style.display = show ? 'flex' : 'none';
}

async function updateCoins(amount, reason = '') {
  if (!auth.currentUser) return false;
  try {
    const userRef = ref(db, `users/${auth.currentUser.uid}`);
    const snapshot = await get(userRef);
    const currentCoins = snapshot.exists() ? snapshot.val().coins || 0 : 0;
    const newCoins = currentCoins + amount;
    if (newCoins < 0) throw new Error('Insufficient coins');
    await update(userRef, { 
      coins: newCoins,
      totalEarned: (snapshot.val()?.totalEarned || 0) + (amount > 0 ? amount : 0)
    });
    if (coinsEl) coinsEl.innerText = newCoins;
    if (coinsWithdrawEl) coinsWithdrawEl.innerText = newCoins;
    return true;
  } catch (err) {
    showToast(err.message, true);
    return false;
  }
}

async function showRewardedAdVoluntary(reward, adType, duration) {
  return new Promise((resolve) => {
    const modal = document.getElementById('adModal');
    const video = document.getElementById('adVideo');
    const timer = document.getElementById('adTimer');
    const progress = document.getElementById('adProgress');
    const claimBtn = document.getElementById('adClaimBtn');
    const titleEl = document.getElementById('adTitle');
    const instruction = document.getElementById('adInstruction');
    
    titleEl.innerHTML = `🎬 ${adType} Ad - Earn ${reward} Coins`;
    instruction.innerHTML = `Watch for ${duration} seconds to earn ${reward} coins!`;
    
    let timeLeft = duration;
    timer.textContent = timeLeft;
    progress.style.width = '0%';
    claimBtn.classList.remove('active');
    claimBtn.textContent = 'Claim Reward';
    
    const adVideos = [
      'https://www.w3schools.com/html/mov_bbb.mp4',
      'https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4'
    ];
    video.src = adVideos[Math.floor(Math.random() * adVideos.length)];
    video.load();
    video.play().catch(e => console.log('Autoplay blocked'));
    modal.style.display = 'flex';
    
    let adCompleted = false;
    const adTimerInterval = setInterval(() => {
      timeLeft--;
      timer.textContent = timeLeft;
      progress.style.width = `${((duration - timeLeft) / duration) * 100}%`;
      if (timeLeft <= 0) {
        clearInterval(adTimerInterval);
        adCompleted = true;
        claimBtn.classList.add('active');
        claimBtn.textContent = `✓ Claim ${reward} Coins`;
        instruction.innerHTML = `Ad completed! Click "Claim Reward" to get ${reward} coins.`;
      }
    }, 1000);
    
    window.claimAdReward = async function() {
      if (!adCompleted) {
        showToast('Watch full ad!', true);
        return;
      }
      clearInterval(adTimerInterval);
      modal.style.display = 'none';
      video.pause();
      video.currentTime = 0;
      const success = await updateCoins(reward, `Watched ${adType} Ad`);
      if (success) showToast(`+${reward} Coins Earned! 🎉`, false);
      resolve(true);
    };
  });
}

window.showRewardedAd = function(reward, adType, duration) {
  if (isAdPlaying) { showToast('Please wait!', true); return false; }
  isAdPlaying = true;
  showRewardedAdVoluntary(reward, adType, duration).finally(() => {
    isAdPlaying = false;
  });
};

window.copyInviteCode = function() {
  const codeElement = document.getElementById('myCode');
  const code = codeElement.innerText;
  
  if (code && code !== 'LOADING...') {
    const tempInput = document.createElement('input');
    tempInput.value = code;
    document.body.appendChild(tempInput);
    tempInput.select();
    tempInput.setSelectionRange(0, 99999);
    
    try {
      const successful = document.execCommand('copy');
      if (successful) {
        showToast('✅ Invite code copied! Share with friends', false);
        codeElement.style.transform = 'scale(0.95)';
        setTimeout(() => {
          codeElement.style.transform = 'scale(1)';
        }, 200);
      } else {
        showToast('Press Ctrl+C to copy code', false);
      }
    } catch (err) {
      showToast('Press Ctrl+C to copy code', false);
    }
    
    document.body.removeChild(tempInput);
  } else {
    showToast('Loading invite code...', true);
  }
};

async function loadMoviesFromDB() {
  try {
    const moviesRef = ref(db, 'movies');
    const snapshot = await get(moviesRef);
    if (snapshot.exists()) {
      const movies = [];
      snapshot.forEach(child => {
        movies.push({ id: child.key, ...child.val() });
      });
      return movies;
    }
    return [];
  } catch (err) {
    console.error("Error loading movies:", err);
    return [];
  }
}

function renderMovies(moviesToShow) {
  if (!moviesGrid) return;
  if (currentPage === 1) moviesGrid.innerHTML = '';
  const start = (currentPage - 1) * MOVIES_PER_PAGE;
  const end = start + MOVIES_PER_PAGE;
  const pageMovies = moviesToShow.slice(0, end);
  
  pageMovies.forEach(movie => {
    const card = document.createElement('div');
    card.className = 'movie-card';
    card.innerHTML = `
      <div class="movie-poster">
        ${movie.posterUrl ? `<img src="${movie.posterUrl}" onerror="this.src='https://via.placeholder.com/200x250?text=No+Image'">` : `<span>${movie.icon || '🎬'}</span>`}
      </div>
      <div class="movie-info">
        <div class="movie-title">${movie.title || 'Untitled'}</div>
        <div class="movie-year">${movie.year || '2024'} • ${movie.genre || 'Action'}</div>
        <button class="watch-btn" onclick="event.stopPropagation(); watchMovie('${movie.link}', '${movie.title}')">🎬 Watch Now (5 Coins)</button>
      </div>
    `;
    moviesGrid.appendChild(card);
  });
  
  if (loadingMore) loadingMore.style.display = 'none';
  isLoading = false;
  hasMore = moviesToShow.length > end;
}

window.watchMovie = async function(link, title) {
  if (!auth.currentUser) { 
    showToast('Please login first!', true); 
    return; 
  }
  if (!link || link === '#') { 
    showToast('No video link available!', true); 
    return; 
  }
  
  const coins = parseInt(coinsEl.innerText);
  if (coins < 5) {
    showToast(`Insufficient coins! Need 5 coins. Go to Earn page to get coins!`, true);
    return;
  }
  
  if (isAdPlaying) {
    showToast('Please wait, ad is playing!', true);
    return;
  }
  
  isAdPlaying = true;
  
  const adCounter = document.getElementById('adCounter');
  if (adCounter) {
    adCounter.innerHTML = '🎬 Watching Ad...';
  }
  
  await showMandatoryAd(link, title);
  
  const success = await updateCoins(-5, `Watched: ${title}`);
  if (!success) {
    showToast('Failed to deduct coins!', true);
  }
  
  isAdPlaying = false;
};

// ===========================================
// BANNER CAROUSEL
// ===========================================
let banners = [];
let currentSlide = 0;
let slideInterval = null;
const INTERVAL_TIME = 3000;

function createCarousel() {
  const slidesContainer = document.getElementById('carouselSlides');
  const dotsContainer = document.getElementById('carouselDots');
  
  if (!slidesContainer || banners.length === 0) return;
  
  slidesContainer.innerHTML = '';
  dotsContainer.innerHTML = '';
  
  banners.forEach((banner, index) => {
    const slide = document.createElement('div');
    slide.className = 'carousel-slide';
    if (banner.imageUrl && banner.imageUrl.trim() !== '') {
      slide.style.backgroundImage = `url('${banner.imageUrl}')`;
      slide.style.backgroundSize = 'cover';
      slide.style.backgroundPosition = 'center';
    } else {
      slide.style.background = banner.color || 'linear-gradient(135deg, #ff0000, #cc0000)';
    }
    slide.innerHTML = `
      <div class="slide-content">
        <div class="slide-title">📢 ${banner.title}</div>
        <div class="slide-message">${banner.message}</div>
        ${banner.link ? `<button class="slide-link" onclick="event.stopPropagation(); window.open('${banner.link}', '_blank')">🎬 Watch</button>` : ''}
      </div>
    `;
    slidesContainer.appendChild(slide);
    
    const dot = document.createElement('div');
    dot.className = 'carousel-dot';
    dot.onclick = () => goToSlide(index);
    dotsContainer.appendChild(dot);
  });
  
  updateCarousel();
  startAutoSlide();
}

function updateCarousel() {
  const slidesContainer = document.getElementById('carouselSlides');
  const dots = document.querySelectorAll('.carousel-dot');
  if (!slidesContainer) return;
  slidesContainer.style.transform = `translateX(-${currentSlide * 100}%)`;
  dots.forEach((dot, index) => {
    if (index === currentSlide) dot.classList.add('active');
    else dot.classList.remove('active');
  });
}

function goToSlide(index) {
  if (index < 0) index = banners.length - 1;
  if (index >= banners.length) index = 0;
  currentSlide = index;
  updateCarousel();
  resetAutoSlide();
}

function nextSlide() { goToSlide(currentSlide + 1); }
function prevSlide() { goToSlide(currentSlide - 1); }

function startAutoSlide() {
  if (slideInterval) clearInterval(slideInterval);
  slideInterval = setInterval(() => nextSlide(), INTERVAL_TIME);
}

function resetAutoSlide() {
  if (slideInterval) { clearInterval(slideInterval); startAutoSlide(); }
}

async function loadBannerCarousel() {
  try {
    const bannersRef = ref(db, 'bannerPosts');
    const snapshot = await get(bannersRef);
    if (snapshot.exists()) {
      const allBanners = [];
      snapshot.forEach(child => { allBanners.push({ id: child.key, ...child.val() }); });
      banners = allBanners.filter(b => b.status === 'active');
      if (banners.length > 0) createCarousel();
    }
  } catch (err) { console.error("Error loading banners:", err); }
}

window.searchMovies = function() {
  const term = document.getElementById('searchInput').value.toLowerCase().trim();
  displayedMovies = term === '' ? [...allMovies] : allMovies.filter(m => m.title?.toLowerCase().includes(term) || m.genre?.toLowerCase().includes(term));
  currentPage = 1; hasMore = true;
  if (moviesGrid) moviesGrid.innerHTML = '';
  renderMovies(displayedMovies);
  if (displayedMovies.length === 0 && moviesGrid) {
    moviesGrid.innerHTML = `<div class="no-results"><span>🔍</span><p>No movies found for "${term}"</p><p style="font-size:12px;">Try searching for: Action, Comedy, Drama, etc.</p></div>`;
  }
};

window.resetSearch = function() {
  document.getElementById('searchInput').value = '';
  displayedMovies = [...allMovies];
  currentPage = 1; hasMore = true;
  if (moviesGrid) moviesGrid.innerHTML = '';
  renderMovies(displayedMovies);
};

window.addEventListener('scroll', () => {
  if (window.innerHeight + window.scrollY >= document.body.offsetHeight - 200) {
    if (!isLoading && hasMore) {
      isLoading = true;
      if (loadingMore) loadingMore.style.display = 'block';
      setTimeout(() => { currentPage++; renderMovies(displayedMovies); }, 500);
    }
  }
});

// Spin Wheel
const SPIN_PATTERN = [20, 20, 20, 20, 20, 30, 10, 10, 10, 10, 10];
let spinPatternIndex = 0;

function createSpinWheel() {
  const wheel = document.getElementById('spinWheel');
  if (!wheel) return;
  wheel.innerHTML = '';
  const segmentCount = 8, angleStep = 360 / segmentCount;
  const rewards = [10, 20, 30, 50, 100, 200, 400, 500];
  const colors = ['#ff4444', '#ff6644', '#ff8844', '#ffaa44', '#ffcc44', '#ffee44', '#ffff44', '#ffff88'];
  for (let i = 0; i < segmentCount; i++) {
    const seg = document.createElement('div');
    seg.className = 'segment';
    seg.style.background = `linear-gradient(135deg, ${colors[i]}, ${colors[i]}dd)`;
    seg.style.transform = `rotate(${i * angleStep}deg) skewY(${90 - angleStep}deg)`;
    seg.style.transformOrigin = '100% 100%';
    const span = document.createElement('span');
    span.textContent = rewards[i];
    span.style.transform = `rotate(${angleStep/2}deg)`;
    seg.appendChild(span);
    wheel.appendChild(seg);
  }
}

function getPatternReward() { 
  const r = SPIN_PATTERN[spinPatternIndex]; 
  spinPatternIndex = (spinPatternIndex + 1) % SPIN_PATTERN.length; 
  return r; 
}

window.spinWheel = async function() {
  if (!auth.currentUser) { showToast('Please login first!', true); return; }
  const btn = document.getElementById('spinBtn');
  const wheel = document.getElementById('spinWheel');
  const rewardDiv = document.getElementById('spinReward');
  const userRef = ref(db, `users/${auth.currentUser.uid}`);
  const snapshot = await get(userRef);
  const lastSpin = snapshot.val()?.lastSpin;
  if (lastSpin && Date.now() - lastSpin < 24 * 60 * 60 * 1000) {
    const hoursLeft = Math.ceil(24 - (Date.now() - lastSpin) / (60 * 60 * 1000));
    showToast(`Next spin in ${hoursLeft} hours!`, true); return;
  }
  const reward = getPatternReward();
  btn.disabled = true; btn.textContent = 'Spinning...';
  wheel.classList.add('spinning');
  rewardDiv.innerHTML = '';
  setTimeout(async () => {
    wheel.classList.remove('spinning');
    rewardDiv.innerHTML = `🎉 You won ${reward} coins! 🎉`;
    await updateCoins(reward, 'Spin Wheel');
    await update(userRef, { lastSpin: Date.now() });
    btn.disabled = false; btn.textContent = '🎲 SPIN NOW';
    setTimeout(() => rewardDiv.innerHTML = '', 3000);
    updateSpinTimer();
  }, 4000);
};

async function updateSpinTimer() {
  if (!auth.currentUser) return;
  const userRef = ref(db, `users/${auth.currentUser.uid}`);
  const snapshot = await get(userRef);
  const lastSpin = snapshot.val()?.lastSpin;
  const timer = document.getElementById('spinTimer');
  if (lastSpin) {
    const nextSpin = lastSpin + (24 * 60 * 60 * 1000);
    if (Date.now() >= nextSpin) timer.innerHTML = '✅ Ready to spin!';
    else timer.innerHTML = `⏰ Next spin in ${Math.ceil((nextSpin - Date.now()) / (60 * 60 * 1000))} hours`;
  } else timer.innerHTML = '✅ Ready to spin!';
}

window.claimDailyBonus = async function() {
  if (!auth.currentUser) return;
  const userRef = ref(db, `users/${auth.currentUser.uid}`);
  const snapshot = await get(userRef);
  const lastDaily = snapshot.val()?.lastDailyBonus;
  if (lastDaily && Date.now() - lastDaily < 24 * 60 * 60 * 1000) {
    const hoursLeft = Math.ceil(24 - (Date.now() - lastDaily) / (60 * 60 * 1000));
    showToast(`Come back in ${hoursLeft} hours!`, true); return;
  }
  await update(userRef, { lastDailyBonus: Date.now() });
  await updateCoins(50, 'Daily Bonus');
  document.getElementById('dailyBonusAmount').innerHTML = '✓ Claimed';
  document.getElementById('dailyBonusTimer').innerHTML = 'Come back tomorrow!';
  showToast('Daily Bonus: +50 Coins! 🎉', false);
};

// ===========================================
// INVITE SYSTEM
// ===========================================
function getShareMessage() { 
  const code = myCodeEl ? myCodeEl.innerText : 'LOADING';
  return `🎬 Join Viniflix! Use my invite code "${code}" to get +5000 BONUS COINS! 🔥\n\nStart earning now: ${window.location.href}`; 
}

window.shareViaWhatsApp = () => {
  window.open(`https://wa.me/?text=${encodeURIComponent(getShareMessage())}`, '_blank');
};

window.shareViaTelegram = () => {
  window.open(`https://t.me/share/url?url=${window.location.href}&text=${encodeURIComponent('Join Viniflix! Use my invite code to get +5000 bonus coins! 🔥')}`, '_blank');
};

window.shareViaCopy = () => { 
  const message = getShareMessage();
  const tempInput = document.createElement('input');
  tempInput.value = message;
  document.body.appendChild(tempInput);
  tempInput.select();
  
  try {
    const successful = document.execCommand('copy');
    if (successful) {
      showToast('✅ Invite message copied! Share with friends 📋', false);
    } else {
      showToast('Press Ctrl+C to copy', false);
    }
  } catch (err) {
    showToast('Press Ctrl+C to copy', false);
  }
  
  document.body.removeChild(tempInput);
};

window.redeemInvite = async function() {
  if (!auth.currentUser) return;
  const code = prompt("Enter invite code:");
  if (!code) return;
  try {
    showLoading(true);
    const usersRef = ref(db, 'users');
    const snapshot = await get(usersRef);
    let inviterId = null;
    if (snapshot.exists()) {
      for (const key in snapshot.val()) {
        if (snapshot.val()[key].inviteCode === code.toUpperCase() && key !== auth.currentUser.uid) {
          inviterId = key; break;
        }
      }
    }
    if (!inviterId) { showToast("Invalid Code ❌", true); return; }
    const userRef = ref(db, `users/${auth.currentUser.uid}`);
    const userSnap = await get(userRef);
    if (userSnap.val()?.usedInviteCode) { showToast("Already used a code!", true); return; }
    await update(userRef, { coins: (userSnap.val()?.coins || 0) + 5000, usedInviteCode: code.toUpperCase(), totalEarned: (userSnap.val()?.totalEarned || 0) + 5000 });
    const inviterRef = ref(db, `users/${inviterId}`);
    const inviterSnap = await get(inviterRef);
    await update(inviterRef, { coins: (inviterSnap.val()?.coins || 0) + 5000, totalEarned: (inviterSnap.val()?.totalEarned || 0) + 5000 });
    await loadUser(auth.currentUser.uid);
    showToast("+5000 Coins Added! 🎉", false);
  } catch (err) { showToast("Error: " + err.message, true); } finally { showLoading(false); }
};

// ===========================================
// WITHDRAW
// ===========================================
window.withdraw = async function() {
  if (!auth.currentUser) return;
  const coins = parseInt(coinsEl.innerText);
  const upi = upiInput.value.trim();
  if (coins < 100000) { showToast("Minimum 100,000 coins (₹100) required for withdrawal", true); return; }
  if (!upi || !upi.includes('@')) { showToast("Valid UPI ID required", true); return; }
  const amount = Math.floor(coins / 100000);
  if (!confirm(`Withdraw ₹${amount} (${amount * 100000} coins will be deducted)?`)) return;
  try {
    showLoading(true);
    const withdrawalsRef = ref(db, 'withdrawals');
    const newRef = push(withdrawalsRef);
    await set(newRef, { uid: auth.currentUser.uid, amount, coins: coins, upi, status: "pending", timestamp: Date.now() });
    await update(ref(db, `users/${auth.currentUser.uid}`), { coins: coins % 100000 });
    await loadUser(auth.currentUser.uid);
    showToast("Withdrawal Request Sent! 💸 Will be processed within 48 hours", false);
    await loadWithdrawHistory();
  } catch (err) { showToast("Withdrawal failed", true); } finally { showLoading(false); }
};

async function loadWithdrawHistory() {
  if (!auth.currentUser) return;
  try {
    const withdrawalsRef = ref(db, 'withdrawals');
    const snapshot = await get(withdrawalsRef);
    const historyDiv = document.getElementById("withdrawHistory");
    if (!snapshot.exists()) { if (historyDiv) historyDiv.innerHTML = '<p style="color:#888;">No history</p>'; return; }
    let html = '';
    snapshot.forEach(child => {
      const w = child.val();
      if (w.uid === auth.currentUser.uid) {
        html += `<div class="withdraw-item"><div class="withdraw-header"><span class="withdraw-amount">₹${w.amount}</span><span class="withdraw-status ${w.status === 'completed' ? 'status-completed' : w.status === 'pending' ? 'status-pending' : 'status-failed'}">${w.status.toUpperCase()}</span></div><div class="withdraw-date">${new Date(w.timestamp).toLocaleDateString()}</div></div>`;
      }
    });
    if (historyDiv) historyDiv.innerHTML = html || '<p style="color:#888;">No history</p>';
  } catch (err) {}
}

async function loadInviteStats() {
  if (!auth.currentUser) return;
  try {
    const usersRef = ref(db, 'users');
    const snapshot = await get(usersRef);
    let count = 0;
    if (snapshot.exists()) {
      for (const key in snapshot.val()) {
        if (snapshot.val()[key].referredBy === auth.currentUser.uid) count++;
      }
    }
    document.getElementById('totalInvites').innerText = count;
    document.getElementById('totalBonus').innerText = count * 5000;
  } catch (err) {}
}

window.login = async function() {
  const email = emailInput.value.trim(), password = passwordInput.value;
  if (!email || !password) { showToast('Fill all fields', true); return; }
  try {
    showLoading(true);
    await signInWithEmailAndPassword(auth, email, password);
    showToast('Login successful!', false);
  } catch (err) { showToast('Login failed: ' + err.message, true); } finally { showLoading(false); }
};

window.showSignup = function() {
  referCodeSection.style.display = 'block';
  document.querySelector('.login-container .btn-primary').style.display = 'none';
  document.querySelector('.login-container .btn-secondary').style.display = 'none';
  document.querySelector('.divider').style.display = 'none';
  let btn = document.getElementById('signupBtn');
  if (!btn) {
    btn = document.createElement('button');
    btn.id = 'signupBtn';
    btn.className = 'btn-primary';
    btn.textContent = 'Sign Up';
    btn.onclick = signup;
    document.querySelector('.login-container').appendChild(btn);
    const back = document.createElement('button');
    back.className = 'btn-secondary';
    back.textContent = '← Back to Login';
    back.onclick = () => {
      referCodeSection.style.display = 'none';
      document.querySelector('.login-container .btn-primary').style.display = 'block';
      document.querySelector('.login-container .btn-secondary').style.display = 'block';
      document.querySelector('.divider').style.display = 'block';
      btn.remove();
      back.remove();
      referCodeInput.value = '';
    };
    document.querySelector('.login-container').appendChild(back);
  }
};

window.signup = async function() {
  const email = emailInput.value.trim(), password = passwordInput.value, refCode = referCodeInput.value.trim().toUpperCase();
  if (!email || !password) { showToast('Fill all fields', true); return; }
  if (password.length < 6) { showToast('Password must be 6+ chars', true); return; }
  try {
    showLoading(true);
    const userCred = await createUserWithEmailAndPassword(auth, email, password);
    const newCode = Math.random().toString(36).substring(2,8).toUpperCase();
    let referrerId = null;
    if (refCode) {
      const usersRef = ref(db, 'users');
      const snapshot = await get(usersRef);
      if (snapshot.exists()) {
        for (const key in snapshot.val()) {
          if (snapshot.val()[key].inviteCode === refCode && key !== userCred.user.uid) {
            referrerId = key; break;
          }
        }
      }
    }
    await set(ref(db, `users/${userCred.user.uid}`), { 
      coins: 100, inviteCode: newCode, email: email, createdAt: Date.now(), 
      totalEarned: 100, totalWithdrawn: 0, referredBy: referrerId || null, usedReferCode: refCode || null 
    });
    if (referrerId) {
      const referrerRef = ref(db, `users/${referrerId}`);
      const referrerSnap = await get(referrerRef);
      if (referrerSnap.exists()) {
        await update(referrerRef, { coins: (referrerSnap.val().coins || 0) + 5000, totalEarned: (referrerSnap.val().totalEarned || 0) + 5000 });
        showToast('Referral bonus sent! 🎉 +5000 coins!', false);
      }
    }
    showToast(`Signup Successful! +100 coins ${refCode && referrerId ? '& referral bonus sent!' : ''} 🎉`, false);
    emailInput.value = ''; passwordInput.value = ''; referCodeInput.value = '';
  } catch (err) { showToast('Signup failed: ' + err.message, true); } finally { showLoading(false); }
};

async function loadUser(uid) {
  const userRef = ref(db, `users/${uid}`);
  const snapshot = await get(userRef);
  if (snapshot.exists()) {
    const data = snapshot.val();
    if (coinsEl) coinsEl.innerText = data.coins;
    if (coinsWithdrawEl) coinsWithdrawEl.innerText = data.coins;
    if (myCodeEl) myCodeEl.innerText = data.inviteCode;
    await loadInviteStats();
    const movies = await loadMoviesFromDB();
    allMovies = movies.length > 0 ? movies : sampleMovies;
    displayedMovies = [...allMovies];
    renderMovies(displayedMovies);
    await loadWithdrawHistory();
    updateSpinTimer();
    await loadBannerCarousel();
  }
}

window.showPage = function(pageId) {
  document.getElementById("loginPage").style.display = "none";
  document.querySelectorAll(".page").forEach(p => p.style.display = "none");
  const el = document.getElementById(pageId);
  if (el) el.style.display = "block";
  document.querySelectorAll('.nav button').forEach(btn => btn.classList.remove('active'));
  if (pageId === 'homePage') document.getElementById('navHome')?.classList.add('active');
  if (pageId === 'earnPage') document.getElementById('navEarn')?.classList.add('active');
  if (pageId === 'withdrawPage') document.getElementById('navWallet')?.classList.add('active');
  if (pageId === 'withdrawPage' && auth.currentUser) loadWithdrawHistory();
  if (pageId === 'homePage' || pageId === 'earnPage' || pageId === 'withdrawPage') {
    setTimeout(() => loadBannerAds(), 100);
  }
};

window.logout = async function() { await signOut(auth); location.reload(); };
window.viewAllMovies = function() { showToast('More movies coming soon! 🎬', false); };

// Carousel Navigation
document.getElementById('carouselPrev')?.addEventListener('click', () => prevSlide());
document.getElementById('carouselNext')?.addEventListener('click', () => nextSlide());

// Initialize
createSpinWheel();

// Auth state listener - User stays logged in after refresh
onAuthStateChanged(auth, async (user) => {
  if (user) {
    document.getElementById("loginPage").style.display = "none";
    await loadUser(user.uid);
    showPage("homePage");
    setTimeout(() => loadBannerAds(), 500);
  } else {
    document.getElementById("loginPage").style.display = "flex";
    document.querySelectorAll(".page").forEach(p => p.style.display = "none");
    allMovies = sampleMovies;
    displayedMovies = [...allMovies];
    renderMovies(displayedMovies);
    loadBannerCarousel();
  }
});
</script>
</body>
</html>
