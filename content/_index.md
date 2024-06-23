---
---

<div style="text-align: center;">
  <a href="https://podcast.jagunbae.com/reviews">
    <img src="/images/main-thumbnail.jpg" alt="Podcast Main Thumbnail" style="width:100%; max-width:400px;"/>
  </a>
</div>

<div style="text-align: center; margin-top: 20px;">
  <a href="https://apple.com/podcast-link" class="button apple">Listen on Apple Podcasts</a>
  <a href="https://spotify.com/podcast-link" class="button spotify">Listen on Spotify</a>
  <a href="https://youtube.com/podcast-link" class="button youtube">Listen on YouTube</a>
</div>

<div style="text-align: center; margin-top: 20px;">
  <button class="share-button" onclick="copyURL()">🔗</button>
  <p id="share-notification" style="display:none; color: green;">강소팟 추천 감사합니다! 😉</p>
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