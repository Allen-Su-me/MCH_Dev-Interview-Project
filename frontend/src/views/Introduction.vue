<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="intro-content">
        <img src="/images/profile.jpg" alt="Your Photo" class="profile-pic">
        <div class="intro-text">
          <h2>自我介紹</h2>
          <p>
            我是蘇郁凱，我一直對網頁開發很感興趣，但一直沒有比較系統化的學習，多半是需要什麼feature就去查或是問gpt，對主流框架也接觸不多，希望能藉此機會充實相關知識。
            此外，我也希望能藉此認識更多同樣對網頁開發感興趣的同學，並學習如何與他人合作完成一個專案。
            <br><br>  
            平常的興趣是打羽球，有參加系羽；也有參加GDSC，是Gen AI技術組的成員。
          </p>
          <button class="contact-button">聯絡我</button> 
        </div>
      </div>
    </header>
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <ul>
        <li>Github: <a href="https://github.com/Allen-Su-me" target="_blank">https://github.com/Allen-Su-me</a></li>
        <li>學經歷：武陵高中/陽明交通大學資訊工程學系</li>
        <li>個人網站/作品集: <a href="https://algebraodyssey.netlify.app/" target="_blank">https://algebraodyssey.netlify.app/</a></li>
      </ul>
    </section>
  </div>
</template>

<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  background-color: #f5f5f5;
  padding: 40px;
  border-radius: 10px;
  border: 1px solid #ddd; 
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.intro-content {
    display: flex; 
    align-items: center; 
    gap: 30px;        
}
.profile-pic {
    width: 200px; 
    height: 200px; 
    border-radius: 50%; 
    object-fit: cover; 
    aspect-ratio: 1/1; 
}

.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.1rem;
  margin-bottom: 20px;
  line-height: 1.5; 
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
  transition: background-color 0.3s ease;/*新增滑鼠懸停動畫*/
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}

.about-section li {
  font-size: 1rem;
  line-height: 2.5;
}

.about-section a {
  color: #4a90e2;
  text-decoration: none;
  transition: color 0.3s ease;
}

.about-section a:hover {
  color: #357abd;
  text-decoration: underline;
}
</style>