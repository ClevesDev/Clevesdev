## Hi there 👋
# 🚀 Hola, soy Dimas | Software Engineer Student

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00ADB5&center=true&vCenter=true&width=600&lines=Software+Engineer+Student;Flutter+%26+Dart+Developer;Aesthetic+Engineering+%26+Clean+Architecture" alt="Typing SVG" />
</p>

---

### ⚡ Sobre mí
Soy desarrollador de software enfocado en la creación de aplicaciones móviles robustas bajo el estándar de **Clean Architecture** y la estética del **Minimalismo Suizo**. Me apasiona optimizar la experiencia de usuario (UI/UX) y el rendimiento en sistemas móviles.

* 📱 **Desarrollo Móvil**: Especializado en Dart & Flutter para soluciones multiplataforma de alto rendimiento.
* 📐 **Arquitectura**: Fiel creyente del código limpio, desacoplado y con principios SOLID.
* 🎓 **Formación**: Estudiante de Ingeniería de Software en la Universidad Alejandro de Humboldt.

---

### 📹 Krust ERP (Showcase)
Demostración de la aplicación en funcionamiento (POS, inventario offline-first y diseño visual premium):

<p align="center">
  <video src="assets/showcase.mp4" width="700" autoplay loop muted playsinline style="border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.45);"></video>
</p>

---

### 🕹️ Pacman Arcade (Interactive Animation)
<p align="center">
  <svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg" style="background: #0D1117; border-radius: 16px; border: 2px solid #00ADB5;">
    <style>
      @keyframes pacman-move {
        0% { transform: translateX(-100px); }
        100% { transform: translateX(900px); }
      }
      @keyframes pacman-chomp {
        0%, 100% { clip-path: polygon(100% 74%, 75% 75%, 100% 76%, 100% 100%, 0% 100%, 0% 0%, 100% 0%); }
        50% { clip-path: polygon(100% 50%, 75% 75%, 100% 100%, 100% 100%, 0% 100%, 0% 0%, 100% 0%); }
      }
      @keyframes ghost-move {
        0% { transform: translateX(-180px); }
        100% { transform: translateX(820px); }
      }
      @keyframes dot-1 { 0%, 20% { opacity: 1; } 22%, 100% { opacity: 0; } }
      @keyframes dot-2 { 0%, 32% { opacity: 1; } 34%, 100% { opacity: 0; } }
      @keyframes dot-3 { 0%, 45% { opacity: 1; } 47%, 100% { opacity: 0; } }
      @keyframes dot-4 { 0%, 57% { opacity: 1; } 59%, 100% { opacity: 0; } }
      @keyframes dot-5 { 0%, 70% { opacity: 1; } 72%, 100% { opacity: 0; } }
      @keyframes dot-6 { 0%, 82% { opacity: 1; } 84%, 100% { opacity: 0; } }
      
      .pacman { animation: pacman-move 8s linear infinite; }
      .pacman-body { fill: #FFD700; animation: pacman-chomp 0.3s ease-in-out infinite; }
      .ghost { animation: ghost-move 8s linear infinite; }
      .d1 { fill: #00ADB5; animation: dot-1 8s step-end infinite; }
      .d2 { fill: #00ADB5; animation: dot-2 8s step-end infinite; }
      .d3 { fill: #00ADB5; animation: dot-3 8s step-end infinite; }
      .d4 { fill: #00ADB5; animation: dot-4 8s step-end infinite; }
      .d5 { fill: #00ADB5; animation: dot-5 8s step-end infinite; }
      .d6 { fill: #00ADB5; animation: dot-6 8s step-end infinite; }
    </style>

    <!-- Laberinto de fondo (Líneas de borde neon) -->
    <line x1="0" y1="20" x2="800" y2="20" stroke="#1F2937" stroke-width="2" stroke-dasharray="10 5" />
    <line x1="0" y1="100" x2="800" y2="100" stroke="#1F2937" stroke-width="2" stroke-dasharray="10 5" />

    <!-- Comida (Dots) -->
    <circle cx="120" cy="60" r="6" class="d1" />
    <circle cx="220" cy="60" r="6" class="d2" />
    <circle cx="320" cy="60" r="6" class="d3" />
    <circle cx="420" cy="60" r="6" class="d4" />
    <circle cx="520" cy="60" r="6" class="d5" />
    <circle cx="620" cy="60" r="6" class="d6" />

    <!-- Pacman -->
    <g class="pacman">
      <g transform="translate(100, 60)">
        <circle cx="0" cy="0" r="22" class="pacman-body" />
        <circle cx="4" cy="-10" r="2.5" fill="#000000" />
      </g>
    </g>

    <!-- Fantasma Blinky (Persiguiendo a Pacman) -->
    <g class="ghost">
      <g transform="translate(30, 60)">
        <path d="M -18,12 L -18,-8 A 18,18 0 0,1 18,-8 L 18,12 L 12,6 L 6,12 L 0,6 L -6,12 L -12,6 Z" fill="#FF0000" />
        <circle cx="-6" cy="-4" r="4.5" fill="#FFFFFF" />
        <circle cx="6" cy="-4" r="4.5" fill="#FFFFFF" />
        <circle cx="-4.5" cy="-4" r="1.8" fill="#0000FF" />
        <circle cx="7.5" cy="-4" r="1.8" fill="#0000FF" />
      </g>
    </g>
  </svg>
</p>

---

### 🛠️ Stack Tecnológico
<p align="left">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

---

### 📫 Conéctate conmigo
<p align="left">
  <a href="https://linkedin.com/in/dimas-cleves"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:dimascleves.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>
