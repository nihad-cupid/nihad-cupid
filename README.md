<!-- Premium Football-Themed Animated Header -->
<div align="center">
  
  <!-- Animated Gradient Background -->
  <div style="
    background: linear-gradient(90deg, 
      #004D98 0%, 
      #0A2E5C 25%, 
      #A50044 50%, 
      #8A0036 75%, 
      #004D98 100%
    );
    background-size: 400% 400%;
    animation: gradientShift 8s ease infinite;
    border-radius: 20px;
    padding: 40px 20px;
    margin-bottom: 30px;
    box-shadow: 0 10px 30px rgba(165, 0, 68, 0.3);
    position: relative;
    overflow: hidden;
  ">
    
    <!-- Animated Background Pattern -->
    <div style="
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background-image: 
        radial-gradient(circle at 25% 25%, rgba(255, 255, 255, 0.1) 2px, transparent 2px),
        radial-gradient(circle at 75% 75%, rgba(255, 255, 255, 0.05) 1px, transparent 1px);
      background-size: 50px 50px, 30px 30px;
      opacity: 0.5;
    "></div>
    
    <!-- Main Content -->
    <div style="position: relative; z-index: 2;">
      
      <!-- Profile Image with Border Animation -->
      <img src="https://avatars.githubusercontent.com/Hasibul-Nihad?v=4" 
           alt="Nihad's Profile" 
           style="
             width: 150px;
             height: 150px;
             border-radius: 50%;
             border: 4px solid #FFD700;
             box-shadow: 0 0 20px rgba(255, 215, 0, 0.5);
             margin-bottom: 20px;
             animation: pulse 2s infinite;
           ">
      
      <!-- Animated Typing Text -->
      <div style="margin-bottom: 15px;">
        <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=FFD700&center=true&vCenter=true&width=600&height=60&lines=Hi%2C+I'm+Nihad!+%F0%9F%91%8B;Full+Stack+Developer;Bar%C3%A7a+Devotee;Tech+Innovator" 
             alt="Typing Intro" />
      </div>
      
      <!-- Animated Tagline -->
      <div style="
        font-size: 18px;
        color: #FFFFFF;
        font-weight: 300;
        letter-spacing: 1px;
        margin-bottom: 20px;
        text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        animation: fadeInUp 1.5s ease;
      ">
        <span style="color: #FFD700;">⚡</span> Where imagination blends with clean code & modern UI aesthetics
      </div>
      
      <!-- Animated Football Badge -->
      <div style="
        display: inline-block;
        animation: rotate 20s linear infinite;
        margin-bottom: 20px;
      ">
        <svg width="60" height="60" viewBox="0 0 60 60">
          <!-- Football Pattern -->
          <circle cx="30" cy="30" r="28" fill="#004D98" stroke="#FFD700" stroke-width="2"/>
          <circle cx="30" cy="30" r="20" fill="#A50044"/>
          <path d="M30,10 L30,50 M10,30 L50,30" stroke="#FFFFFF" stroke-width="2"/>
          <circle cx="30" cy="30" r="6" fill="none" stroke="#FFFFFF" stroke-width="2"/>
          <!-- FCB Text -->
          <text x="30" y="35" text-anchor="middle" fill="#FFFFFF" font-family="Arial" font-size="12" font-weight="bold">FCB</text>
        </svg>
      </div>
      
      <!-- Animated Stats Bar -->
      <div style="
        display: flex;
        justify-content: center;
        gap: 30px;
        margin-top: 20px;
        animation: slideUp 1s ease;
      ">
        <div style="text-align: center;">
          <div style="font-size: 24px; color: #FFD700; font-weight: bold;">100+</div>
          <div style="font-size: 12px; color: #FFFFFF; opacity: 0.9;">Commits</div>
        </div>
        <div style="text-align: center;">
          <div style="font-size: 24px; color: #FFD700; font-weight: bold;">10+</div>
          <div style="font-size: 12px; color: #FFFFFF; opacity: 0.9;">Projects</div>
        </div>
        <div style="text-align: center;">
          <div style="font-size: 24px; color: #FFD700; font-weight: bold;">24/7</div>
          <div style="font-size: 12px; color: #FFFFFF; opacity: 0.9;">Code Ready</div>
        </div>
      </div>
      
    </div>
    
    <!-- Animated Corner Accents -->
    <div style="
      position: absolute;
      top: 20px;
      left: 20px;
      width: 40px;
      height: 40px;
      border-top: 2px solid #FFD700;
      border-left: 2px solid #FFD700;
      animation: cornerGlow 3s ease-in-out infinite;
    "></div>
    <div style="
      position: absolute;
      top: 20px;
      right: 20px;
      width: 40px;
      height: 40px;
      border-top: 2px solid #FFD700;
      border-right: 2px solid #FFD700;
      animation: cornerGlow 3s ease-in-out infinite 0.5s;
    "></div>
    <div style="
      position: absolute;
      bottom: 20px;
      left: 20px;
      width: 40px;
      height: 40px;
      border-bottom: 2px solid #FFD700;
      border-left: 2px solid #FFD700;
      animation: cornerGlow 3s ease-in-out infinite 1s;
    "></div>
    <div style="
      position: absolute;
      bottom: 20px;
      right: 20px;
      width: 40px;
      height: 40px;
      border-bottom: 2px solid #FFD700;
      border-right: 2px solid #FFD700;
      animation: cornerGlow 3s ease-in-out infinite 1.5s;
    "></div>
    
  </div>
  
  <!-- CSS Animations -->
  <style>
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    @keyframes pulse {
      0% { box-shadow: 0 0 20px rgba(255, 215, 0, 0.5); }
      50% { box-shadow: 0 0 30px rgba(255, 215, 0, 0.8); }
      100% { box-shadow: 0 0 20px rgba(255, 215, 0, 0.5); }
    }
    
    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    @keyframes slideUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    @keyframes cornerGlow {
      0%, 100% { opacity: 0.3; }
      50% { opacity: 1; }
    }
    
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
  </style>
  
