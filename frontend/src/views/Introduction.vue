<template>
  <div class="introduction">
    <div class="hero-section">
      <div class="profile-container">
        <img src="/images/profile.jpg" alt="Your Photo" class="profile-pic">
        <div class="social-links">
          <a href="https://github.com/Allen-Su-me" target="_blank" class="social-icon">
            <i class="fab fa-github"></i>
          </a>
          <a href="mailto:allensu.me@gmail.com" class="social-icon">
            <i class="fas fa-envelope"></i>
          </a>
        </div>
      </div>
      <div class="intro-content">
        <h1 class="name">蘇郁凱 <span class="subtitle">Allen Su</span></h1>
        <h2 class="profession">國立陽明交通大學資訊工程學系 大一生</h2>
        <div class="divider"></div>
        <p class="bio">
          我一直對網頁開發很感興趣，但一直沒有比較系統化的學習，多半是需要什麼feature就去查或是問gpt，
          對主流框架也接觸不多，希望能藉由加入梅竹黑客松的技術部機會充實相關知識。
          此外，我也希望能藉此認識更多同樣對網頁開發感興趣的同學，並學習如何與他人合作完成一個專案。
        </p>
        <div class="tags-container">
          <div class="tag">武陵高中</div>
          <div class="tag">交大資工</div>
          <div class="tag">資工系羽</div>
          <div class="tag">GDSC Gen AI技術組</div>
        </div>
      </div>
    </div>

    <section class="projects-section">
      <h2 class="section-title">作品集 <span class="section-subtitle">Projects</span></h2>
      <div class="projects-grid">
        <div class="project-card">
          <div class="project-image">
            <img src="/images/codeduel.png" alt="CodeDuel">
          </div>
          <div class="project-content">
            <h3 class="project-title">CodeDuel</h3>
            <p class="project-description">
              一個程式對戰平台，讓使用者可以與他人同時進行線上程式比賽。
            </p>
            <div class="tech-stack">
              <span class="tech-tag">HTML5</span>
              <span class="tech-tag">JavaScript</span>
              <span class="tech-tag">CSS</span>
              <span class="tech-tag">Firebase Realtime Database</span>
            </div>
            <a href="https://codeduel.netlify.app/" target="_blank" class="view-project">
              查看專案 <i class="fas fa-external-link-alt"></i>
            </a>
          </div>
        </div>

        <div class="project-card">
          <div class="project-image">
            <img src="/images/algebraodyssey.png" alt="Algebra Odyssey">
          </div>
          <div class="project-content">
            <h3 class="project-title">Algebra Odyssey</h3>
            <p class="project-description">
              一款教育遊戲，透過互動式體驗幫助中學生學習代數。
            </p>
            <div class="tech-stack">
              <span class="tech-tag">HTML5</span>
              <span class="tech-tag">CSS</span>
              <span class="tech-tag">JavaScript</span>
              <span class="tech-tag">plotly</span>
              <span class="tech-tag">gsap</span>
            </div>
            <a href="https://algebraodyssey.netlify.app/" target="_blank" class="view-project">
              查看專案 <i class="fas fa-external-link-alt"></i>
            </a>
          </div>
        </div>

        <div class="project-card">
          <div class="project-image">
            <img src="/images/wordele.png" alt="Wordele-化合物遊戲">
          </div>
          <div class="project-content">
            <h3 class="project-title">Wordele-化合物遊戲</h3>
            <p class="project-description">
              一款類似Wordle的手機遊戲，曾經登上三星應用商店排行榜冠軍。
            </p>
            <div class="tech-stack">
              <span class="tech-tag">HTML5</span>
              <span class="tech-tag">CSS</span>
              <span class="tech-tag">JavaScript</span>
              <span class="tech-tag">Java</span>
              <span class="tech-tag">Mobile</span>
            </div>
            <a href="https://play.google.com/store/apps/details?id=com.wordele" target="_blank" class="view-project">
              查看專案 <i class="fas fa-external-link-alt"></i>
            </a>
          </div>
        </div>

      </div>
    </section>

    
    <section class="academic-section">
      <h2 class="section-title">專業能力 <span class="section-subtitle">Academic & Technical Growth</span></h2>
      <div class="academic-content">
        <div class="academic-card">
          <div class="academic-icon">
            <i class="fas fa-graduation-cap"></i>
          </div>
          <div class="academic-details">
            <h3>大學課程</h3>
            <ul class="academic-list">
              <li>
                <span class="course-name">計算機網路概論</span>
                <span class="course-grade">A+</span>
              </li>
              <li>
                <span class="course-name">線性代數</span>
                <span class="course-grade">A+</span>
              </li>
              <li>
                <span class="course-name">普通物理(一)</span>
                <span class="course-grade">A+</span>
              </li>
              <li>
                <span class="course-name">學術英文閱讀與寫作</span>
                <span class="course-grade">A+</span>
              </li>
            </ul>
          </div>
        </div>
        <div class="academic-card">
          <div class="academic-icon">
            <i class="fas fa-code"></i>
          </div>
          <div class="academic-details">
            <h3>自我學習</h3>
            
            <!-- Categorized skills -->
            <div class="skills-category">
              <h4>前端開發</h4>
              <div class="skills-group">
                <span class="tag">HTML/CSS</span>
                <span class="tag">JavaScript</span>
                <span class="tag">D3.js</span>
              </div>
            </div>
            
            <div class="skills-category">
              <h4>程式語言</h4>
              <div class="skills-group">
                <span class="tag">C/C++</span>
                <span class="tag">Python</span>                
                <span class="tag">Java</span>
              </div>
            </div>
            
            <div class="skills-category">
              <h4>開發工具</h4>
              <div class="skills-group">
                <span class="tag">Git</span>
                <span class="tag">VS Code</span>
                <span class="tag">Android Studio</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    
    <section class="awards-section">
      <h2 class="section-title">獲獎紀錄 <span class="section-subtitle">Awards & Honors</span></h2>
      <div class="awards-timeline">
        <div class="timeline-line"></div>
        
        <div class="award-item">
          <div class="award-year">2024</div>
          <div class="timeline-dot"></div>
          <div class="award-content">
            <h3 class="award-title">CodePi Innovation Challenge</h3>
            <p class="award-description">Most Creative Idea</p>
          </div>
        </div>
        
        <div class="award-item">
          <div class="award-year">2022</div>
          <div class="timeline-dot"></div>
          <div class="award-content">
            <h3 class="award-title">2022 Intel AI For Youth Program</h3>
            <p class="award-description">菁英領袖獎及黑客松冠軍</p>
          </div>
        </div>
        
        <div class="award-item">
          <div class="award-year">2022</div>
          <div class="timeline-dot"></div>
          <div class="award-content">
            <h3 class="award-title">行政院數位發展部數位產業署「AI產業實戰應用人才淬煉計畫」111學年度高中職生扎根系列活動</h3>
            <p class="award-description">綜合表現卓越獎並受邀參與企業參訪及成果展</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Introduction',
  mounted() {
    
    if (!document.getElementById('font-awesome')) {
      const link = document.createElement('link');
      link.id = 'font-awesome';
      link.rel = 'stylesheet';
      link.href = 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css';
      document.head.appendChild(link);
    }
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap');

.introduction {
  font-family: 'Noto Sans TC', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 3rem 1.5rem;
  color: #333;
}

.hero-section {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-bottom: 4rem;
  background: linear-gradient(to bottom, #f8f9fa, #ffffff);
  border-radius: 16px;
  padding: 3rem;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
}

@media (min-width: 768px) {
  .hero-section {
    flex-direction: row;
    align-items: center;
  }
}

.profile-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  flex-shrink: 0;
}

.profile-pic {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid white;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
  transition: transform 0.3s ease;
}

.profile-pic:hover {
  transform: scale(1.03);
}

.social-links {
  display: flex;
  gap: 1rem;
  margin-top: 1.5rem;
}

.social-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: #f0f0f0;
  color: #555;
  text-decoration: none;
  font-size: 1.2rem;
  transition: all 0.3s ease;
}

