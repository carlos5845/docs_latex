1. INTRODUCCIÓN

Aquí explicas brevemente:

El crecimiento de las amenazas cibernéticas.
La importancia de evaluar la seguridad de los servicios web.
La necesidad de identificar amenazas antes de que puedan generar impacto.
Qué son Cyber Kill Chain y STRIDE.
Por qué se utilizarán ambas técnicas.
El contexto de la UNAP como caso de aplicación.

Puedes terminar indicando qué contiene el documento.

2. PLANTEAMIENTO DEL PROBLEMA
2.1 Descripción del problema

Explicas el problema desde el punto de vista de seguridad.

Por ejemplo:

Las instituciones universitarias gestionan diversos servicios digitales que pueden estar expuestos a diferentes amenazas de seguridad. La identificación y análisis sistemático de estas amenazas permite establecer medidas de prevención, detección y mitigación.

Luego introduces el caso de los servicios autorizados de la UNAP.

2.2 Formulación del problema
Problema general

¿Cómo pueden las técnicas Cyber Kill Chain y STRIDE contribuir al análisis e identificación de amenazas de seguridad en los servicios web institucionales de la Universidad Nacional del Altiplano?

Problemas específicos
¿Qué amenazas pueden identificarse mediante STRIDE?
¿Cómo pueden representarse los escenarios de ataque mediante Cyber Kill Chain?
¿Qué controles de seguridad pueden proponerse a partir de los resultados obtenidos?
3. OBJETIVOS
3.1 Objetivo general

Aplicar las técnicas Cyber Kill Chain y STRIDE para identificar y analizar amenazas de seguridad en los servicios web institucionales autorizados de la Universidad Nacional del Altiplano.

3.2 Objetivos específicos
Identificar los activos y componentes relevantes del alcance autorizado.
Aplicar STRIDE para identificar y clasificar las posibles amenazas.
Analizar los escenarios de ataque mediante las etapas de Cyber Kill Chain.
Relacionar las amenazas identificadas con medidas de prevención, detección y mitigación.
Elaborar recomendaciones de seguridad a partir de los resultados.
4. JUSTIFICACIÓN

Puedes dividirla en:

4.1 Justificación técnica

Explicas por qué es importante identificar amenazas en servicios web.

4.2 Justificación académica

Explicas que el trabajo permite aplicar conocimientos de ciberseguridad en un entorno real.

4.3 Justificación institucional

Explicas que los resultados pueden servir como insumo para mejorar controles de seguridad, dentro del alcance autorizado.

5. MARCO TEÓRICO

Esta será una de las partes más importantes.

5.1 Ciberseguridad
Concepto.
Confidencialidad.
Integridad.
Disponibilidad.
Autenticidad.
No repudio.
5.2 Amenazas, vulnerabilidades y riesgos

Explicar la diferencia:

Amenaza → Vulnerabilidad → Riesgo → Impacto
5.3 Modelado de amenazas

Explicar qué es Threat Modeling y para qué sirve.

5.4 Cyber Kill Chain

Aquí desarrollas la metodología completa.

5.4.1 Concepto
5.4.2 Objetivo
5.4.3 Etapas
Reconocimiento
Armamento
Entrega
Explotación
Instalación
Comando y control
Acciones sobre objetivos
5.4.4 Técnicas de trabajo

Explicas cómo se utiliza cada etapa durante un análisis.

Por ejemplo:

Etapa	Qué analiza el auditor
Reconocimiento	Información que podría ser obtenida sobre el objetivo
Armamento	Recursos/técnicas que podría preparar un atacante
Entrega	Posibles mecanismos de llegada del ataque
Explotación	Vulnerabilidades que podrían ser aprovechadas
Instalación	Persistencia o ejecución de código
C2	Comunicación con infraestructura externa
Acciones sobre objetivos	Impacto o finalidad del ataque
5.5 STRIDE
5.5.1 Concepto
5.5.2 Objetivo
5.5.3 Categorías STRIDE
Categoría	Significado
S	Spoofing
T	Tampering
R	Repudiation
I	Information Disclosure
D	Denial of Service
E	Elevation of Privilege
5.5.4 Técnicas de aplicación