</div>

<!-- Animated Divider -->
<div align="center" style="margin: 30px 0;">
  <div style="
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    animation: fadeInUp 1s ease;
  ">
    <div style="width: 100px; height: 3px; background: linear-gradient(to right, transparent, #004D98);"></div>
    <div style="
      animation: float 3s ease-in-out infinite;
      font-size: 24px;
      color: #A50044;
    ">⚽</div>
    <div style="width: 100px; height: 3px; background: linear-gradient(to left, transparent, #A50044);"></div>
  </div>
</div>
<br>
<br>
<br>




### ⚡ **My Playbook (Skills & Tech Stack)**
My toolkit is designed for building robust foundations and sleek interfaces.

| **Domain**          | **Technologies & Tools**                                                                                                   |
|---------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Core & Logic**    | `C` `C++` `Python`                                                                                                         |
| **Web & Interface** | `HTML5` `CSS3` `TailwindCSS` `JavaScript`                                                                                  |
| **Data & Storage**  | `MySQL`                                                                                                                    |
| **Tools & Design**  | `Git` `GitHub` `VS Code` `Figma`                                                                                           |

---

### 💬 **Beyond the Code**
*"It took me 17 years and 114 days to become an overnight success."* – Lionel Messi
This quote resonates deeply with my journey in tech. Mastery is not an event; it's a process of continuous learning, iteration, and passion.



- 🔭 **Currently Exploring:** Deepening my JavaScript fundamentals and planning a full-stack project.
- ⚽ **Fun Fact:** I can discuss Barça's tactics from the Cruyff era to Xavi's present.
- 🤝 **Open to:** Collaborative projects, hackathons, or discussing tech/football anytime!

---

### 📣 **Connect With Me**
Let's build something amazing or just talk about the beautiful game!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasibul-nihad/)

[![X (Twitter)](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Hasibul_Nihad)

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hasibul-Nihad)

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](hasibulnihad@gmail.com)

---





<br>
<div align="center">
  
  ### ⚽ **Visca Barça, Visca el Code!** 💙❤️
  
  *"Just as tiki-taka requires precision and teamwork, great code demands clarity and collaboration."*
  
  ![Visitor Count](https://komarev.com/ghpvc/?username=Hasibul-Nihad&color=004D98&style=flat-square&label=PROFILE+VIEWS)
  
</div>