.social-icon:hover {
  background-color: #656d73;
  color: white;
  transform: translateY(-3px);
}

.intro-content {
  flex: 1;
}

.name {
  font-size: 2.5rem;
  font-weight: 700;
  margin: 0;
  color: #1a1a1a;
}

.subtitle {
  font-size: 1.5rem;
  font-weight: 400;
  color: #666;
  margin-left: 0.5rem;
}

.profession {
  font-size: 1.2rem;
  font-weight: 500;
  color: #656d73;
  margin: 0.5rem 0 1rem;
}

.divider {
  width: 60px;
  height: 4px;
  background-color: #656d73;
  margin: 1.5rem 0;
}

.bio {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #555;
  margin-bottom: 1.5rem;
}

.tags-container {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
  margin: 1.5rem 0;
}

.tag {
  background-color: #f0f0f0;
  color: #555;
  padding: 0.5rem 1rem;
  border-radius: 30px;
  font-size: 0.9rem;
  transition: all 0.3s ease;
}

.tag:hover {
  background-color: #e0e0e0;
  transform: translateY(-2px);
}

.contact-button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background-color: #656d73;
  color: white;
  padding: 0.8rem 1.5rem;
  border-radius: 8px;
  text-decoration: none;
  font-size: 1rem;
  font-weight: 500;
  margin-top: 1rem;
  transition: all 0.3s ease;
}

.contact-button:hover {
  background-color: #36383a;
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

/* Projects Section */
.section-title {
  font-size: 2rem;
  color: #1a1a1a;
  text-align: center;
  margin-bottom: 3rem;
  position: relative;
  padding-bottom: 1.5rem;
}

.section-subtitle {
  display: block;
  font-size: 1.2rem;
  font-weight: 400;
  color: #656d73;
  margin-top: 0.3rem;
}

.section-title::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 80px;
  height: 3px;
  background-color: #656d73;
}

