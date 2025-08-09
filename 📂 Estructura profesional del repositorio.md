/CyberThreat-Intelligence-Repo
│
├── README.md                               # Visión general, propósito y cómo usar el repo
│
├── /docs                                    # Documentación técnica y metodológica
│    ├── 01_Plataformas_Intercambio.md       # ISAC, AIS, MISP (uso y ejemplos)
│    ├── 02_Ciclo_Inteligencia_Difusion.md   # Etapas del ciclo y protocolos de difusión
│    ├── 03_COP_COE.md                       # Common Operational Picture & Environment
│    ├── 04_Panorama_Inteligencia.md         # Análisis operacional y de amenazas
│    ├── 05_Marcos_Referencia.md             # STIX, TAXII, MITRE ATT&CK, NIST 800-61
│    └── 06_Procedimiento_Clasificacion.md   # Clasificación de inteligencia y manejo seguro
│
├── /processes                               # Procedimientos operativos estándar (SOP)
│    ├── SOP_Identificacion.md               # Identificación de amenazas y recolección
│    ├── SOP_Analisis.md                     # Evaluación de impacto y probabilidad
│    ├── SOP_Registro_STIX_TAXII.md          # Formato estructurado y almacenamiento
│    ├── SOP_Difusion.md                     # Boletines, alertas y control de distribución
│    └── SOP_Seguimiento_Entregables.md      # Mitigado / Pendiente / Cierre sin feedback
│
├── /bulletins                               # Boletines e informes de inteligencia
│    ├── TEMPLATE_Boletin_Semanal.md         # Plantilla estándar
│    ├── TEMPLATE_Informe_Incidente.md       # Formato post-mortem
│    ├── Ejemplo_Boletin_Semanal_01.md
│    └── Ejemplo_Informe_Incidente_01.md
│
├── /tools                                   # Herramientas y guías técnicas
│    ├── Guia_MISP.md                        # Instalación, configuración, integración
│    ├── Guia_AIS_ISAC.md                    # Uso de AIS e ISAC para intercambio seguro
│    ├── Scripts_Extraccion_IOCs.md          # Ejemplos en Python (API MISP, VirusTotal)
│    └── Plantillas_STIX_TAXII.json          # Ejemplos de datos estructurados
│
└── /reports                                 # Reportes y visualizaciones
     ├── Dashboard_Panoramas.md              # Uso de Power BI / Kibana / Grafana
     ├── Informe_Tendencias_Anual_2025.md
     └── Analisis_Campañas_Amenazas_Q3_2025.md
