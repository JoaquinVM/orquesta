# 🎼 Orquesta

**Dirige una startup de agentes de IA.** Tienes 10 sprints para llegar a la Serie A: reparte el trabajo, contrata, forma a tu equipo y entrega funcionalidades sin quedarte sin caja.

**▶ Juega aquí: https://joaquinvm.github.io/orquesta/**

*[English below](#english)*

## Cómo se juega

1. **Sprint (75 s, en tiempo real):** toca una tarea y luego un agente. Cada tarea paga 💰.
2. **Planificación (sin reloj):** entre sprints revisas ingresos y nómina, contratas candidatos, formas agentes y compras mejoras.
3. **Los agentes aprenden haciendo:** cada tarea suma experiencia en su área hasta llegar a Jr, Sr y Experto. Dar trabajo a un agente sin nivel es más lento y arriesgado, pero así es como se forma.
4. **Funcionalidades:** desde el sprint 3 llegan cadenas Diseño → Código → QA. Entregarlas completas da un bonus y reputación ⭐.
5. Pierdes si te quedas **sin caja para la nómina** o **sin reputación**.

Cada sprint trae algo nuevo: contratar, la tienda, QA, candidatos Sr, el área de Datos… La complejidad crece a medida que la dominas.

### Modos y progreso

- **📅 Reto diario:** mismas tareas y candidatos para todo el mundo ese día. Mantén tu racha de días.
- **🏅 14 logros** y **7 rangos**, de Becario a Director de orquesta, según la valoración final.
- **Resultado para compartir** al estilo Wordle: 🟩 sprint limpio · 🟨 algún fallo · 🟥 sprint malo · 💥 donde caíste.

## Por qué existe

Trabajo a diario con un sistema de agentes de IA que reparten y revisan trabajo. Este juego es la versión jugable de ese problema: **orquestar bien importa más que tener muchos agentes**.

## Detalles técnicos

- Un solo `index.html`: HTML, CSS y JavaScript sin dependencias ni build.
- Todos los números de ritmo y economía están en el objeto `CFG`, al principio del script.
- El equilibrio se ajustó simulando partidas con distintas estrategias (pasiva, sin contratar, óptima).
- Funciona en móvil y escritorio, en español e inglés. El progreso se guarda en tu navegador.

---

## English

**Run a startup of AI agents.** You have 10 sprints to reach Series A: assign work, hire, train your team and ship features without running out of cash.

**▶ Play: https://joaquinvm.github.io/orquesta/**

- **Sprints (75 s, real time):** tap a task, then an agent. Every task pays 💰.
- **Planning (no clock):** hire candidates, train agents, buy upgrades, watch your payroll.
- **Agents learn by doing:** XP turns them into Jr, Sr and Expert specialists.
- **Features:** from sprint 3, Design → Code → QA chains pay a bonus and reputation.
- New mechanics unlock sprint by sprint. Daily challenge, 14 achievements, 7 ranks and a Wordle-style share grid.

Single `index.html`, vanilla HTML/CSS/JS, no dependencies. All tuning lives in the `CFG` object.

## Licencia / License

[MIT](LICENSE)
