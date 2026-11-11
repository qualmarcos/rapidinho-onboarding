# 🇧🇷 Português Rapidinho · Bienvenida (onboarding)

Presentación de bienvenida para el inicio de las clases, con actividades que los alumnos responden en el celular.

- **Presentación:** https://qualmarcos.github.io/rapidinho-onboarding/
- **Página del alumno:** https://qualmarcos.github.io/rapidinho-onboarding/aluno.html (se abre con el QR)

## Actividades con celular

| Slide | Actividad |
|---|---|
| 16 | **Nuvem de desejos:** cada alumno envía hasta 3 palabras en portugués; la nube crece. Después, «Formar frases»: los alumnos escriben frases con las palabras de la nube. |
| 17 | **Verdadeiro ou falso:** 20 datos sobre Brasil, con votos, explicación y ranking final. |

## Cómo funciona

- Al abrir la presentación se crea una sala con un código de 5 letras. El QR de los slides 16 y 17 lleva a `aluno.html?s=CÓDIGO`.
- La conexión es directa entre el celular y el navegador del profesor (WebRTC con PeerJS). No hay servidor ni base de datos: las palabras y respuestas quedan solo en el navegador del profesor (localStorage).
- Si la presentación se abre desde un archivo local, el QR apunta igual a la página publicada en GitHub Pages.
- Si un celular no logra conectarse, el profesor puede escribir palabras o frases en «Añadir desde aquí…».

## Teclas

← → cambiar de slide · **F** pantalla completa · **N** notas del presentador
