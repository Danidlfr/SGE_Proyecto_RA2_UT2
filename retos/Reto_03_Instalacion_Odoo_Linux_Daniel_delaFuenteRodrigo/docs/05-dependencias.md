# 05 — Dependencias (Python, wkhtmltopdf, librerías)

1. Instala Python y paquetes de compilación:
   ```bash
   sudo apt -y install python3 python3-pip python3-venv build-essential libxslt1-dev      libzip-dev libldap2-dev libsasl2-dev libjpeg-dev libpq-dev
   ```

   Por defecto en Linux viene ya instalado, por lo que no suele hacer falta

2. Instala **wkhtmltopdf** compatible (para reportes PDF).  

   ![Instalar wkhtmltopdf](../assets/img/05-dependencias/paso01_instalarMkhtmltopdf.png)

3. Verifica versiones:
   ```bash
   python3 --version
   wkhtmltopdf --version
   ```

   ![Verificar versiones](../assets/img/05-dependencias/paso02_comprobarVersiones.png)

> Resultado esperado: dependencias instaladas y comprobadas.
