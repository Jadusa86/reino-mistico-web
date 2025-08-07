# Reino Místico - Documentación de Despliegue

## Estructura de Archivos Creados

```
landing-page/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interactivo
└── legal.md           # Términos legales
```

## Instrucciones de Despliegue

### Opción 1: GitHub Pages (Recomendado - Gratuito)

1. **Crear repositorio en GitHub:**
   ```bash
   # Crear nuevo repositorio llamado "reino-mistico-web"
   git init
   git add .
   git commit -m "Initial landing page"
   git remote add origin https://github.com/tu-usuario/reino-mistico-web.git
   git push -u origin main
   ```

2. **Activar GitHub Pages:**
   - Ve a Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Tu sitio estará en: `https://tu-usuario.github.io/reino-mistico-web`

### Opción 2: Netlify (Fácil y profesional)

1. **Conectar con GitHub:**
   - Ve a [Netlify.com](https://netlify.com)
   - "New site from Git"
   - Conecta tu repositorio GitHub
   - Auto-deploy activado

2. **Dominio personalizado (opcional):**
   - Compra dominio en Namecheap/GoDaddy
   - Ejemplo: `reino-mistico.com`
   - Configurar DNS en Netlify

### Opción 3: Vercel

1. **Desplegar con Vercel:**
   ```bash
   npx vercel --prod
   ```
   - Seguir instrucciones en pantalla
   - Conectar con GitHub para auto-deploy

## Configuraciones Importantes

### 1. Actualizar Enlaces del Bot

En `index.html`, cambiar todas las instancias de:
```html
https://t.me/TuBotTarotBot
```

Por tu bot real:
```html
https://t.me/TuBotRealName
```

### 2. Configurar Email de Contacto

Cambiar en `index.html` y `legal.md`:
```html
contacto@reino-mistico.com
```

Por tu email real:
```html
tu-email@gmail.com
```

### 3. Información para Stripe

Una vez desplegado, usar esta URL como "Business Website":
```
https://tu-usuario.github.io/reino-mistico-web
```

O tu dominio personalizado:
```
https://reino-mistico.com
```

## Características Incluidas

### ✅ Requerimientos de Stripe
- Información de contacto completa
- Términos y condiciones detallados
- Política de privacidad y reembolsos
- Descripción clara de servicios
- Precios transparentes

### ✅ SEO Optimizada
- Meta tags apropiados
- Estructura semántica HTML5
- Velocidad de carga optimizada
- Responsive design

### ✅ Profesional
- Diseño moderno y místico
- Animaciones sutiles
- Navegación intuitiva
- Call-to-actions claros

### ✅ Legal Compliance
- GDPR compatible
- Términos legales españoles
- Política de cookies
- Información corporativa

## Próximos Pasos

1. **Subir archivos a GitHub**
2. **Activar GitHub Pages**
3. **Actualizar enlaces del bot**
4. **Configurar Stripe con la nueva URL**
5. **Opcional: Comprar dominio personalizado**

## URLs de Ejemplo

Después del despliegue tendrás:
- **Página principal**: `https://tu-sitio.com`
- **Para Stripe**: Usar esta URL como "Business Website"
- **Bot de Telegram**: Enlazado desde múltiples botones CTA

## Mantenimiento

- **Actualizar precios**: Editar `index.html`
- **Cambiar maestros**: Modificar sección de maestros
- **Nuevos servicios**: Agregar a sección de servicios
- **Legal updates**: Editar `legal.md`

¿Necesitas ayuda con algún paso del despliegue?
