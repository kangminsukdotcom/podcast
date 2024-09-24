---
---

<div style="text-align: center;">
  <a href="https://podcast.jagunbae.com/reviews">
    <img src="/images/main-thumbnail.jpg" alt="Podcast Main Thumbnail" style="width:100%; max-width:400px;"/>
  </a>
</div>
<p>강단과 소신이 필요할 때 꺼내 듣는 일과 삶에 대한 진지한 대화. 강단과 소신 부부는 제주에서 콘텐츠 회사 '작은배'를 운영하고 있습니다.</p>
<div style="text-align: center; margin-top: 20px;">
  <a href="https://podcasts.apple.com/kr/podcast/%EA%B0%95%EC%86%8C%ED%8C%9F/id1701380319" class="button apple">Apple Podcast</a>
  <a href="https://podcasters.spotify.com/pod/show/cheesylazy" class="button spotify">Spotify</a>
  <a href="https://www.youtube.com/playlist?list=PLxwFutPC1Kq53Iam6OeVNUNdpFJqK5ArH" class="button youtube">YouTube</a>
</div>

<div style="text-align: center; margin-top: 20px;">
  <button class="share-button" onclick="copyURL()">🔗</button>
  <p id="share-notification" style="display:none; color: green;">링크 복사 완료!<br></br> 강소팟 추천 감사합니다. 😉</p>
</div>

<script>
  function copyURL() {
    const url = window.location.href;
    navigator.clipboard.writeText(url).then(() => {
      const notification = document.getElementById('share-notification');
      notification.style.display = 'block';
      setTimeout(() => {
        notification.style.display = 'none';
      }, 2000);
    });
  }
</script>