Aquí explicas cómo utilizar STRIDE sobre:

usuarios;
servidores;
aplicaciones;
bases de datos;
APIs;
comunicaciones;
sistemas de autenticación.
5.6 Comparación entre STRIDE y Cyber Kill Chain

Esta sección te recomiendo incluirla porque demuestra que comprendes que no hacen exactamente lo mismo.

Característica	STRIDE	Cyber Kill Chain
Enfoque	Amenazas	Proceso del ataque
Principal pregunta	¿Qué puede salir mal?	¿Cómo avanza el ataque?
Uso principal	Modelado de amenazas	Análisis de ataques
Momento de uso	Principalmente diseño/análisis	Análisis de la cadena de ataque
Resultado	Amenazas clasificadas	Etapas del ataque
6. METODOLOGÍA

Aquí explicas cómo vas a realizar tu trabajo sobre la UNAP.

6.1 Tipo de investigación

Podría ser, según los requisitos de tu curso:

Investigación aplicada.

6.2 Enfoque

Podrías plantearlo como:

Enfoque cualitativo/descriptivo, complementado con evaluación técnica cuando corresponda.

6.3 Área de estudio

Servicios web institucionales autorizados de la Universidad Nacional del Altiplano.

6.4 Alcance

Aquí debes especificar exactamente qué te autorizaron.

Por ejemplo:

Dominio:
unap.edu.pe

Activos:
[los activos autorizados]

Periodo:
[fecha]

Pruebas permitidas:
[según autorización]

No pongas solamente unap.edu.pe si la autorización realmente abarca determinados subdominios, IP, aplicaciones o servicios.

7. DESARROLLO / APLICACIÓN PRÁCTICA

Esta sería la parte central de tu trabajo.

7.1 Reconocimiento del entorno autorizado

Documentas los activos que forman parte del alcance.

Por ejemplo:

Dominio
   │
   ├── Servicio web
   ├── Aplicación
   ├── API
   └── Otros activos autorizados

Sin incluir información sensible que no sea necesaria para el documento.

7.2 Identificación de activos

Puedes crear una tabla:

ID	Activo	Tipo	Función	Alcance
A01	Servicio web	Web	Portal institucional	Autorizado
A02	Aplicación	Web	Servicio institucional	Autorizado
A03	API	API	Comunicación	Autorizado
7.3 Aplicación de STRIDE

Aquí haces el análisis real.

Por ejemplo:

Activo	STRIDE	Amenaza	Impacto potencial	Control
Aplicación web	S	Suplantación de usuario	Acceso no autorizado	MFA, controles de sesión
Aplicación web	T	Modificación no autorizada	Alteración de información	Validación y autorización
Base de datos	I	Exposición de información	Pérdida de confidencialidad	Control de acceso
Servicio web	D	Indisponibilidad	Interrupción del servicio	Protección anti-DoS

La idea es que no solamente enumeres STRIDE, sino que demuestres cómo lo aplicaste.

7.4 Construcción de escenarios de ataque

A partir de las amenazas identificadas mediante STRIDE, puedes construir escenarios hipotéticos o basados en evidencia de auditoría.

Por ejemplo:

Amenaza STRIDE
      ↓
Escenario
      ↓
Posible vector
      ↓
Etapa Cyber Kill Chain
      ↓
Control de seguridad
7.5 Aplicación de Cyber Kill Chain

Aquí tomas uno o varios escenarios y los analizas mediante las siete etapas.

Por ejemplo:

Etapa	Análisis
Reconocimiento	Información públicamente disponible
Armamento	Recursos necesarios para el escenario
Entrega	Vector hipotético/autorizado
Explotación	Vulnerabilidad o condición identificada
Instalación	Ejecución/persistencia, si corresponde
C2	Comunicación, si corresponde
Acciones sobre objetivos	Posible impacto

