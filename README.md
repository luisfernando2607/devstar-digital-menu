<div align="center">

# 🍽️ DevStar Digital Menu

**Menú digital y pedidos de almuerzo por WhatsApp para restaurantes y equipos de trabajo**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)

</div>

---

## 💡 ¿Cómo funciona?

1. El **administrador** arma el menú del día en `admin.html` y comparte el enlace (o un QR).
2. Cada **persona** abre el enlace, elige sus opciones y escribe su nombre.
3. El pedido se envía **por WhatsApp** al número configurado y, opcionalmente, queda registrado en **Google Sheets**.

Sin servidor, sin base de datos y sin instalar nada: son dos archivos HTML.

---

## ✨ Funcionalidades

**Vista del cliente — `index.html`**

- Menú por secciones con selección táctil, pensado para móvil
- Resumen del pedido antes de enviar
- Envío directo por WhatsApp con el mensaje ya armado
- Modo claro / oscuro

**Panel de administración — `admin.html`**

- Editor del menú del día: agregar, editar y restablecer secciones
- Número de WhatsApp destino, saludo y mensaje de cierre configurables
- Webhook opcional a Google Sheets (Apps Script)
- Enlace para compartir, vista previa y botón para compartir por WhatsApp

---

## 🚀 Uso

```bash
git clone https://github.com/luisfernando2607/devstar-digital-menu.git
```

Publica la carpeta en cualquier hosting estático (GitHub Pages, Netlify, Vercel) o ábrela localmente. Configura el menú desde `admin.html`.

---

<div align="center">

Desarrollado por **[Luis Fernando Flores](https://github.com/luisfernando2607)** · DevStar · Guayaquil, Ecuador 🇪🇨

</div>
