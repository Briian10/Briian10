<div align="center">

# <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px"> ¡Hola! Soy Brian

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

<div align="center">
  
  [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&multiline=true&width=600&height=80&lines=Frontend+Developer+%F0%9F%92%9C;Creando+experiencias+digitales;Siempre+aprendiendo+algo+nuevo)](https://git.io/typing-svg)
  
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---

<div align="center">

## 🌟 Sobre mí

</div>

// BrianCard.tsx
export default function BrianCard() {
  const brian = {
    nombre: "Brian",
    rol: "Frontend Developer Jr.",
    ubicacion: "🌎 Somewhere coding...",
    experiencia: "Junior pero con mucha pasión",
    estado: "En constante aprendizaje 📚",
    motivacion: "Convertir ideas en experiencias digitales increíbles ✨",
    cafe_consumido: "∞ tazas y contando... ☕",
    tecnologias: {
      frontend: ["HTML5", "CSS3", "JavaScript", "React", "Tailwind CSS"],
      herramientas: ["Git", "VS Code", "Figma", "Vercel"],
      aprendiendo: ["TypeScript", "Next.js", "Node.js"],
      proximas_metas: ["Vue.js", "React Native", "Three.js"]
    }
  };

  return (
    <div className="max-w-4xl mx-auto mt-10 p-6 bg-white/30 dark:bg-gray-800/30 backdrop-blur-md border border-gray-200 dark:border-gray-700 rounded-2xl shadow-2xl transition-all duration-300 hover:scale-[1.02]">
      <div className="flex flex-col md:flex-row items-start md:items-center justify-between gap-6">
        <div>
          <h1 className="text-4xl font-extrabold text-gray-900 dark:text-white">{brian.nombre}</h1>
          <p className="text-lg text-indigo-600 dark:text-indigo-400">{brian.rol}</p>
        </div>
        <span className="px-4 py-2 rounded-full bg-indigo-100 text-indigo-700 dark:bg-indigo-900 dark:text-indigo-300 text-sm">
          {brian.ubicacion}
        </span>
      </div>

      <div className="mt-6 grid grid-cols-1 md:grid-cols-2 gap-4 text-sm text-gray-800 dark:text-gray-200">
        <Detail label="🚀 Experiencia" value={brian.experiencia} />
        <Detail label="📚 Estado actual" value={brian.estado} />
        <Detail label="☕ Café consumido" value={brian.cafe_consumido} />
        <Detail label="💡 Motivación" value={brian.motivacion} />
      </div>

      <div className="mt-8 grid grid-cols-1 md:grid-cols-2 gap-6">
        <TechList title="Frontend" items={brian.tecnologias.frontend} color="bg-pink-100" />
        <TechList title="Herramientas" items={brian.tecnologias.herramientas} color="bg-yellow-100" />
        <TechList title="Aprendiendo" items={brian.tecnologias.aprendiendo} color="bg-green-100" />
        <TechList title="Próximas metas" items={brian.tecnologias.proximas_metas} color="bg-blue-100" />
      </div>
    </div>
  );
}

function Detail({ label, value }: { label: string; value: string }) {
  return (
    <div className="flex items-start space-x-2">
      <span className="font-semibold">{label}:</span>
      <span>{value}</span>
    </div>
  );
}

function TechList({
  title,
  items,
  color
}: {
  title: string;
  items: string[];
  color: string;
}) {
  return (
    <div className={`p-4 rounded-lg ${color} dark:bg-opacity-10`}>
      <h3 className="font-bold text-gray-700 dark:text-gray-300 mb-2">{title}</h3>
      <ul className="flex flex-wrap gap-2">
        {items.map((tech) => (
          <li
            key={tech}
            className="px-3 py-1 bg-white/80 dark:bg-gray-700/50 rounded-full text-xs font-medium text-gray-900 dark:text-gray-100 shadow-sm"
          >
            {tech}
          </li>
        ))}
      </ul>
    </div>
  );
}


<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---

<div align="center">

## 🚀 Stack Tecnológico

### 💫 Frontend (Mi zona de comfort)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### 🔮 Explorando ahora
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

### 🛠️ Herramientas del día a día
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---

<div align="center">

## 🌟 Mi Journey como Frontend Developer

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=2000&pause=500&color=8B5CF6&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=120&lines=💪+Dominando:+HTML5+%7C+CSS3+%7C+JavaScript;🔥+Aprendiendo:+React+%7C+TypeScript+%7C+Tailwind;🚀+Próximo+nivel:+Next.js+%7C+Node.js+%7C+Fullstack;✨+Estado:+En+construcción+pero+con+mucha+pasión)](https://git.io/typing-svg)



</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---

<div align="center">

## 🎯 Proyectos que me enorgullecen

</div>

<div align="center">

### 🌟 Mi Portafolio Personal
[[![Portfolio](https://img.shields.io/badge/🚀_Ver_Portfolio-8B5CF6?style=for-the-badge&logoColor=white)](https://mi-portafolio-h34tfzg79-brians-projects-3a29f8e0.vercel.app/)]

*Mi espacio digital donde muestro mi evolución como developer*

</div>

<div align="center">

(https://mi-portafolio-two-lake.vercel.app/)


</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---

<div align="center">

### 🎯 Metas para 2025
- ✅ Crear mi primer portafolio
- 🔄 Dominar React y sus hooks
- 🔄 Aprender TypeScript
- ⏳ Contribuir a proyectos open source
- ⏳ Conseguir mi primer trabajo como Frontend Developer

</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---




---

<div align="center">

## 💭 Un poco más sobre mí...

</div>

<img align="right" alt="Coding" width="300" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">

```yaml
brian_dev:
  edad: "Joven y con ganas de aprender"
  personalidad: ["Curioso", "Perseverante", "Creativo"]
  
  que_me_motiva:
    - "Ver mi código funcionando perfectamente"
    - "Resolver bugs complicados (después de mucho café)"
    - "Crear interfaces que la gente realmente use"
    - "La sensación de 'Por fin funciona!' 🎉"
  
  cuando_no_programo:
    - 🎮 Gaming (para relajar la mente)
    - 📺 Viendo tutoriales en YouTube
    - 🏃‍♂️ Ejercicio (el cuerpo también necesita mantenimiento)
    - ☕ Probando nuevas cafeterías
  
  frase_favorita: "No es un bug, es una feature no documentada"
  estado_mental: "Siempre en modo aprendizaje 🧠"
```

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

---

<div align="center">

## 📫 ¡Conectemos y crecemos juntos!

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-8B5CF6?style=for-the-badge&logoColor=white)](https://mi-portafolio-h34tfzg79-brians-projects-3a29f8e0.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tu-perfil)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/tu-usuario)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tu-email@gmail.com)

---

![Profile Views](https://komarev.com/ghpvc/?username=TU_USERNAME&color=blueviolet&style=for-the-badge&label=Visitors)

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

</div>

---

<div align="center">

### 💫 *"Cada línea de código es un paso más cerca de mis sueños"*

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

**✨ Si mi perfil te inspira o mis proyectos te sirven, ¡dale una ⭐ a mis repos! ✨**

### 🚀 *Juntos construyamos el futuro, una línea de código a la vez*

</div>