Importante: si tu auditoría no permite explotación, no necesitas explotar una vulnerabilidad para demostrar la metodología. Puedes documentar el escenario y detenerte en la validación autorizada.

8. RESULTADOS

Aquí presentas lo que encontraste.

Puedes incluir:

8.1 Amenazas identificadas mediante STRIDE
8.2 Escenarios analizados mediante Cyber Kill Chain
8.3 Controles de seguridad existentes
8.4 Brechas identificadas
8.5 Matriz de riesgo

Por ejemplo:

Hallazgo	Probabilidad	Impacto	Nivel
H01	Media	Alto	Alto
H02	Baja	Medio	Medio
H03	Media	Bajo	Medio

La escala exacta debería definirse previamente en tu metodología.

9. PROPUESTA DE MITIGACIÓN

Para cada hallazgo:

Hallazgo	Recomendación	Prioridad	Responsable
H01	Implementar control de autenticación	Alta	Área TI
H02	Mejorar controles de acceso	Media	Área TI
H03	Fortalecer monitoreo	Media	Seguridad
10. CONCLUSIONES

Relaciona cada conclusión con tus objetivos.

Por ejemplo:

Se identificaron las principales categorías de amenazas mediante STRIDE.
Cyber Kill Chain permitió representar la progresión de determinados escenarios.
La combinación de ambas técnicas permitió analizar las amenazas desde perspectivas complementarias.
Se identificaron oportunidades de mejora en los controles de seguridad.
11. RECOMENDACIONES

Aquí propones acciones concretas para mejorar la seguridad.

12. REFERENCIAS BIBLIOGRÁFICAS

Te recomiendo utilizar fuentes oficiales y académicas para el marco teórico, por ejemplo:

documentación de Microsoft para STRIDE;
documentación de Lockheed Martin para Cyber Kill Chain;
NIST;
OWASP;
artículos científicos;
libros de ciberseguridad.

1. INTRODUCCIÓN

2. PLANTEAMIENTO DEL PROBLEMA
   2.1 Descripción del problema
   2.2 Formulación del problema
   2.3 Problemas específicos

3. OBJETIVOS
   3.1 Objetivo general
   3.2 Objetivos específicos

4. JUSTIFICACIÓN
   4.1 Justificación técnica
   4.2 Justificación académica
   4.3 Justificación institucional

5. MARCO TEÓRICO
   5.1 Ciberseguridad
   5.2 Amenazas, vulnerabilidades y riesgos
   5.3 Modelado de amenazas
   5.4 Cyber Kill Chain
       5.4.1 Concepto
       5.4.2 Objetivo
       5.4.3 Las 7 etapas
       5.4.4 Técnica de aplicación
   5.5 STRIDE
       5.5.1 Concepto
       5.5.2 Objetivo
       5.5.3 Las 6 categorías
       5.5.4 Técnica de aplicación
   5.6 Comparación STRIDE vs Cyber Kill Chain

6. METODOLOGÍA
   6.1 Tipo de investigación
   6.2 Enfoque
   6.3 Área de estudio
   6.4 Alcance autorizado
   6.5 Procedimiento de evaluación

7. APLICACIÓN PRÁCTICA
   7.1 Reconocimiento del entorno autorizado
   7.2 Identificación de activos
   7.3 Aplicación de STRIDE
   7.4 Identificación de amenazas
   7.5 Construcción de escenarios
   7.6 Aplicación de Cyber Kill Chain
   7.7 Análisis de controles

8. RESULTADOS
   8.1 Amenazas identificadas
   8.2 Escenarios analizados
   8.3 Hallazgos
   8.4 Matriz de riesgos

9. PROPUESTA DE MITIGACIÓN

10. CONCLUSIONES

11. RECOMENDACIONES

12. REFERENCIAS BIBLIOGRÁFICAS
