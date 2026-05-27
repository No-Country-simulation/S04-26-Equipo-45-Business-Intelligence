# S04-26-Equipo-45-Business-Intelligence
Automatización de reportes ejecutivos de personal mediante la conexión de fuentes de datos internas de GlobalForce con dashboards interactivos, reduciendo el tiempo de preparación de tres días a menos de una hora.

# GlobalForce Analytics – Strategic Workforce Insights Pipeline 🚀

### 📊 De 3 días de procesamiento manual en Excel a menos de 1 hora con automatización de datos.

---

## 📝 Descripción del Proyecto
GlobalForce Analytics es una solución integral de Business Intelligence y automatización de datos diseñada para resolver el cuello de botella operativo en la generación de reportes mensuales de fuerza laboral (*workforce*). 

Anteriormente, la consolidación de datos fragmentados de nómina (*headcount*), horas y costos se realizaba manualmente en Microsoft Excel, consumiendo **tres (3) días laborables completos por cliente**. Esta arquitectura implementa un *Modern Data Stack* contenedorizado que automatiza el proceso de Extracción, Transformación y Carga (ETL), garantizando soberanía de datos, escalabilidad multi-cliente y reportes ejecutivos dinámicos en menos de una hora.

---

## 🛠️ Stack Tecnológico e Infraestructura

El proyecto está diseñado bajo una arquitectura desacoplada y escalable, utilizando herramientas líderes en ingeniería de datos y BI:

*   **Orquestación y ETL:** `n8n`https://img.shields.io/badge/n8n-FF6C37?style=for-the-badge&logo=n8n&logoColor=white) – Automatización del flujo de datos mensual y limpieza de registros mediante lógica personalizada en nodos y JavaScript.
*   **Data Warehouse:** `Supabase (PostgreSQL)` – Base de datos relacional robusta en la nube para el almacenamiento seguro e íntegro del modelo dimensional.
*   **Visualización y Analítica:** `Power BI Desktop` – Modelado de datos (Esquema en Estrella) y cálculo dinámico de KPIs de Recursos Humanos mediante lenguaje DAX.
*   **Despliegue y DevOps:** `Docker & Docker Compose` – Contenedorización de todo el ecosistema analítico (n8n, variables de entorno y conectores) desplegado de forma aislada en un **Servidor Privado Virtual (VPS)**.

## 📋 Documentación Completa del Proyecto

Para facilitar la lectura según el perfil del stakeholder, la documentación se encuentra organizada en los siguientes módulos interactivos:
* 📄 **Informe Ejecutivo y Propuesta Conceptual**: https://cake-soup-303.notion.site/INFORME-EJECUTIVO-Y-PROPUESTA-CONCEPTUAL-36c811cc04aa80ac99bcc7c281e4494a - Diseñado para Directores de Operaciones y Client Managers. Incluye el análisis de mercado y prototipos visuales
* ⚙️ **Arquitectura de Datos y Modelo Dimensional**: https://cake-soup-303.notion.site/DOCUMENTACI-N-T-CNICA-Y-ARQUITECTURA-DEL-MODELO-DE-DATOS-36c811cc04aa8032b457c911747eb3a3 - Detalle técnico del esquema en estrella, diccionario de datos en Supabase y fórmulas DAX.
* 📖 **Manual de Operación del Sistema***: https://cake-soup-303.notion.site/MANUAL-DE-USUARIO-Y-OPERACI-N-DEL-SISTEMA-36c811cc04aa80c0a15ee11176ab58cf - Guía paso a paso para el analista encargado de ejecutar el pipeline mensual en n8n.
