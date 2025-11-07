<!-- 🎧 Playlist Spotify — Modo Foco (compatível GitHub e Web) -->
<section style="text-align: center; margin-top: 40px;">
  <h2 style="color: #1DB954;">🎧 Sons e Playlists para Concentração</h2>
  <p style="color: #444;">Deixe a música te guiar no modo foco — energia verde Spotify com o toque do seu estilo 💚💜</p>

  <!-- 🔸 Botão principal com gradiente -->
  <a href="https://open.spotify.com/user/31smb24pscew3akwdhp2dbpyluni" target="_blank" rel="noopener noreferrer">
    <div style="
      display: inline-block;
      padding: 12px 24px;
      border-radius: 10px;
      font-family: 'Segoe UI', sans-serif;
      font-weight: bold;
      font-size: 16px;
      color: white;
      text-decoration: none;
      background: linear-gradient(90deg, #1DB954, #5865F2);
      box-shadow: 0 0 12px rgba(88,101,242,0.4);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    ">
      🎧 Abrir Modo Foco no Spotify
    </div>
  </a>

  <!-- 🔸 Player (fora do GitHub) -->
  <div class="spotify-embed" style="margin-top: 25px;">
    <iframe 
      style="border-radius:12px"
      src="https://open.spotify.com/embed/playlist/37i9dQZF1DWZeKCadgRdKQ?utm_source=generator"
      width="420"
      height="352"
      frameborder="0"
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      loading="lazy">
    </iframe>
  </div>

  <!-- 🔸 Fallback (para GitHub) -->
  <div class="spotify-fallback" style="margin-top: 25px;">
    <a href="https://open.spotify.com/playlist/37i9dQZF1DWZeKCadgRdKQ" target="_blank" rel="noopener noreferrer">
      <img 
        src="https://i.scdn.co/image/ab67706f000000021cbb8f8e0e2d86b6fefbfb3a" 
        alt="Playlist Deep Focus" 
        width="350" 
        style="border-radius:12px; box-shadow: 0 0 20px rgba(29,185,84,0.3), 0 0 20px rgba(88,101,242,0.3);" 
        title="Abrir Playlist no Spotify" />
    </a>
  </div>
</section>

<!-- 🔹 Script inteligente: escolhe versão conforme ambiente -->
<script>
  const isGithub = window.location.hostname.includes("github.io") || window.location.hostname.includes("github.com");

  if (isGithub) {
    document.querySelector('.spotify-embed').style.display = 'none';
    document.querySelector('.spotify-fallback').style.display = 'block';
  } else {
    document.querySelector('.spotify-embed').style.display = 'block';
    document.querySelector('.spotify-fallback').style.display = 'none';
  }
</script>

