# Desencadenado: app Android

## Si ya tenés el repo en GitHub (actualizar)

1. Entrá al repo `desencadenado` en github.com.
2. Tocá **Add file > Upload files** y subí, reemplazando los anteriores:
   - `package.json`
   - `LEEME.md`
   - la carpeta `www` completa (`index.html` y `xlsx.full.min.js`)
3. Tocá **Commit changes**. GitHub compila solo (pestaña **Actions**, 5 a 8 minutos).
4. Desde el celular: repo > **Releases** > la versión más nueva > `Desencadenado.apk`. Instalala encima de la anterior.

## Primera vez (desde cero)

1. En github.com tocá **New repository**, nombre `desencadenado` (puede ser privado) y **Create repository**.
2. Tocá **uploading an existing file** y arrastrá todo el contenido de esta carpeta, incluida la carpeta oculta `.github` (en Windows: Ver > Elementos ocultos) y la carpeta `keystore`. **Commit changes**.
   - Si `.github` no se sube: **Add file > Create new file**, nombre `.github/workflows/build-apk.yml`, y pegá el contenido de ese archivo.
3. Pestaña **Actions**: "Compilar APK" corre solo. Si no arranca: "Compilar APK" > **Run workflow**.
4. Cuando quede en verde, desde el celular: repo > **Releases** > `Desencadenado.apk`.
5. Abrilo y aceptá "instalar apps de origen desconocido" cuando Android lo pida.

## Pasar tus registros

- Si en el celular tenías la versión anterior del APK, los datos pasan solos al abrir la nueva.
- Para traer lo que cargaste en la app web: abrí `migracion-desencadenado.txt`, copiá todo el texto, y en la app andá a **Progreso > Copia de seguridad > Mostrar**, borrá lo que haya, pegalo y tocá **Cargar**.

## Qué tiene

- Semanas 1 a 11, repeticiones por serie (segundos en planchas), peso y variante.
- Ciclos: al terminar el programa, "Empezar ciclo nuevo" guarda la vuelta anterior para comparar.
- Progreso: avance por semana, gráfico y tabla por ejercicio.
- Exportar Excel: se abre el menú de compartir para guardarlo en Drive, mandarlo por WhatsApp o mail.
- Temporizadores en ejercicios por tiempo y barra de descanso de 30, 60 o 90 s.
- Copia de seguridad en texto. Los datos viven en el celular: hacé una copia cada tanto.

No borres la carpeta `keystore`: es lo que permite instalar actualizaciones sin perder los datos.
