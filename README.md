# external-eyez-esports
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>External Eyez eSports</title>
  <!-- Orbitron font -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
  <!-- Font Awesome -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: #f1c27d; /* skin tone */
      color: #000000;
      line-height: 1.8;
      scroll-behavior: smooth;
      overflow-x: hidden;
    }

    /* Header + Navbar (sticky) */
    .header-navbar {
      position: sticky;
      top: 0;
      width: 100%;
      background-color: #000000;
      display: flex;
      flex-direction: column;
      align-items: center;
      z-index: 1000;
      padding: 10px 0;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }

    .header-navbar .site-title {
      font-size: 36px;
      font-weight: bold;
      color: white;
      text-decoration: none;
      padding: 5px 20px;
      transition: 0.3s;
    }

    .header-navbar .site-title:hover {
      color: #ffb6c1;
      text-shadow: 0 0 10px #ffb6c1;
    }

    .header-navbar nav {
      display: flex;
      gap: 20px;
      padding: 10px 0;
    }

    .header-navbar nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 18px;
      padding: 8px 12px;
      transition: 0.3s;
      border-radius: 5px;
    }

    .header-navbar nav a:hover {
      background: linear-gradient(45deg, #ff9a9e, #fad0c4);
      color: black;
      box-shadow: 0 0 10px #ffb6c1, 0 0 20px #ffb6c1;
    }

    /* Section Styles */
    section {
      padding: 120px 20px 60px 20px;
      min-height: 100vh;
      max-width: 1000px;
      margin: auto;
      page-break-after: always;
      opacity: 0;
      transform: translateY(50px);
      transition: opacity 1s ease, transform 1s ease;
    }

    section.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* Full-width Black Strip Headings */
    section h1 {
      font-size: 36px;
      text-align: center;
      background-color: black;
      color: #ffffff;
      display: block;
      width: 100%;
      padding: 15px 0;
      margin-bottom: 30px;
      text-shadow: 0 0 8px #fff, 0 0 15px #ffb6c1;
      animation: glowHeading 2s infinite alternate;
    }

    @keyframes glowHeading {
      from { text-shadow: 0 0 5px #fff, 0 0 10px #ffb6c1; }
      to { text-shadow: 0 0 15px #fff, 0 0 30px #ffb6c1; }
    }

    section p {
      text-align: justify;
      font-size: 18px;
      color: #000000;
    }

    /* Centered Buttons (stacked vertically) */
    .button-container {
      text-align: center;
      margin-top: 20px;
      display: flex;
      flex-direction: column;
      gap: 15px;
      align-items: center;
    }

    .section-btn, .social-btn {
      display: inline-block;
      width: 250px;
      padding: 12px 25px;
      font-size: 16px;
      font-weight: bold;
      border-radius: 8px;
      text-decoration: none;
      transition: 0.4s;
      text-align: center;
    }

    .section-btn {
      background: linear-gradient(45deg, #ffb6c1, #ff69b4);
      color: black;
    }

    .section-btn:hover {
      background: linear-gradient(45deg, #ff69b4, #ff1493);
      color: white;
      transform: scale(1.05);
      box-shadow: 0 0 15px #ff69b4, 0 0 30px #ff1493;
    }

    .social-btn {
      background-color: #000000;
      color: white;
    }

    .social-btn:hover {
      background: linear-gradient(45deg, #ff9a9e, #fad0c4);
      color: black;
      transform: scale(1.05);
      box-shadow: 0 0 15px #ff9a9e, 0 0 30px #fad0c4;
    }

    .section-btn i, .social-btn i {
      margin-right: 8px;
    }

    /* Footer */
    footer {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color: #000000;
      color: white;
      text-align: center;
      padding: 15px 0;
      font-size: 18px;
      font-weight: bold;
      z-index: 1000;
      box-shadow: 0 -4px 10px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>

  <!-- Sticky Header + Navbar -->
  <div class="header-navbar">
    <a href="#home" class="site-title">EXTERNAL EYEZ ESPORTS</a>
    <nav>
      <a href="#home">Home</a>
      <a href="#team">Team</a>
      <a href="#achievements">Achievements</a>
      <a href="#tournament">Tournament</a>
      <a href="#recruitment">Recruitment</a>
      <a href="#about">About Us</a>
    </nav>
  </div>

  <!-- Home Section -->
  <section id="home">
    <h1>Home</h1>
    <p>
      External Eyez eSports is not just a gaming organization—it is a movement, a vision, and a commitment to excellence in competitive esports. Since its inception, External Eyez eSports has strived to redefine the standards of professional gaming, emphasizing discipline, teamwork, and the relentless pursuit of victory. The foundation of our organization was built on the passion of a small group of dedicated gamers who refused to settle for mediocrity. Each member brought unique skills, insights, and creative strategies that, when combined, formed the backbone of an organization that would soon leave a mark in the competitive gaming world.
      Our organization emphasizes mental resilience, tactical analysis, and adaptability as core principles. These principles are integrated into our daily practices, ensuring that each player is prepared not only for immediate challenges but also for long-term success in the competitive arena.
      Beyond competitions, our vision encompasses community building and mentorship. External Eyez eSports aims to inspire aspiring gamers by offering guidance, sharing insights from experienced players, and creating an environment where talent can flourish. Through interactive sessions, workshops, and online content, we provide educational resources that help players understand game mechanics, strategy formulation, and effective communication within teams. We emphasize the importance of sportsmanship, ethical gameplay, and respect for opponents, as we believe that professionalism extends beyond victories and defeats.
      The Home section also highlights our journey, chronicling the milestones that have shaped External Eyez eSports. From local tournaments where we first proved our mettle to regional and national competitions where our reputation grew, each achievement reflects dedication, strategic planning, and teamwork. These stories are not just about trophies—they are about perseverance, learning, and the relentless pursuit of mastery.
      By navigating this section, gamers, fans, and enthusiasts gain a comprehensive understanding of what sets External Eyez eSports apart. It is a combination of passion, planning, and execution that has made us a formidable name in the esports community. From fostering young talent to setting competitive benchmarks, the Home section encapsulates the ethos, values, and vision that drive our organization forward, making it clear why External Eyez eSports is not just a team but a movement shaping the future of professional gaming.
    </p>
    <div class="button-container">
      <a href="#recruitment" class="section-btn"><i class="fas fa-user-plus"></i>Join Recruitment</a>
      <a href="#team" class="section-btn"><i class="fas fa-users"></i>Our Team</a>
      <a href="#achievements" class="section-btn"><i class="fas fa-trophy"></i>Achievements</a>
      <a href="#tournament" class="section-btn"><i class="fas fa-gamepad"></i>Tournaments</a>
    </div>
  </section>

  <!-- Team Section -->
  <section id="team">
    <h1>Team</h1>
    <p>
      The Team section is the heartbeat of External Eyez eSports. Every professional esports organization is defined not just by its achievements, but by the players, coaches, strategists, and analysts who make success possible. At External Eyez eSports, assembling the right team is a meticulous process, combining careful selection, rigorous evaluation, and continuous development. Each player is evaluated for technical skill, strategic thinking, communication ability, and adaptability, ensuring they can contribute meaningfully to team dynamics.
      Our players are more than individuals—they are a cohesive unit where every role is crucial. From strategists who plan our approaches to analysts who break down opponents’ gameplay, each member plays a specialized role while maintaining flexibility to adapt as the game demands. The training regimen is structured to enhance reflexes, decision-making speed, and tactical awareness. Daily practice sessions involve scenario-based exercises, mock competitions, and in-depth analysis of gameplay footage. Coaches monitor performance closely, providing feedback that sharpens both skill and mental resilience.
      External Eyez eSports also prioritizes personal development. Beyond technical skills, our team members are encouraged to develop leadership qualities, emotional intelligence, and a growth mindset. Workshops on stress management, communication, and strategic thinking complement gaming practice, ensuring players are well-rounded individuals capable of thriving under pressure. This holistic approach ensures that our team does not just perform—they excel in every dimension of competitive gaming.
      Communication is the lifeblood of any team, and at External Eyez eSports, we cultivate an environment where open, effective communication is prioritized. Players learn to coordinate under pressure, anticipate each other’s moves, and execute strategies flawlessly. This synergy allows us to dominate tournaments, adapt to unexpected scenarios, and consistently outperform competitors. Additionally, mentorship programs connect experienced players with new recruits, creating a culture of learning and shared knowledge.
      The Team section provides detailed profiles of each member, showcasing not only their accomplishments but also their personality, strengths, and unique contributions to the organization. It illustrates how teamwork, trust, and dedication combine to create an unstoppable force in competitive gaming. By exploring this section, fans and aspiring gamers gain insight into the individuals behind the brand, understanding the human effort, skill, and strategy that make External Eyez eSports a leader in professional esports.
    </p>
    <div class="button-container">
      <a href="#recruitment" class="section-btn"><i class="fas fa-user-plus"></i>Join Recruitment</a>
    </div>
  </section>

  <!-- Achievements Section -->
  <section id="achievements">
    <h1>Achievements</h1>
    <p>
      External Eyez eSports has consistently demonstrated excellence across multiple competitive arenas. Our Achievements section is a testament to the dedication, strategy, and relentless effort that have propelled our organization to prominence. Each trophy, medal, and accolade is a reflection of countless hours of preparation, intense practice, and precise execution. Beyond physical rewards, our achievements represent milestones in our growth, learning, and evolution as a competitive entity.
      Our victories span local, regional, and national tournaments. In each competition, External Eyez eSports has distinguished itself through innovative strategies, exceptional teamwork, and the ability to adapt to the ever-changing dynamics of competitive gaming. Achievements are meticulously documented, not only celebrating successes but also extracting insights for future improvements. Every tournament provides an opportunity to analyze performance, understand opponent tactics, and refine strategies, creating a cycle of continuous growth and refinement.
      Achievements are not just about winning—they are about setting benchmarks, inspiring team members, and establishing a legacy. External Eyez eSports views every competition as a platform to demonstrate professionalism, ethics, and strategic brilliance. Media coverage, community recognition, and fan engagement amplify the impact of our achievements, reinforcing the organization’s reputation and attracting emerging talent.
      The Achievements section also highlights individual accolades. Players receive recognition for their skills, innovation, and contribution to the team’s success. These personal milestones are celebrated alongside team victories, reflecting the balanced emphasis on individual growth and collective excellence. The section narrates stories of resilience, tactical ingenuity, and moments where split-second decisions determined outcomes.
      Furthermore, External Eyez eSports views achievements as a motivational tool. Aspiring gamers visiting the site gain insight into what dedication, strategic planning, and teamwork can accomplish. The Achievements section communicates that success in esports is a combination of talent, preparation, mental resilience, and consistent effort. It inspires not only current team members but also the wider gaming community, illustrating the high standards that External Eyez eSports upholds and the legacy we continue to build.
    </p>
  </section>

  <!-- Tournament Section -->
  <section id="tournament">
    <h1>Tournament</h1>
    <p>
      Tournaments are central to External Eyez eSports. Each event tests our preparation, strategy, and teamwork. We approach competitions with meticulous planning, including analyzing opponents, refining strategies, and improving coordination. Tournament participation helps our team evolve, develop mental resilience, and demonstrate skill under pressure. Detailed preparation ensures that every player understands their role, anticipates opponent moves, and contributes to the overall strategy effectively.  
      Each tournament experience is a learning opportunity. Post-game analysis is conducted to identify strengths, weaknesses, and opportunities for improvement. By doing so, External Eyez eSports ensures that every competition, whether won or lost, adds value to the team’s growth and expertise. Fans can track our progress, witness our gameplay evolution, and learn from our strategic insights.
      The Tournament section provides information about upcoming events, registration links, and how players can participate. Our approach is structured, professional, and highly competitive, emphasizing excellence in execution, innovation in tactics, and teamwork as the cornerstone of success.
    </p>
    <div class="button-container">
      <a href="https://whatsapp.com/channel/0029VbBRSaS2Jl8E2FynXc0S" class="section-btn"><i class="fas fa-clipboard-list"></i>Register for Tournament</a>
    </div>
  </section>

  <!-- Recruitment Section -->
  <section id="recruitment">
    <h1>Recruitment</h1>
    <p>
      Recruitment at External Eyez eSports identifies players with skill, strategy, and potential. Candidates are evaluated through gameplay, teamwork exercises, and strategic challenges. We provide mentorship, training, and guidance to nurture talent into professional players. Each recruit is assessed for adaptability, communication, and strategic thinking, ensuring they integrate seamlessly into the team.
      Recruitment also includes workshops, coaching, and practical gameplay experience. Players are taught to maintain professionalism, discipline, and a growth mindset. The Recruitment section informs aspiring gamers about the application process, requirements, and expectations to join External Eyez eSports. Our aim is to discover, nurture, and develop the next generation of esports champions.
    </p>
    <div class="button-container">
      <a href="https://whatsapp.com/channel/0029VbBRSaS2Jl8E2FynXc0S" class="section-btn"><i class="fas fa-user-plus"></i>Register Here</a>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about">
    <h1>About Us</h1>
    <p>
      External Eyez eSports was founded with the vision of redefining competitive gaming through professionalism, strategic innovation, and player development. We aim to inspire aspiring gamers, build a strong brand, and contribute to the growth of esports. Our organization values discipline, teamwork, and the relentless pursuit of victory.  
      With a focus on community, mentorship, and competitive excellence, we provide opportunities for players to learn, grow, and showcase their skills. External Eyez eSports also engages with fans and the wider esports community, creating content, sharing insights, and promoting esports as a respected profession.  
      The About Us section introduces visitors to our philosophy, history, achievements, and goals. It reinforces why External Eyez eSports stands out as a professional, innovative, and forward-thinking esports organization.
    </p>
    <div class="button-container">
      <a href="https://instagram.com/externaleyes.gg" class="social-btn"><i class="fab fa-instagram"></i>Instagram</a>
      <a href="https://youtube.com/externaleyes" class="social-btn"><i class="fab fa-youtube"></i>External Eyez eSports</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    Gaze of Hell, Wrath Unbound
  </footer>

  <!-- JavaScript for animations -->
  <script>
    const sections = document.querySelectorAll('section');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if(entry.isIntersecting){
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.2 });
    sections.forEach(section => observer.observe(section));
  </script>

</body>
</html>