.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2.5rem;
}

@media (min-width: 768px) {
  .projects-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

.project-card {
  background-color: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
  transition: all 0.3s ease;
  height: 100%;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.12);
}

.project-image {
  height: 250px;
  overflow: hidden;
  position: relative;
  background-color: #f9f9f9;
}

.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.3s ease-in-out, opacity 0.3s ease;
  box-shadow: inset 0 0 10px rgba(0,0,0,0.1);
}

.project-card:hover .project-image img {
  transform: scale(1.05);
}

.project-content {
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  flex: 1;
}

.project-title {
  font-size: 1.3rem;
  font-weight: 600;
  margin: 0 0 0.8rem 0;
  color: #1a1a1a;
}

.project-description {
  font-size: 1rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 1.5rem;
  flex: 1;
}

.tech-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
}

.tech-tag {
  background-color: #f0f0f0;
  color: #555;
  padding: 0.3rem 0.8rem;
  border-radius: 30px;
  font-size: 0.85rem;
  transition: all 0.3s ease;
}

.tech-tag:hover {
  background-color: #e0e0e0;
}

.view-project {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: #656d73;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 500;
  margin-top: auto;
  transition: all 0.3s ease;
}

.view-project:hover {
  color: #36383a;
}

.view-project i {
  font-size: 0.8rem;
}


.academic-section {
  margin: 5rem 0;
}

.academic-content {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2.5rem;
}

@media (min-width: 768px) {
  .academic-content {
    grid-template-columns: repeat(2, 1fr);
  }
}

.academic-card {
  background-color: white;
  border-radius: 12px;
  padding: 2rem;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
  display: flex;
  flex-direction: column;
  height: 85%;
}

@media (min-width: 640px) {
  .academic-card {
    flex-direction: row;
    align-items: flex-start;
  }
}

.academic-icon {
  background-color: #f0f0f0;
  color: #656d73;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.5rem;
  flex-shrink: 0;
}

@media (min-width: 640px) {
  .academic-icon {
    margin-right: 1.5rem;
    margin-bottom: 0;
  }
}

.academic-icon i {
  font-size: 1.5rem;
}

.academic-details {
  flex: 1;
}

.academic-details h3 {
  font-size: 1.3rem;
  font-weight: 600;
  margin: 0 0 1.2rem 0;
  color: #1a1a1a;
}

.academic-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.academic-list li {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.8rem 0;
  border-bottom: 1px solid #f0f0f0;
}

.academic-list li:last-child {
  border-bottom: none;
}

.course-name {
  font-weight: 500;
  color: #333;
}

.course-grade {
  font-weight: 700;
  color: #656d73;
}

.skill-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
}


.skills-category {
  margin-bottom: 1.5rem;
}

.skills-category:last-child {
  margin-bottom: 0;
}

.skills-category h4 {
  font-size: 1rem;
  font-weight: 600;
  color: #555;
  margin: 0 0 0.8rem 0;
}

.skills-group {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
  margin-bottom: 0.5rem;
}


.awards-section {
  margin: 5rem 0;
}

.awards-list {
  max-width: 800px;
  margin: 0 auto;
}

.award-item {
  display: flex;
  margin-bottom: 2rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid #f0f0f0;
}



.award-year {
  font-size: 1.5rem;
  font-weight: 700;
  color: #656d73;
  min-width: 100px;
  padding-right: 2rem;
  position: relative;
}

.award-content {
  flex: 1;
  padding-left: 1rem;
  position: relative;
}



.award-title {
  font-size: 1.2rem;
  font-weight: 600;
  margin: 0 0 0.5rem 0;
  color: #1a1a1a;
}

.award-description {
  font-size: 1rem;
  color: #555;
  margin: 0;
}



.awards-timeline {
  max-width: 800px;
  margin: 0 auto;
  position: relative;
  padding: 2rem 0;
}

.timeline-line {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 120px;
  width: 2px;
  background-color: #f0f0f0;
}

.award-item {
  display: flex;
  position: relative;
  margin-bottom: 3rem;
  align-items: center;
}

.award-item:last-child {
  margin-bottom: 0;
}

.award-year {
  font-size: 1.5rem;
  font-weight: 700;
  color: #656d73;
  width: 80px;
  text-align: right;
  padding-right: 2rem;
  position: relative;
  line-height: 1.2;
}

.timeline-dot {
  position: absolute;
  left: 120px;
  transform: translateX(-50%);
  width: 16px;
  height: 16px;
  background-color: #656d73;
  border-radius: 50%;
  border: 3px solid white;
  box-shadow: 0 0 0 1px #f0f0f0;
  z-index: 1;
}

.award-content {
  flex: 1;
  padding-left: 2rem;
}

.award-title {
  font-size: 1.2rem;
  font-weight: 600;
  margin: 0 0 0.5rem 0;
  color: #1a1a1a;
}

.award-description {
  font-size: 1rem;
  color: #555;
  margin: 0;
}
</style>