<head>
    <link rel="stylesheet" href="style.css">
    <script>
        // Script pour cacher le menu lorsque l'utilisateur scroll vers le bas
        document.addEventListener("DOMContentLoaded", function() {
            let lastScrollTop = 0;
            const nav = document.querySelector('nav');
            
            window.addEventListener("scroll", function() {
                let scrollTop = window.pageYOffset || document.documentElement.scrollTop;

                if (scrollTop > lastScrollTop) {
                    // Scroll vers le bas, on cache le menu
                    nav.style.top = "-100px";  // Déplace le menu vers le haut pour le cacher
                } else {
                    // Scroll vers le haut, on montre le menu
                    nav.style.top = "0";
                }
                lastScrollTop = scrollTop;
            });
        });
    </script>
</head>

<!-- Menu de navigation fixe -->
<nav style="position: fixed; top: 0; left: 0; width: 100%; background-color: #8b4513; color: white; text-align: center; padding: 10px 0; z-index: 1000; transition: top 0.3s;">
    <ul style="list-style-type: none; margin: 0; padding: 0; display: flex; justify-content: center; gap: 20px;">
        <li><a href="#history" style="color: white; text-decoration: none; font-size: 1.2em;">History</a></li>
        <li><a href="#culture" style="color: white; text-decoration: none; font-size: 1.2em;">Culture</a></li>
        <li><a href="#food" style="color: white; text-decoration: none; font-size: 1.2em;">Food</a></li>
        <li><a href="#restaurants" style="color: white; text-decoration: none; font-size: 1.2em;">Restaurants</a></li>
        <li><a href="#tourism" style="color: white; text-decoration: none; font-size: 1.2em;">Tourism</a></li>
        <li><a href="#mea" style="color: white; text-decoration: none; font-size: 1.2em;">MEA</a></li>
        <li><a href="#when-to-visit" style="color: white; text-decoration: none; font-size: 1.2em;">When to Visit</a></li>
    </ul>
</nav>

<!-- Full-width image with center alignment -->
<p style="text-align: center; margin-top: 60px;"> <!-- Ajout d'une marge pour compenser le menu fixe -->
  <a href="when-to-visit.md">
    <img src="https://raw.githubusercontent.com/Mary-create24/escapade-libanaise/main/images/1-image-liban.jpg" alt="Image du Liban" style="width: 100%;">
  </a>
</p>

<!-- Stylized title -->
<h1 style="text-align: center; font-family: 'Cairo', sans-serif;">
  <span style="color: red;">Escapade</span>
  <span style="color: white; background-color: red; padding: 0 5px;">Libanaise</span>
  <span style="color: green;">.com</span>
</h1>

# Welcome to Escapade Libanaise

Explore the rich culture and history of Lebanon. Here are some sections to check out:

## Sections

### History {#history}
- [History](history.md)

### Culture {#culture}
- [Culture](culture.md)

### Food {#food}
- [Food](food.md)

### Restaurants {#restaurants}
- [Restaurants](restaurant.md)

### Tourism {#tourism}
- [Tourism](tourism.md)

### Middle East Airlines (MEA) {#mea}
- [MEA](mea.md)

### When to Visit Lebanon {#when-to-visit}
- [When to Visit Lebanon](when-to-visit.md)

**Discover the Beauty of Lebanon!**
