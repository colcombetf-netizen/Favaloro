# Favaloro | Un diálogo con el cirujano del corazón

Conversá por voz con una recreación digital del doctor René Favaloro, pionero del bypass coronario: su vida, su obra y cómo cuidar el corazón. Recreación hecha con inteligencia artificial con fines educativos; no reemplaza una consulta médica.

## Publicarlo en GitHub Pages
1. Creá un repositorio público y subí estos archivos (**Add file → Upload files → Commit changes**).
2. En **Settings → Pages**, elegí **Deploy from a branch**, rama **main**, carpeta **/ (root)**, y tocá **Save**.
3. Abrí `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`, tocá **Hablar** y permití el micrófono.

## El agente
- ID: `agent_9101m4hcs5m1f3p9df75kjm8t35h`. Para usar otro sin tocar el código: `index.html?agente=TU_ID`.
- Tiene que ser **público**: en ElevenLabs, pestaña *Security*, autenticación desactivada. Si usás lista de dominios, agregá `TU_USUARIO.github.io`.

## Qué hace la figura
- Mueve la boca según cada letra que dice el agente y según el sonido real.
- Se puede girar 360°; mira a quien la rodea; gesticula al hablar.
- «Escucharlo sin conectarse» usa la voz del dispositivo, sin gastar créditos.

Necesita internet: la voz viaja por ElevenLabs y la figura usa Three.js desde jsDelivr. Cada conversación consume créditos de ElevenLabs.

## Agregar la voz rioplatense (pendiente)
El agente quedó con la voz por defecto de ElevenLabs. Para una voz argentina: **Voices → Voice Library**, buscá «Chelo - Young, Publicity and Characters» (o «Uriel - Raspy and Husky texture»), tocá **Add to my voices** y elegila en la pestaña **Voice** del agente. Dejá velocidad 0,95 y estabilidad 0,6.

## Revisar antes de publicar
Probá la conversación en https://elevenlabs.io/app/talk-to?agent_id=agent_9101m4hcs5m1f3p9df75kjm8t35h y verificá en la base de conocimiento los datos biográficos menores (por ejemplo, la mención al tío médico y los traslados a caballo o en sulky en Jacinto Aráoz).
