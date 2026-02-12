# softwarelibresv.com

Sitio web de recopilaciones de Software Libre para El Salvador, inspirado en cdlibre.org pero adaptado al contexto salvadoreño.

## 🚀 Publicar en GitHub Pages

### Paso 1: Crear el repositorio

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Clic en el botón **"New"** (nuevo repositorio)
3. Nombre del repositorio: `softwarelibresv.com` (o el que prefieras)
4. Marca como **Public** (público)
5. Clic en **"Create repository"**

### Paso 2: Subir los archivos

**Opción A: Desde la web de GitHub (más fácil)**

1. En tu repositorio nuevo, clic en **"uploading an existing file"**
2. Arrastra TODOS los archivos y carpetas de este proyecto
3. Escribe un mensaje de commit: "Initial commit - sitio web softwarelibresv"
4. Clic en **"Commit changes"**

**Opción B: Usando Git desde terminal (más profesional)**

```bash
# Navega a la carpeta donde están los archivos
cd ruta/a/los/archivos

# Inicializa Git
git init

# Agrega todos los archivos
git add .

# Haz el primer commit
git commit -m "Initial commit - sitio web softwarelibresv"

# Conecta con tu repositorio (reemplaza 'tuusuario')
git remote add origin https://github.com/tuusuario/softwarelibresv.com.git

# Sube los archivos
git branch -M main
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. En tu repositorio, ve a **Settings** (configuración)
2. En el menú lateral, busca **"Pages"**
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona **"main"** y carpeta **"/ (root)"**
5. Clic en **"Save"**

### Paso 4: Esperar y acceder

1. Espera 1-3 minutos para que GitHub compile el sitio
2. Refresca la página de Settings > Pages
3. Verás un mensaje: **"Your site is live at https://tuusuario.github.io/softwarelibresv.com/"**
4. ¡Listo! Tu sitio está publicado

## 🌐 Usar un dominio personalizado (opcional)

Si querés usar **softwarelibresv.com** como dominio:

1. Compra el dominio en un registrador (Namecheap, GoDaddy, etc.)
2. En la configuración DNS del dominio, agrega estos registros:

```
Tipo: A
Host: @
Valor: 185.199.108.153

Tipo: A
Host: @
Valor: 185.199.109.153

Tipo: A
Host: @
Valor: 185.199.110.153

Tipo: A
Host: @
Valor: 185.199.111.153

Tipo: CNAME
Host: www
Valor: tuusuario.github.io
```

3. En GitHub Pages (Settings > Pages), en **"Custom domain"** escribe: `softwarelibresv.com`
4. Marca **"Enforce HTTPS"**
5. Espera 24-48 horas para propagación DNS

## 📁 Estructura del Proyecto

```
softwarelibresv.com/
│
├── index.html              # Página principal
├── presentacion.html       # Sobre el proyecto
├── faq.html               # Preguntas frecuentes
├── participar.html        # Cómo colaborar
├── README.md              # Este archivo
│
├── css/
│   └── style.css          # Estilos del sitio
│
├── catalogo/              # (por crear)
│   └── index.html
│
├── boletin/               # (por crear)
│   └── index.html
│
└── descargas/             # (por crear)
    └── index.html
```

## 🎨 Características del Sitio

- ✅ Diseño responsive (funciona en móviles y tablets)
- ✅ Inspirado en cdlibre.org
- ✅ Adaptado al contexto salvadoreño
- ✅ CSS moderno y limpio
- ✅ Sin dependencias externas
- ✅ Optimizado para GitHub Pages
- ✅ Licencia Apache License 2.0

## 📝 Próximos Pasos

Para completar el sitio, necesitarás crear:

1. **Catálogo de programas** (`catalogo/index.html`)
2. **Sección de boletín** (`boletin/index.html`)
3. **Página de descargas** (`descargas/index.html`)
4. **Enlaces útiles** (`enlaces.html`)
5. **Estadísticas** (`estadisticas.html`)
6. **Novedades** (`novedades.html`)

## 🤝 Contribuir

Este es un proyecto de código abierto. Las contribuciones son bienvenidas:

1. Fork el repositorio
2. Crea una rama: `git checkout -b feature/nueva-funcionalidad`
3. Commit tus cambios: `git commit -m 'Agrega nueva funcionalidad'`
4. Push a la rama: `git push origin feature/nueva-funcionalidad`
5. Abre un Pull Request

## 📜 Licencia

Este proyecto está bajo licencia [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

**Desarrollado con ❤️ para la comunidad de Software Libre en El Salvador 🇸🇻**
