# 🛡️ IMT Lazarus Blocker & Proxy

Una solución ligera para interceptar y bloquear las conexiones y dominios de control de **IMT Lazarus**. Permite alojar el script de proxy tanto en `localhost` como en **GitHub**, ofreciendo un enlace URL remoto para configurar el proxy en tus dispositivos.

---

## 📌 ¿Cómo funciona?

El proyecto utiliza un archivo de configuración/proxy que redirige o bloquea las peticiones dirigidas a los servidores de IMT Lazarus. Puedes usar este archivo localmente o alojarlo en la nube para obtener una URL directa de proxy.

---

## 🚀 Opciones de Alojamiento (Hosting)

### 1. Alojamiento en `localhost`
* Ejecuta el servidor proxy en tu equipo local utilizando el código proporcionado en este repositorio.
* Apunta la configuración de red de tu navegador o sistema a `http://localhost:<PUERTO>`.

### 2. Alojamiento en GitHub / GitHub Pages
Si necesitas un enlace accesible desde cualquier lugar sin mantener tu PC encendido:
1. Sube este repositorio a tu cuenta de GitHub.
2. Activa **GitHub Pages** desde `Settings` -> `Pages` en tu repositorio.
3. Obtén la URL pública generada (o usa el enlace `Raw` del archivo proxy/PAC) para usarla como la dirección de proxy automático en tus dispositivos.

4. ## ⚡ Enlace Listo para Usar (Opción Rápida)

Si no quieres configurar un servidor ni crear tu propio repositorio, puedes usar directamente el archivo PAC que ya se encuentra activo y alojado en GitHub Gist:

🔗 **URL del Proxy PAC:**
```text
[https://gist.githubusercontent.com/acorik/8a1115e070eed38038cb4be931c74a4e/raw/5612956c9654888b0b11e99259f01f8383cf4fe1/proxy.pac](https://gist.githubusercontent.com/acorik/8a1115e070eed38038cb4be931c74a4e/raw/5612956c9654888b0b11e99259f01f8383cf4fe1/proxy.pac)

---

## 📱 Configuración en Móviles (Bypass de restricciones de colegio)

La mayoría de centros educativos bloquean la opción de cambiar o editar la configuración del proxy en los ajustes globales del sistema o del navegador en ordenadores gestionados. Sin embargo, en **dispositivos móviles (Android / iOS)** es posible omitir este bloqueo mediante métodos alternativos:

* **Aplicaciones de gestión de Proxy/VPN local:**
  * **Android:** Usa herramientas como *ProxyDroid*, *Every Proxy* o *HTTP Injector* para forzar el uso de una URL de proxy o script PAC a nivel de aplicación o interfaz de red.
  * **iOS (iPhone/iPad):** Puedes utilizar aplicaciones de gestión de tráfico de red (como *Shadowrocket* o *Potatso*) o perfiles de red personalizados para cargar la URL del proxy alojado en GitHub aunque los ajustes del sistema estén limitados.
* **Ajustes de Wi-Fi:** En la red Wi-Fi conectada, accede a *Ajustes Avanzados* -> *Proxy* -> *Configuración Automática (PAC)* e introduce el enlace alojado en GitHub.

---

## ⚙️ Instalación y Configuración Rápidas

1. **Clona el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/imt-lazarus-blocker.git](https://github.com/tu-usuario/imt-lazarus-blocker.git)
