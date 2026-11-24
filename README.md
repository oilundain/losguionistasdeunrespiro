# Los guionistas de unrespiro

Un skill de Claude con cinco guionistas especializados en los vídeos cortos de **unrespiro** (Reels y TikTok). Su objetivo: que cada vídeo cuente una historia que enganche **y** lleve de forma natural a instalar la app.

Puede trabajar de dos formas:

- **Generar:** le das un tema (una historia, un personaje, un problema, un sector como deporte, tecnología o negocios) y propone ángulos que lo conectan con unrespiro, elige el mejor y escribe un esqueleto de guion.
- **Revisar:** le das una idea, un guion o la transcripción de un vídeo ya grabado, y lo analiza, lo puntúa y lo mejora.

## Los cinco guionistas

1. **El Narrador:** gancho, historia y tensión. ¿Engancha a quien no conoce la app?
2. **El Puente:** el salto de la historia al problema y de ahí a unrespiro. ¿Es natural o forzado?
3. **El Director Visual:** fuerza visual con imagen de archivo (metáfora central, planos realizables) y app en pantalla resolviendo el problema.
4. **El Closer:** el cierre. Un único CTA, pegado a un beneficio, con la acción visible.
5. **El Público Objetivo:** alguien con el problema que se pregunta si el vídeo le convence y si le ve utilidad.

Se tensan a propósito: el arte frente a la venta (Narrador contra Closer), la historia frente a lo que el archivo permite mostrar (Narrador contra Director Visual) y la lógica de la conexión frente a si la persona se la cree (Puente contra Público Objetivo).

## Qué entrega

**Al revisar:** un estado (listo para grabar, grabar con ajustes o replantear), un termómetro de cinco puntos (historia, puente, visual, cierre y convicción), los 3 cambios de mayor impacto, 3 ganchos reescritos, 2 cierres, una lista de planos con términos de búsqueda para bancos de imagen y una única acción inmediata.

**Al generar:** un ranking de ángulos, el recomendado con su puente hacia una función real de la app y su metáfora visual, un esqueleto de guion y una lista de cosas por comprobar antes de grabar.

## Cuatro plantillas a probar

1. **Historia o personaje → moraleja → unrespiro.**
2. **Problema → demo → descarga.**
3. **UGC personal → solución.**
4. **UGC con palabra clave** ("comenta X y te paso el enlace").

> Son estructuras para probar, no copys aprobados ni resultados garantizados. El skill las trata como hipótesis y da prioridad a las métricas reales si las aportas.

## Cómo instalarlo (sin terminal)

**Opción 1: que Claude lo instale por ti.** Abre una conversación nueva en Claude y pega esto:

> Instala este skill de Claude por mí. El archivo SKILL.md está en este repositorio de GitHub: https://github.com/oilundain/losguionistasdeunrespiro
> Déjalo listo para usarlo y guíame en lo que necesites.

Si Claude no consigue leer el repositorio (a veces GitHub limita las peticiones), prueba con el enlace directo al archivo:

> https://raw.githubusercontent.com/oilundain/losguionistasdeunrespiro/main/SKILL.md

**Opción 2: descarga el archivo.**
1. Abre [SKILL.md](SKILL.md) y descárgalo.
2. Adjúntalo a una conversación con Claude y pídele que lo instale, o bien, en Ajustes → Capacidades → Skills, súbelo como `.zip` de una carpeta llamada `los-guionistas-de-unrespiro` que contenga el `SKILL.md`.

## Cómo usarlo

Dile a Claude cosas como:

- "Guionistas de unrespiro: idea para un reel sobre [tema]"
- "Busca historias para unrespiro a partir de [tema]"
- "Revisa este guion de unrespiro: [guion]"
- "Llama a los guionistas: mejora el CTA de este vídeo"

Para mejores resultados, indica el tema o el guion, la fase (idea, guion o vídeo ya grabado), el objetivo del vídeo (instalar, conversación o alcance) y, si las tienes, la transcripción y las métricas.

## Cosas a tener en cuenta

- **No inventa funciones de la app.** Solo usa las que aparecen en la sección de contexto de `SKILL.md`. Si un guion afirma algo más, lo marca como "verificar con el equipo". Si la app cambia, actualiza esa sección.
- **En una conversación normal de claude.ai** no hay sub-agentes, así que Claude simula a los cinco guionistas uno por uno, con algo menos de independencia. En Claude Code y Cowork los lanza en paralelo.
- **Solo para vídeos de unrespiro.** Para otros contenidos de formato corto existe una versión general: [sala de guionistas](https://github.com/oilundain/saladeguionistas).

## Cómo mejorarlo

El skill mejora cuanto más real sea lo que sabe. Estas son las ediciones que más valen:

- Actualizar la descripción de la app en `SKILL.md` cuando cambien las funciones.
- Añadir las plantillas o principios que se confirmen con resultados reales, y quitar los que no funcionen.
- Añadir ejemplos de ganchos y cierres que hayan funcionado.

Para editar, abre `SKILL.md` en GitHub, pulsa el icono del lápiz, cambia lo que necesites y confirma con **Commit changes**.

## Créditos

La mecánica de reunión (opiniones independientes, lectura cruzada anónima y síntesis final) parte de la metodología [LLM Council](https://github.com/karpathy/llm-council) de Andrej Karpathy, a través del skill [LLM Council](https://github.com/aiwithremy/claude-skills-llm-council) de Ole Lehmann (compartido por aiwithremy), que se adaptó en la [sala de guionistas](https://github.com/oilundain/saladeguionistas). Este skill está pensado específicamente para los vídeos de unrespiro.
