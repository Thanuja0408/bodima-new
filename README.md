# bodima-new
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login - Bodima.lk</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="min-h-screen flex items-center justify-center" style="background: linear-gradient(135deg, #ff6b35 0%, #f7931e 100%);">
  <div class="floating-elements absolute inset-0 pointer-events-none"></div>
  
  <!-- Dark Mode Toggle -->
  <button id="darkModeToggle" class="fixed top-6 right-6 z-50 bg-white/20 backdrop-blur-sm hover:bg-white/30 rounded-full p-3 text-white transition-all" title="Toggle Dark Mode">
    <span id="darkModeIcon">🌙</span>
  </button>
  
  <div class="relative z-10 w-full max-w-md mx-4">
    <div class="glass-effect rounded-3xl p-10 shadow-2xl">
      <div class="text-center mb-8">
        <h1 class="text-5xl font-bold text-white mb-2">🏠 Bodima.lk</h1>
        <p class="text-white/80 text-lg">Login to your account</p>
      </div>
      
      <form method="POST" action="" class="space-y-6">
        <div>
          <label for="username" class="block text-white font-semibold mb-2 text-lg">Username</label>
          <input 
            type="text" 
            id="username" 
            name="username"
            required 
            placeholder="Enter username"
            class="w-full px-6 py-4 border-0 rounded-xl bg-white/90 backdrop-blur-sm focus:ring-4 focus:ring-white/30 focus:outline-none text-lg shadow-lg"
          >
        </div>
        
        <div>
          <label for="password" class="block text-white font-semibold mb-2 text-lg">Password</label>
          <input 
            type="password" 
            id="password" 
            name="password"
            required 
            placeholder="Enter password"
            class="w-full px-6 py-4 border-0 rounded-xl bg-white/90 backdrop-blur-sm focus:ring-4 focus:ring-white/30 focus:outline-none text-lg shadow-lg"
          >
        </div>
        
                
        <button 
          type="submit" 
          class="w-full px-8 py-4 bg-gradient-to-r from-orange-500 to-orange-600 text-white rounded-xl hover:from-orange-600 hover:to-orange-700 transition-all duration-300 font-semibold text-lg shadow-lg hover:shadow-xl transform hover:scale-105"
        >
          Login
        </button>
      </form>
      
      <div class="mt-6 text-center">
        <a href="home.php" class="text-white/80 hover:text-white transition-colors">
          ← Back to Home
        </a>
      </div>
    </div>
  </div>
  
  <script src="script.js"></script>
</body>
</html>
