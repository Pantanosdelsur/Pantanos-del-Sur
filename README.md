# Pantanos del Sur — Web

Blog de pesca deportiva en los embalses de la Comunitat Valenciana.

## Estructura

```
pantanos-del-sur/
├── index.html              ← Página principal (HOME)
├── css/
│   └── style.css           ← Estilos completos
├── js/
│   └── main.js             ← JavaScript (nav, animaciones)
├── img/
│   ├── logo_principal.png  ← Logo circular completo
│   ├── logo_simplificado.png ← Icono para nav y favicon
│   └── logo_horizontal.png ← Logo para footer y banners
└── pages/
    ├── blog.html           ← Listado de artículos
    ├── articulo.html       ← Primer artículo (plantilla)
    ├── pantanos.html       ← Fichas de embalses
    ├── aventuras.html      ← Crónicas de salidas
    └── equipo.html         ← Material y afiliados
```

## Cómo subir a GitHub Pages (GRATIS)

### Paso 1 — Crear cuenta en GitHub
Ve a https://github.com y crea una cuenta gratuita si no tienes.

### Paso 2 — Crear repositorio
1. Haz clic en "New repository"
2. Nombre: `pantanos-del-sur` (o lo que quieras)
3. Márcalo como **Public**
4. Haz clic en "Create repository"

### Paso 3 — Subir los archivos
**Opción fácil (sin instalar nada):**
1. En el repositorio vacío, haz clic en "uploading an existing file"
2. Arrastra TODA la carpeta `pantanos-del-sur`
3. Escribe un mensaje como "Primera versión" y haz clic en "Commit changes"

### Paso 4 — Activar GitHub Pages
1. Ve a **Settings** del repositorio
2. En el menú izquierdo, haz clic en **Pages**
3. En "Source" selecciona **Deploy from a branch**
4. En "Branch" selecciona **main** y carpeta **/ (root)**
5. Haz clic en **Save**

### Paso 5 — Tu web está online
En 1-2 minutos la web estará en:
`https://TU_USUARIO.github.io/pantanos-del-sur/`

---

## Personalizar

### Cambiar imágenes
Las imágenes de fondo son de Unsplash (gratuitas). Para cambiarlas por fotos propias:
1. Pon tus fotos en la carpeta `img/`
2. Busca en los HTML `images.unsplash.com/...` y cambia por `../img/tu-foto.jpg`

### Añadir artículos
Copia el archivo `pages/articulo.html`, renómbralo y edita el contenido.
Luego añade el enlace en `pages/blog.html`.

### Dominio propio (opcional)
Si quieres `pantanosdelsur.com` en vez de `TU_USUARIO.github.io/...`:
- Compra el dominio (~10-12€/año en Namecheap, Dondominio, etc.)
- En GitHub Pages > Custom domain, escribe tu dominio
- Configura los DNS según las instrucciones de GitHub

---

Hecho con pasión desde Rojales 🎣
