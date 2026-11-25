# Justificación del uso de Inteligencia Artificial

**Equipo BodegaNube** · Java: Diseño y Construcción de Soluciones nativas en Nube (JVY0101) · Evaluación Parcial 3

Documento grupal pedido por el docente: cada integrante declara qué herramientas de IA usó, en qué etapas del
proyecto y con qué prompts, y explica qué hizo y verificó por su cuenta. Referencia: orientaciones de uso de IA
de Duoc UC en <https://bibliotecas.duoc.cl/ia>.

> **Cómo completar tu sección**: reemplaza todo lo que está entre `[corchetes]`. Copia tus prompts tal como los
> escribiste (puedes acortar archivos pegados, indicando qué eran). Sé concreto en "qué hice yo": qué revisaste,
> qué ejecutaste, qué corregiste y qué decidiste.

---

## Lucas (oLUCX)

### Herramientas
| Herramienta | Versión o modelo | Cómo la usé |
|---|---|---|
| Claude Code (Anthropic), extensión de VS Code | Claude Opus 5.5 | Asistente de programación con acceso a la carpeta del proyecto: leía el código y las instrucciones, proponía y escribía archivos y ejecutaba pruebas en mi PC |

### Etapas en que la usé
| Etapa | Para qué usé la IA | Qué hice y verifiqué yo |
|---|---|---|
| EP1 – Arquitectura | [ej.: redactar y ordenar el informe de arquitectura a partir del caso] | [ej.: definí con el equipo los 4 microservicios; corregí el diagrama] |
| EP2 – Microservicios | Escribir el código de los 5 microservicios separado en pasos para que cada integrante lo subiera en su rama | [ej.: revisé cada paso, lo ejecuté con Postman, resolví conflictos de ramas] |
| EP3 – Análisis de la pauta | Comparar las instrucciones y la rúbrica con lo que ya tenía el proyecto y proponer un plan y un reparto | Confirmé el plazo, el reparto y las correcciones del docente (`/api/v1`, organización en GitHub) |
| EP3 – Código e infraestructura | Dockerfiles, docker-compose, stack de Swarm y scripts, pipelines de GitHub Actions, plantillas CloudFormation, funciones Lambda, filtro JWT del gateway, pruebas E2E | [ej.: ejecuté los pipelines, revisé que el clúster quedara arriba, probé con Postman] |
| EP3 – Guía del equipo | Generar la guía en PDF con los pasos de cada integrante | [ej.: la revisé y la compartí con el equipo] |

### Prompts empleados (EP3)
1. Con el PDF de instrucciones de la EP3 y tres capturas de los anuncios del AVA adjuntos:
   > Tengo esas instrucciones y esas screenshots para la entrega 3, que debemos de hacer segun lo que ya tenemos
   > en este proyecto?
2. > También me pidio el profe que cambiemos eso de /api/v1 en la semántica de los endpoints... y me parece que
   > tambien tenemos que cambiar todo a una organizacion en github y de ahi mismo invitar al profesor si vamos a
   > ocupar aws academy learner y aun no me he enrelado en la invitación que nos llegó pero lo hacemos rapidito,
   > me sirve el reparto pero necesito un pdf local para poder compartirlo a mis compañeros no un artifact
   > porfavor con lo mismo de la vez pasada, que hace cada uno que codigo agrega donde con ayuda de links y un
   > inpunt en donde tengan guardado su proyecto para que se entienda mejor, el mismo estilo utilizado
   > anteriormente para hacer el trabajo
3. [agrega los prompts siguientes]

### Prompts empleados (EP1 y EP2)
[pega aquí los prompts de esas sesiones]

### Reflexión
[qué aportó la IA, qué errores tuvo que corrigieron ustedes, qué aprendiste al revisar su trabajo. Ejemplo
real del equipo: la prueba de carga detectó que dos reservas simultáneas del mismo producto se pisaban
(sobreventa) y se corrigió con un bloqueo de fila]

---

## Nicolás Bralla (nbralla)

### Herramientas
| Herramienta | Versión o modelo | Cómo la usé |
|---|---|---|
| [ej.: Claude Code, ChatGPT, GitHub Copilot] | [modelo] | [cómo] |

### Etapas en que la usé
| Etapa | Para qué usé la IA | Qué hice y verifiqué yo |
|---|---|---|
| [EP2 – ms-ordenes] | [ ] | [ ] |
| [EP3 – reserva de stock, Lambdas, pruebas E2E] | [ ] | [ ] |

### Prompts empleados
1. [prompt exacto]

### Reflexión
[ ]

---

## BOCAZ96

### Herramientas
| Herramienta | Versión o modelo | Cómo la usé |
|---|---|---|
| [ej.: Claude Code, ChatGPT, GitHub Copilot] | [modelo] | [cómo] |

### Etapas en que la usé
| Etapa | Para qué usé la IA | Qué hice y verifiqué yo |
|---|---|---|
| [EP2 – ms-inventario y ms-picking-despacho] | [ ] | [ ] |
| [EP3 – cola SQS, EC2 con CloudFormation, bloqueo de stock] | [ ] | [ ] |

### Prompts empleados
1. [prompt exacto]

### Reflexión
[ ]
