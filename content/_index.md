---
---

<div style="text-align: center;">
  <a href="https://podcast.jagunbae.com/reviews">
    <img src="/images/main-thumbnail.jpg" alt="Podcast Main Thumbnail" style="width:100%; max-width:400px;"/>
  </a>
</div>

<div style="text-align: center; margin-top: 20px;">
  <a href="https://podcasts.apple.com/podcast/강소팟/id1701380319" class="button-a">Apple Podcast</a>
  <a href="https://podcasters.spotify.com/pod/show/cheesylazy" class="button-s">Spotify</a>
  <a href="https://www.youtube.com/playlist?list=PLxwFutPC1Kq53Iam6OeVNUNdpFJqK5ArH" class="button-y">YouTube</a>
</div>

<div style="text-align: center; margin-top: 20px;">
  <button class="share-button" onclick="copyURL()">🔗</button>
  <p id="share-notification" style="display:none; color: green;">강소팟 추천 감사합니다!</p>
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
