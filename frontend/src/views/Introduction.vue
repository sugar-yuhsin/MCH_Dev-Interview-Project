<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="intro-container">
        <img src="../../public/images/Me.jpeg" alt="個人照片" class="profile-image" />
        <div class="intro-text">
          <h2>自我介紹</h2>
          <p>
            Hi! 開發部長們你們好 >< <br>
            我是現在就讀清大資工大二的施又歆，是苗栗人，但高中在新竹讀，已經在這邊當被風吹的女子第五年了，<br>
            常自稱自己是假E人（我很Ｉ），就是還算可以跟別人講話，但其實也蠻喜歡自己一個人安安靜靜的時候。<br>
            對我來說，參加各式資訊領域活動，可以發揮長才，也可以認識更多資訊領域的夥伴，並從中接觸到所有有趣的知識。<br>
            所以想成為黑客松的開發部員，跟一樣喜歡這個領域的人們籌備這場盛會！<br>
          </p>
        </div>
      </div>
    </header>
    
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <ul>
        <li>好棒棒1</li>
        <li>好棒棒2</li>
        <li>好棒棒3</li>
      </ul>
    </section>
  </div>
</template>

<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1000px;
  margin: 0 auto;
}

.intro-header {
  background-color: #f5f5f5;
  padding: 35px;
  border-radius: 10px;
}

.intro-container {
  display: flex;
  align-items: center; /* 垂直置中 */
  gap: 20px; /* 文字和圖片之間的間距 */
}

.profile-image {
  width: 170px; /* 調整圖片大小 */
  height: 200px;
  border-radius: 50%; /* 讓圖片變成圓形 */
  object-fit: cover; /* 確保圖片完整填滿 */
}

.intro-text {
  flex: 1; /* 讓文字區域填滿剩餘空間 */
}

.intro-text h2 {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1rem;
  margin-bottom: 20px;
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

.about-section ul {
  list-style-type: disc;
  padding-left: 20px;
}

.about-section li {
  font-size: 1rem;
  line-height: 1.6;
}
</style>
