<!-- Header Banner -->
<div id="top"></div>
<style>
  /* Custom 3D Styles */
  :root {
    --neon-green: #2ef847;
    --dark-bg: #0d1117;
  }
  
  .profile-3d-container {
    perspective: 1000px;
    margin: 2rem 0;
  }
  
  .profile-card {
    background: var(--dark-bg);
    border: 2px solid var(--neon-green);
    border-radius: 15px;
    padding: 20px;
    transform-style: preserve-3d;
    transition: transform 0.5s ease;
    position: relative;
    box-shadow: 0 0 20px rgba(46, 248, 71, 0.2);
  }
  
  .profile-card:hover {
    transform: translateZ(20px) rotateX(5deg);
  }
  
  .about-item {
    transform-style: preserve-3d;
    transition: all 0.3s ease;
    border: 1px solid var(--neon-green);
  }
  
  .about-item:hover {
    transform: translateZ(10px);
    box-shadow: 0 0 15px rgba(46, 248, 71, 0.3);
  }
  
  .about-item h3 {
    transform: translateZ(5px);
  }
  
  .stats-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin: 2rem 0;
  }
  
  .stats-card {
    background: rgba(13, 17, 23, 0.9);
    border: 1px solid var(--neon-green);
    border-radius: 10px;
    padding: 15px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .stats-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(46, 248, 71, 0.2);
  }
  
  .connect-buttons {
    display: flex;
    gap: 15px;
    justify-content: center;
    flex-wrap: wrap;
    margin: 2rem 0;
  }
  
  .connect-button {
    transform-style: preserve-3d;
    transition: transform 0.3s ease;
  }
  
  .connect-button:hover {
    transform: translateZ(10px) scale(1.05);
  }
  
  .donation-container {
    position: relative;
    padding: 2rem;
    background: linear-gradient(45deg, rgba(46, 248, 71, 0.1), rgba(13, 17, 23, 0.9));
    border-radius: 15px;
    transform-style: preserve-3d;
    transition: transform 0.5s ease;
  }
  
  .donation-container:hover {
    transform: translateZ(15px);
  }
  
  /* Animated background effect */
  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  body {
    background: linear-gradient(-45deg, #0d1117, #161b22, #1f2428, #24292e);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
  }
  
  /* Neon text effect */
  .neon-text {
    color: var(--neon-green);
    text-shadow: 0 0 5px var(--neon-green),
                 0 0 10px var(--neon-green),
                 0 0 20px var(--neon-green);
  }
</style>

<div align="center" class="profile-3d-container">
    <img width="100%" alt="Welcome to my profile!" src="https://github.com/BitmasterXor/BitmasterXor/blob/main/assets/header.png?raw=true">
    <div class="profile-card">
        <img src="https://komarev.com/ghpvc/?username=BitmasterXor&style=flat-square&color=2ef847" alt="Profile Views"/>
        <div class="neon-text">
            <h1>BitmasterXor</h1>
            <h3>Delphi Expert | Security Researcher | Malware Analyst</h3>
        </div>
    </div>
</div>

<!-- Stats Section with 3D effect -->
<div class="stats-container">
    <div class="stats-card">
        <img height="180em" src="https://github-readme-stats.vercel.app/api?username=BitmasterXor&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true&title_color=2ef847&icon_color=2ef847&bg_color=0d1117"/>
    </div>
    <div class="stats-card">
        <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BitmasterXor&layout=compact&langs_count=7&theme=dark&hide_border=true&title_color=2ef847&bg_color=0d1117"/>
    </div>
</div>

<!-- About Me Section with 3D cards -->
<div class="profile-3d-container">
    <div class="profile-card">
        <h2 class="neon-text">
            <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Keyboard.png" alt="Keyboard" width="25" height="25" /> About Me
        </h2>
        <div style="display: grid; gap: 15px;">
            <!-- Your existing about-items with new 3D class -->
            <div class="about-item">
                <h3 class="neon-text">👋 Intro</h3>
                <p>Hi, I'm @BitmasterXor, deeply immersed in Computer Hacking, IT Security Research, and Malware Development.</p>
            </div>
            <!-- Add remaining about-items similarly -->
        </div>
    </div>
</div>

<!-- Connect Section with 3D buttons -->
<div class="connect-buttons">
    <a href="https://www.reddit.com/user/BitmasterXor" class="connect-button">
        <img src="https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white"/>
    </a>
    <!-- Add remaining social media buttons -->
</div>

<!-- Donation Section with 3D effect -->
<div class="donation-container">
    <h2 class="neon-text">Support My Work</h2>
    <table>
        <tr>
            <td align="center">
                <img width="400" src="https://img.shields.io/badge/Bitcoin-Donation-2ef847?style=for-the-badge&logo=bitcoin&logoColor=white"/>
                <br/>
                <img width="400" src="https://img.shields.io/badge/3LA4u7AN7JmGnEGrKAWMcJXaR54XVvPWmd-2ef847?style=flat-square&logo=bitcoin&logoColor=white"/>
            </td>
        </tr>
    </table>
</div>

<!-- Footer with 3D wave effect -->
<div align="center" class="profile-3d-container">
    <div class="neon-text">
        <h2>Thanks for visiting!</h2>
        <p>There is always a crack... That's how the light shines through ✨</p>
    </div>
</div>
