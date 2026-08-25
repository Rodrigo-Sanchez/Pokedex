# 🔴 Pokédex 📖🔍

¡Bienvenido al proyecto **Pokédex Colaborativa**! Este es un repositorio centralizado donde entrenadores e investigadores Pokémon de todo el mundo pueden contribuir documentando las diferentes especies descubiertas.

## 🎯 Objetivo del proyecto
Crear la base de datos de Pokémon más completa y organizada por tipos, utilizando un flujo de trabajo de control de versiones basado en **Git**. Este proyecto está diseñado para aprender a colaborar en equipo de manera ordenada.

## 📂 Estructura del repositorio
El inventario de la Pokédex está organizado en carpetas según el tipo principal del Pokémon. Cada especie cuenta con su propio archivo de registro.

```text
pokedex/
├── README.md
├── agua/
│   └── 007_Squirtle.png
│   └── 007_Squirtle.md
├── fuego/
│   └── 004_Charmander.png
│   └── 004_Charmander.md
└── planta/
│   └── 001_Bulbasaur.png
│   └── 001_Bulbasaur.md
```

## 🛠️ Cómo contribuir (Flujo de Trabajo Git)

Si eres un nuevo investigador que desea registrar sus hallazgos, sigue estos pasos para agregar tu información a la Pokédex Global:

### 1. Obtener tu propia Pokédex (`git clone`)
Descarga una copia exacta de la base de datos global a tu computadora local, aceptando la invitación de colaboración en Github Classroom:
```bash
https://classroom.github.com/a/ZQmPTCZW
```

### 2. Registrar un nuevo Pokémon
[De este recurso en línea con el listado de pokemones disponi.](https://www.wikidex.net/wiki/Lista_de_Pok%C3%A9mon_de_la_primera_generaci%C3%B3n)
Crea un archivo nuevo en la carpeta correspondiente a su tipo (por ejemplo, `psiquico/063_Abra.md`) y anota sus datos. Para verificar qué archivos has modificado o creado recientemente en tu terminal, usa:
```bash
git status
```

### 3. Preparar los datos (`git add`)
Selecciona y "captura" los archivos que deseas incluir en tu próximo reporte de investigación (staging area):
```bash
git add psiquico/063_Abra.md
```

### 4. Sellar tu reporte local (`git commit`)
Guarda tus cambios de manera permanente en el historial de tu computadora con un mensaje claro de lo que hiciste:
```bash
git commit -m "Agrega el registro detallado de Abra a la sección de tipo psíquico"
```

### 5. Sincronizar con el laboratorio central (`git push`)
Envía tus descubrimientos a la Pokédex Global en la nube (el repositorio remoto) para compartirlos con el resto del equipo:
```bash
git push origin main
```

## 📝 Plantilla de Registro (Formato Markdown)
Al crear el archivo de un nuevo Pokémon, te pedimos amablemente utilizar la siguiente plantilla para mantener el orden:

```markdown
# [Nombre del Pokémon]
- **Tipo:** [Fuego / Agua / Planta / Eléctrico / etc.]
- **Altura:** [metros]
- **Peso:** [kilogramos]
- **Habilidad Principal:** [Nombre de la habilidad]
- **Descripción:** [Una breve descripción del Pokémon y su comportamiento]  
```

---
*Proyecto de código abierto mantenido por el Laboratorio de Investigación Pokémon de alumnos de Introducción a Ciencias de la Computación.*
