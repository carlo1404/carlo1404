<p align="center">
  <img src="https://i.pinimg.com/originals/fc/52/bf/fc52bfda1b8cbb0b5f2826b8d9b49d5c.gif" width="220" alt="Hacker Art"/>
</p>

<h1 align="center">👋 ¡Hola! Soy Andresitow</h1>

<p align="center"><i>Programador Full Stack autodidacta, con buen humor y cero tolerancia al código feo.</i></p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FFFF&center=true&vCenter=true&width=480&lines=Full+Stack+Developer;Node.js+%2B+Express+Lover;JavaScript+is+my+second+language;Mongo+MySQL+Postgres%3F+Bring+it+on!;VS+Code+%E2%86%92+Santuario+del+Debug" />
</p>

---

### 🧰 Tecnologías y herramientas favoritas

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" title="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" title="Node.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="40" title="Express.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" title="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" title="CSS3"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" title="MySQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="40" title="MongoDB"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" title="Git"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40" title="VS Code"/>
</p>

---

### 🚧 Proyectos que me tienen despierto a las 3 AM

- 🛒 E-commerce con carrito, login y pagos en tiempo real
- 🔧 Sistema administrativo para taller de motos con facturación
- 🎬 Plataforma de videoclub en Python orientado a objetos
- 🧑‍💻 Panel de usuario con actualización de datos, foto de perfil y cambio de contraseña
- 📦 Sistema CRUD modular hecho con Node.js + Express + Mongo

---

### ⚡ Código que me representa

```js
// Cuando el cliente pide una nueva funcionalidad
app.post("/nueva-idea", (req, res) => {
  try {
    construirEnTiempoRecord(req.idea);
    res.status(200).send("¡Ya está en producción!");
  } catch (error) {
    console.error("Ups...", error);
    res.status(500).send("Fue culpa del cliente.");
  }
});
