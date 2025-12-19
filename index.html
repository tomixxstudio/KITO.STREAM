<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kito.Stream 🎵</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white flex flex-col min-h-screen">
  <!-- Header avec Connexion/Inscription -->
  <header class="bg-gray-800 p-4 flex justify-between items-center shadow-lg">
    <h1 class="text-3xl font-extrabold text-green-400">Kito.Stream 🎧</h1>
    <div id="auth-buttons">
      <a href="#" onclick="openLogin()" class="text-lg font-semibold hover:text-green-400">🔑 Connexion</a> |
      <a href="#" onclick="openSignup()" class="text-lg font-semibold hover:text-green-400">📝 Inscription</a>
    </div>
    <div id="user-info" class="hidden">
      <span id="username-display" class="mr-4"></span>
      <button onclick="logout()" class="text-lg font-semibold hover:text-red-400">🚪 Déconnexion</button>
    </div>
  </header>
  
  <div class="flex flex-1">
    <!-- Sidebar de navigation -->
    <nav class="w-64 bg-gray-800 p-5 space-y-6 shadow-lg">
      <ul class="space-y-4 mt-5">
        <li><a href="#" onclick="showSection('home')" class="block text-lg font-semibold hover:text-green-400">🏠 Accueil</a></li>
        <li><a href="#" onclick="showSection('library')" class="block text-lg font-semibold hover:text-green-400">📚 Bibliothèque</a></li>
        <li><a href="#" onclick="showSection('playlist')" class="block text-lg font-semibold hover:text-green-400">🎶 Playlists</a></li>
        <li><a href="#" onclick="showSection('contact')" class="block text-lg font-semibold hover:text-green-400">📩 Contact</a></li>
        <li><a href="#" onclick="showSection('upload')" class="block text-lg font-semibold hover:text-green-400">📤 Partager ma musique</a></li>
      </ul>
    </nav>
    
    <!-- Contenu principal avec différentes sections -->
    <main class="flex-1 p-10 pb-24">
      <!-- Section Accueil -->
      <section id="home" class="page-section">
        <!-- Barre de recherche -->
        <div class="mb-6">
          <input type="text" id="search-input" placeholder="🔍 Rechercher une chanson..." class="w-full p-3 rounded-lg bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-green-400" oninput="searchSongs()">
        </div>
        <h2 class="text-4xl font-bold mb-8 text-green-300">🎵 Sélection du moment</h2>
        <div id="songs-grid" class="grid grid-cols-3 gap-6">
          <!-- Les chansons seront ajoutées dynamiquement -->
        </div>
      </section>
      
      <!-- Section Bibliothèque -->
      <section id="library" class="page-section hidden">
        <h2 class="text-4xl font-bold mb-8 text-green-300">📚 Bibliothèque</h2>
        <p class="mb-4">Découvrez toutes vos musiques préférées et explorez notre collection complète.</p>
        <div id="library-grid" class="mt-6 grid grid-cols-2 gap-4">
          <!-- Chansons de la bibliothèque -->
        </div>
      </section>
      
      <!-- Section Playlists -->
      <section id="playlist" class="page-section hidden">
        <h2 class="text-4xl font-bold mb-8 text-green-300">🎶 Mes Playlists</h2>
        <p class="mb-4">Voici les chansons que vous avez ajoutées à votre playlist :</p>
        <div id="playlist-content" class="mt-6 space-y-4">
          <p class="text-gray-400">Aucune chanson dans votre playlist. Ajoutez-en depuis l'accueil !</p>
        </div>
      </section>
      
      <!-- Section Contact -->
      <section id="contact" class="page-section hidden">
        <h2 class="text-4xl font-bold mb-8 text-green-300">📩 Contactez-nous</h2>
        <form onsubmit="handleContact(event)" class="space-y-4">
          <input type="text" id="contact-name" placeholder="Votre Nom" class="w-full p-3 rounded-lg bg-gray-700 text-white" required>
          <input type="email" id="contact-email" placeholder="Votre Email" class="w-full p-3 rounded-lg bg-gray-700 text-white" required>
          <textarea id="contact-message" placeholder="Votre Message" class="w-full p-3 rounded-lg bg-gray-700 text-white h-32" required></textarea>
          <button type="submit" class="w-full bg-green-500 py-3 rounded-lg text-gray-900 font-semibold hover:bg-green-400">Envoyer</button>
        </form>
        <div id="contact-success" class="hidden mt-4 p-4 bg-green-600 rounded-lg">
          Message envoyé avec succès !
        </div>
      </section>
      
      <!-- Section Partager ma musique -->
      <section id="upload" class="page-section hidden mt-12 p-6 bg-gray-800 rounded-lg">
        <h2 class="text-2xl font-bold text-green-400 mb-4 text-center">📤 Partager votre musique</h2>
        <p class="mb-4 text-center">Merci pour votre intérêt ! Votre musique sera vérifiée par un de nos collaborateurs.</p>
        <p class="mb-4 text-sm text-gray-400 text-center">En soumettant votre fichier, vous acceptez notre politique de droits d'auteur.</p>
        
        <div class="space-y-4">
          <input type="text" id="upload-title" placeholder="Titre de la chanson" class="w-full p-3 rounded-lg bg-gray-700 text-white">
          <input type="text" id="upload-artist" placeholder="Nom de l'artiste" class="w-full p-3 rounded-lg bg-gray-700 text-white">
          <input type="file" id="music-upload" accept="audio/*" class="hidden" onchange="handleFileSelect(event)">
          <label for="music-upload" class="cursor-pointer block text-center px-6 py-3 bg-green-500 text-gray-900 font-semibold rounded-lg hover:bg-green-400">
            🎵 Sélectionner un fichier audio
          </label>
          <div id="file-name" class="text-center text-gray-400"></div>
          <button onclick="submitMusic()" class="w-full bg-blue-500 py-3 rounded-lg text-white font-semibold hover:bg-blue-400">
            📤 Soumettre ma musique
          </button>
        </div>
        <div id="upload-success" class="hidden mt-4 p-4 bg-green-600 rounded-lg text-center">
          Musique soumise avec succès ! Elle sera vérifiée prochainement.
        </div>
      </section>
    </main>
  </div>
  
  <!-- Modale Connexion -->
  <div id="loginModal" class="hidden fixed inset-0 bg-black bg-opacity-75 flex items-center justify-center z-50">
    <div class="bg-gray-800 p-6 rounded-lg w-96">
      <h2 class="text-xl font-bold mb-4 text-white">🔑 Connexion</h2>
      <form onsubmit="handleLogin(event)" class="space-y-4">
        <input type="email" id="login-email" placeholder="Email" class="w-full p-2 rounded-lg bg-gray-700 text-white" required>
        <input type="password" id="login-password" placeholder="Mot de passe" class="w-full p-2 rounded-lg bg-gray-700 text-white" required>
        <button type="submit" class="w-full bg-green-500 p-2 rounded-lg text-gray-900 font-semibold hover:bg-green-400">Se connecter</button>
      </form>
      <div id="login-error" class="hidden mt-2 text-red-400 text-sm"></div>
      <button onclick="closeLogin()" class="mt-4 bg-red-500 p-2 rounded-lg w-full hover:bg-red-400">Fermer</button>
    </div>
  </div>
  
  <!-- Modale Inscription -->
  <div id="signupModal" class="hidden fixed inset-0 bg-black bg-opacity-75 flex items-center justify-center z-50">
    <div class="bg-gray-800 p-6 rounded-lg w-96">
      <h2 class="text-xl font-bold mb-4 text-white">📝 Inscription</h2>
      <form onsubmit="handleSignup(event)" class="space-y-4">
        <input type="text" id="signup-name" placeholder="Nom" class="w-full p-2 rounded-lg bg-gray-700 text-white" required>
        <input type="email" id="signup-email" placeholder="Email" class="w-full p-2 rounded-lg bg-gray-700 text-white" required>
        <input type="password" id="signup-password" placeholder="Mot de passe" class="w-full p-2 rounded-lg bg-gray-700 text-white" required>
        <button type="submit" class="w-full bg-green-500 p-2 rounded-lg text-gray-900 font-semibold hover:bg-green-400">S'inscrire</button>
      </form>
      <div id="signup-success" class="hidden mt-2 text-green-400 text-sm">Inscription réussie ! Connectez-vous maintenant.</div>
      <button onclick="closeSignup()" class="mt-4 bg-red-500 p-2 rounded-lg w-full hover:bg-red-400">Fermer</button>
    </div>
  </div>
  
  <!-- Footer -->
  <footer class="bg-gray-800 p-6 text-center mt-10">
    <p>
      © 2025 Kito.Stream - 
      <a href="#" class="text-green-400 hover:underline" onclick="showSection('contact')">Contact</a> | 
      <a href="#" class="text-green-400 hover:underline">Politique de confidentialité</a> | 
      <a href="#" class="text-green-400 hover:underline">Mentions légales</a> | 
      <a href="#" class="text-green-400 hover:underline">Plan du site</a>
    </p>
    <p class="mt-2 text-sm text-gray-400">Pour toute question, contactez-nous via notre formulaire de contact.</p>
  </footer>
  
  <!-- Lecteur audio persistant en bas -->
  <div class="fixed bottom-0 left-0 right-0 bg-gray-800 p-4 flex items-center justify-between shadow-lg z-40">
    <img id="player-cover" src="https://via.placeholder.com/48/444/fff?text=🎵" class="h-12 w-12 rounded-lg" alt="Pochette">
    <div class="flex-1 mx-4">
      <h3 id="player-title" class="text-lg">🎶 Sélectionnez une musique</h3>
      <p id="player-artist" class="text-sm text-gray-400"></p>
    </div>
    <audio id="audio-player" controls class="w-96">
      <source id="audio-source" src="" type="audio/mp3">
    </audio>
  </div>
  
  <script>
    // Base de données de chansons (simulée)
    const songDatabase = [
      {
        id: 1,
        title: "Summer Vibes",
        artist: "DJ Kito",
        cover: "https://via.placeholder.com/200/1db954/fff?text=Summer",
        audio: "https://cdnjs.cloudflare.com/ajax/libs/soundmanager2/2.97a.20150601/demo/mpc/audio/CHINA_1.mp3"
      },
      {
        id: 2,
        title: "Neon Dreams",
        artist: "Elektro Beat",
        cover: "https://via.placeholder.com/200/e91e63/fff?text=Neon",
        audio: "https://cdnjs.cloudflare.com/ajax/libs/soundmanager2/2.97a.20150601/demo/mpc/audio/CHINA_2.mp3"
      },
      {
        id: 3,
        title: "Midnight Jazz",
        artist: "Blue Notes",
        cover: "https://via.placeholder.com/200/3f51b5/fff?text=Jazz",
        audio: "https://cdnjs.cloudflare.com/ajax/libs/soundmanager2/2.97a.20150601/demo/mpc/audio/CHINA_3.mp3"
      },
      {
        id: 4,
        title: "Acoustic Soul",
        artist: "Harmony String",
        cover: "https://via.placeholder.com/200/ff9800/fff?text=Soul",
        audio: "https://cdnjs.cloudflare.com/ajax/libs/soundmanager2/2.97a.20150601/demo/mpc/audio/CHINA_4.mp3"
      },
      {
        id: 5,
        title: "Electronic Wave",
        artist: "Synth Master",
        cover: "https://via.placeholder.com/200/9c27b0/fff?text=Wave",
        audio: "https://cdnjs.cloudflare.com/ajax/libs/soundmanager2/2.97a.20150601/demo/mpc/audio/CHINA_5.mp3"
      },
      {
        id: 6,
        title: "Urban Flow",
        artist: "Street Beats",
        cover: "https://via.placeholder.com/200/00bcd4/fff?text=Urban",
        audio: "https://cdnjs.cloudflare.com/ajax/libs/soundmanager2/2.97a.20150601/demo/mpc/audio/CHINA_6.mp3"
      }
    ];
    
    // Gestion des utilisateurs et playlist
    let users = {};
    let currentUser = null;
    let playlist = [];
    let uploadedFile = null;
    
    // Initialisation
    function init() {
      renderSongs(songDatabase);
      renderLibrary();
      checkLoggedIn();
    }
    
    // Vérifier si un utilisateur est connecté
    function checkLoggedIn() {
      const savedUser = JSON.parse(localStorage.getItem('currentUser') || 'null');
      if (savedUser) {
        currentUser = savedUser;
        updateUIForLoggedIn();
        loadPlaylist();
      }
    }
    
    // Afficher les chansons
    function renderSongs(songs) {
      const grid = document.getElementById('songs-grid');
      grid.innerHTML = songs.map(song => `
        <div class="bg-gray-700 p-6 rounded-lg shadow-xl hover:bg-gray-600 transition duration-300">
          <img src="${song.cover}" alt="Pochette ${song.title}" class="w-full h-32 object-cover rounded-lg mb-4">
          <h3 class="text-xl font-semibold">${song.title}</h3>
          <p class="text-sm text-gray-400">${song.artist}</p>
          <button onclick="playMusic(${song.id})" class="w-full mt-4 bg-green-500 text-gray-900 py-2 rounded-lg hover:bg-green-400 font-semibold">▶ Play</button>
          <button onclick="addToPlaylist(${song.id})" class="w-full mt-2 bg-blue-500 text-white py-2 rounded-lg hover:bg-blue-400 font-semibold">➕ Ajouter</button>
        </div>
      `).join('');
    }
    
    // Afficher la bibliothèque
    function renderLibrary() {
      const grid = document.getElementById('library-grid');
      grid.innerHTML = songDatabase.map(song => `
        <div class="bg-gray-700 p-4 rounded-lg hover:bg-gray-600 transition duration-300 cursor-pointer" onclick="playMusic(${song.id})">
          <img src="${song.cover}" alt="Pochette" class="w-full h-24 object-cover rounded-lg mb-2">
          <p class="font-semibold">${song.title}</p>
          <p class="text-sm text-gray-400">${song.artist}</p>
        </div>
      `).join('');
    }
    
    // Recherche de chansons
    function searchSongs() {
      const query = document.getElementById('search-input').value.toLowerCase();
      const filtered = songDatabase.filter(song => 
        song.title.toLowerCase().includes(query) || 
        song.artist.toLowerCase().includes(query)
      );
      renderSongs(filtered);
    }
    
    // Jouer une musique
    function playMusic(songId) {
      const song = songDatabase.find(s => s.id === songId);
      if (song) {
        const audioPlayer = document.getElementById("audio-player");
        const audioSource = document.getElementById("audio-source");
        
        audioSource.src = song.audio;
        audioPlayer.load();
        
        // Attendre que le chargement soit terminé avant de jouer
        audioPlayer.play().catch(error => {
          console.log("Erreur de lecture:", error);
          alert("Impossible de lire cette musique. Vérifiez votre connexion.");
        });
        
        document.getElementById("player-title").innerText = song.title;
        document.getElementById("player-artist").innerText = song.artist;
        document.getElementById("player-cover").src = song.cover;
      }
    }
    
    // Ajouter à la playlist
    function addToPlaylist(songId) {
      if (!currentUser) {
        alert('Veuillez vous connecter pour ajouter des chansons à votre playlist !');
        openLogin();
        return;
      }
      
      if (!playlist.find(id => id === songId)) {
        playlist.push(songId);
        savePlaylist();
        renderPlaylist();
        alert('Chanson ajoutée à votre playlist !');
      } else {
        alert('Cette chanson est déjà dans votre playlist !');
      }
    }
    
    // Sauvegarder la playlist
    function savePlaylist() {
      if (currentUser) {
        localStorage.setItem(`playlist_${currentUser.email}`, JSON.stringify(playlist));
      }
    }
    
    // Charger la playlist
    function loadPlaylist() {
      if (currentUser) {
        playlist = JSON.parse(localStorage.getItem(`playlist_${currentUser.email}`) || '[]');
        renderPlaylist();
      }
    }
    
    // Afficher la playlist
    function renderPlaylist() {
      const container = document.getElementById('playlist-content');
      if (playlist.length === 0) {
        container.innerHTML = '<p class="text-gray-400">Aucune chanson dans votre playlist. Ajoutez-en depuis l\'accueil !</p>';
        return;
      }
      
      container.innerHTML = playlist.map(songId => {
        const song = songDatabase.find(s => s.id === songId);
        return `
          <div class="bg-gray-700 p-4 rounded-lg flex items-center justify-between hover:bg-gray-600 transition duration-300">
            <div class="flex items-center space-x-4">
              <img src="${song.cover}" alt="Pochette" class="h-16 w-16 rounded-lg">
              <div>
                <p class="font-semibold">${song.title}</p>
                <p class="text-sm text-gray-400">${song.artist}</p>
              </div>
            </div>
            <div class="flex space-x-2">
              <button onclick="playMusic(${song.id})" class="bg-green-500 px-4 py-2 rounded-lg hover:bg-green-400">▶ Play</button>
              <button onclick="removeFromPlaylist(${song.id})" class="bg-red-500 px-4 py-2 rounded-lg hover:bg-red-400">✖ Retirer</button>
            </div>
          </div>
        `;
      }).join('');
    }
    
    // Retirer de la playlist
    function removeFromPlaylist(songId) {
      playlist = playlist.filter(id => id !== songId);
      savePlaylist();
      renderPlaylist();
    }
    
    // Gestion des sections
    function showSection(sectionId) {
      const sections = document.querySelectorAll('.page-section');
      sections.forEach(section => section.classList.add('hidden'));
      document.getElementById(sectionId).classList.remove('hidden');
    }
    
    // Gestion de l'inscription
    function handleSignup(event) {
      event.preventDefault();
      const name = document.getElementById('signup-name').value;
      const email = document.getElementById('signup-email').value;
      const password = document.getElementById('signup-password').value;
      
      users[email] = { name, email, password };
      localStorage.setItem('users', JSON.stringify(users));
      
      document.getElementById('signup-success').classList.remove('hidden');
      setTimeout(() => {
        closeSignup();
        openLogin();
      }, 1500);
    }
    
    // Gestion de la connexion
    function handleLogin(event) {
      event.preventDefault();
      const email = document.getElementById('login-email').value;
      const password = document.getElementById('login-password').value;
      
      const savedUsers = JSON.parse(localStorage.getItem('users') || '{}');
      const user = savedUsers[email];
      
      if (user && user.password === password) {
        currentUser = { name: user.name, email: user.email };
        localStorage.setItem('currentUser', JSON.stringify(currentUser));
        updateUIForLoggedIn();
        loadPlaylist();
        closeLogin();
      } else {
        const errorDiv = document.getElementById('login-error');
        errorDiv.textContent = 'Email ou mot de passe incorrect';
        errorDiv.classList.remove('hidden');
      }
    }
    
    // Mise à jour de l'UI pour utilisateur connecté
    function updateUIForLoggedIn() {
      document.getElementById('auth-buttons').classList.add('hidden');
      document.getElementById('user-info').classList.remove('hidden');
      document.getElementById('username-display').textContent = `Bonjour, ${currentUser.name} 👋`;
    }
    
    // Déconnexion
    function logout() {
      currentUser = null;
      playlist = [];
      localStorage.removeItem('currentUser');
      document.getElementById('auth-buttons').classList.remove('hidden');
      document.getElementById('user-info').classList.add('hidden');
      renderPlaylist();
      alert('Déconnexion réussie !');
    }
    
    // Modales
    function openLogin() {
      document.getElementById('loginModal').classList.remove('hidden');
      document.getElementById('login-error').classList.add('hidden');
    }
    
    function closeLogin() {
      document.getElementById('loginModal').classList.add('hidden');
    }
    
    function openSignup() {
      document.getElementById('signupModal').classList.remove('hidden');
      document.getElementById('signup-success').classList.add('hidden');
    }
    
    function closeSignup() {
      document.getElementById('signupModal').classList.add('hidden');
    }
    
    // Gestion du contact
    function handleContact(event) {
      event.preventDefault();
      const name = document.getElementById('contact-name').value;
      const email = document.getElementById('contact-email').value;
      const message = document.getElementById('contact-message').value;
      
      console.log('Message envoyé:', { name, email, message });
      document.getElementById('contact-success').classList.remove('hidden');
      event.target.reset();
      
      setTimeout(() => {
        document.getElementById('contact-success').classList.add('hidden');
      }, 3000);
    }
    
    // Gestion de l'upload
    function handleFileSelect(event) {
      uploadedFile = event.target.files[0];
      if (uploadedFile) {
        document.getElementById('file-name').textContent = `Fichier sélectionné : ${uploadedFile.name}`;
      }
    }
    
    function submitMusic() {
      const title = document.getElementById('upload-title').value;
      const artist = document.getElementById('upload-artist').value;
      
      if (!title || !artist || !uploadedFile) {
        alert('Veuillez remplir tous les champs et sélectionner un fichier audio.');
        return;
      }
      
      console.log('Musique soumise:', { title, artist, file: uploadedFile.name });
      document.getElementById('upload-success').classList.remove('hidden');
      document.getElementById('upload-title').value = '';
      document.getElementById('upload-artist').value = '';
      document.getElementById('file-name').textContent = '';
      uploadedFile = null;
      
      setTimeout(() => {
        document.getElementById('upload-success').classList.add('hidden');
      }, 3000);
    }
    
    // Initialiser l'application
    init();
  </script>
</body>
</html>
