# Black Ops 6 Camo Tracker

## Descripción
El **Black Ops 6 Camo Tracker** es una herramienta web diseñada para ayudarte a realizar un seguimiento de tu progreso al desbloquear camuflajes en el juego **Call of Duty: Black Ops 6**. Esta aplicación te permite:

- Llevar un control de los desafíos completados para cada arma.
- Ver tu progreso general y por categoría de arma.
- Navegar entre las categorías y detalles específicos de cada arma.

El diseño es moderno, minimalista y responsivo, utilizando colores en tonos negros, blancos y naranjas para una experiencia visual atractiva.

---

## Funcionalidades
### 1. Página Principal (`index.html`)
- Bienvenida al usuario con una breve descripción de la aplicación.
- Acceso directo a las categorías de armas y a la página de progreso general.

### 2. Página de Categorías (`categories/assault_rifles.html`, etc.)
- Lista de todas las categorías disponibles (Fusiles de Asalto, Subfusiles, Escopetas, etc.).
- Cada categoría redirige a las armas específicas dentro de esa clase.

### 3. Detalles de Armas (`weapons/rifles_asaltos/xm4.html`, etc.)
- Lista de desafíos específicos para cada arma, incluyendo:
  - Headshots.
  - Desafíos especiales.
  - Desafíos de maestría (Oro, Diamante, Espina Oscura, Materia Oscura).
- **Funcionalidad de almacenamiento local**:
  - Los usuarios pueden marcar los desafíos completados.
  - El progreso se guarda automáticamente en el navegador utilizando `localStorage`.

### 4. Página de Progreso General (`dashboard.html`)
- Barra de progreso general que muestra el porcentaje de desafíos completados en todo el juego.
- Barras de progreso para cada categoría de arma (Fusiles de Asalto, Subfusiles, etc.).
- Sección con tarjetas interactivas para cada arma, que redirigen a sus detalles.

---

## Estructura del Proyecto
```plaintext
BO6/
├── index.html                # Página principal.
├── categories/               # Carpetas para las categorías de armas.
│   ├── assault_rifles.html   # Página de Fusiles de Asalto.
│   ├── smgs.html             # Página de Subfusiles.
│   └── ...                   # Otras categorías.
├── weapons/                  # Carpetas para detalles de armas.
│   ├── rifles_asaltos/       # Detalles de Fusiles de Asalto.
│   │   ├── xm4.html          # Página del XM4.
│   │   ├── ak47.html         # Página del AK-74.
│   │   └── ...               # Más armas.
├── styles/                   # Archivos de estilos.
│   └── style.css             # Estilo principal del proyecto.
├── scripts/                  # Archivos de JavaScript (si aplica).
├── dashboard.html            # Página de Progreso General.
└── README.md                 # Documentación del proyecto.
```

---

## Tecnologías Usadas
- **HTML5**: Estructura de las páginas.
- **CSS3**: Diseño responsivo y moderno con barras de progreso y tarjetas interactivas.
- **JavaScript**: Gestión de almacenamiento local para guardar el progreso del usuario.

---

## Instrucciones para Ejecutar
1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/Samueh02/BO6.git
   ```
2. Abre el archivo `index.html` en tu navegador.
3. Navega por las páginas y utiliza la funcionalidad de progreso.

---

## Próximos Pasos
- Implementar estadísticas avanzadas para los usuarios.
- Agregar más animaciones y personalización visual.
- Optimizar para dispositivos móviles y pantallas pequeñas.
- Añadir funcionalidades de usuario (registro y login).

---

## Autor
- **Samueh02**