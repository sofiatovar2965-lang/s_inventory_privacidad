# Política de Privacidad de S-Inventory

Proyecto web independiente (HTML estático) con la política de privacidad que se publicará para la ficha de Google Play.

> No forma parte del repositorio de la app `S-Inventory`.

Correo de contacto configurado: **adminsinventory@gmail.com**

## Publicar con GitHub Pages

1. Crea un repositorio público nuevo en GitHub, por ejemplo `s-inventory-privacidad`.
2. Sube este proyecto:

   ```powershell
   cd "C:\S-inventory privacidad"
   git init
   git add .
   git commit -m "Política de privacidad de S-Inventory"
   git remote add origin https://github.com/TU_USUARIO/s-inventory-privacidad.git
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` / carpeta **`/ (root)`**
   - Save

4. La URL pública será:

   ```
   https://TU_USUARIO.github.io/s-inventory-privacidad/
   ```

5. Copia esa URL en **Play Console → Política de privacidad**.

La página cumple los requisitos de Play: HTTPS, acceso público sin geovallado, página web estándar (no PDF) y específica para esta app.
