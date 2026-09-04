# WomenCiso-MenCiso
Ecosistema Multicapa de Ciberseguridad Logística Zero-Trust
Ecosistema Multicapa Zero-Trust Logístico y Anti-Spoofing
Unidad de ciberseguridad industrial y program management liderada por la Ing. Scarlett Alejandra Cisneros Aymerich.

Resumen del Proyecto 
Las cadenas de suministro globales y locales enfrentan pérdidas multimillonarias anuales debido al robo de carga, coacción de operadores y ciberataques avanzados como el GPS Spoofing. Las soluciones de rastreo tradicionales son vulnerables porque confían ciegamente en señales satelitales expuestas.

Nuestro proyecto presenta el primer Ecosistema Multicapa Zero-Trust Logístico, una arquitectura de defensa en profundidad diseñada para blindar desde el transporte urbano hasta la logística multimodal internacional. En lugar de competir con gigantes tecnológicos o de movilidad, operamos bajo un modelo SDK-as-a-Service, integrando ciberseguridad militar y computación confidencial directamente sobre plataformas aliadas (Google Maps, Uber, Didi, sistemas ERP).

Datos Duros e Indicadores Clave
Impacto Económico: Diseñado para mitigar pérdidas superiores a los 7,000 MDP anuales por robo y sabotaje en el autotransporte de carga.

Modelo Financiero y Viabilidad:

CAPEX Inicial: 2.3 MDP.

OPEX Anual: 1.38 MDP.

ROI Proyectado: 42.6% en el primer año de operación basado en un piloto validado de 500 unidades.

Escala del Mercado: Dirigido a un parque vehicular nacional que supera las 436,000 unidades registradas (SICT).

Arquitectura Técnica y Requerimientos de Seguridad
1. Modelo de Amenazas y Capas Logísticas
El sistema evalúa riesgos bajo la metodología STRIDE y protege cuatro capas críticas:

Capa 1 (Urbana): Prevención de coacción y pánico silencioso mediante biometría de voz/rostro en entornos seguros y red P2P de hashes.

Capa 2 (Terrestre / Retail): Control de rutas con geocercas validadas por API y tokens dinámicos de peaje de un solo uso.

Capa 3 (Industrial / Hazmat): Neutralización de GPS Spoofing avanzado mediante fusión estricta de sensores en el borde (Edge AI: GNSS + IMU).

Capa 4 (Multimodal / Puertos): Aseguramiento de contenedores internacionales con sellos inteligentes inmutables basados en bloques (ledger).

2. Infraestructura Cloud y Computación Confidencial (Google Cloud Platform)
Kubernetes Engine (GKE): Orquestación escalable de microservicios modulares para las cuatro capas logísticas.

Confidential VMs / Confidential Space: Entornos de ejecución aislados por hardware (AMD SEV-SNP) que garantizan que los datos biométricos y sensibles permanezcan cifrados en memoria, inaccesibles incluso a nivel de hipervisor.

Infraestructura como Código (IaC): Despliegue automatizado y reproducible mediante Terraform.

3. Ciberseguridad e Identidad (IAM)
Certificados X.509: Autenticación unívoca e inquebrantable para cada nodo de hardware y microservicio.

TLS 1.3: Cifrado robusto de extremo a extremo para todas las transmisiones de telemetría y datos.

Pipeline DevSecOps y Pruebas Automatizadas
La seguridad se incrusta desde la fase de diseño (Security by Design) mediante un ciclo de vida automatizado:

SAST (SonarQube): Inspección estática del código fuente del SDK y microservicios para detectar fallas de inyección y malas prácticas.

SCA (Snyk): Auditoría continua de bibliotecas de terceros y dependencias para prevenir vulnerabilidades conocidas (CVEs).

DAST (OWASP ZAP): Pruebas dinámicas en tiempo de ejecución sobre las APIs y pasarelas de comunicación en GKE.

Simulación SDR (Radio Definida por Software): Pruebas físicas de laboratorio que emiten señales de interferencia y ataques de posicionamiento para validar el algoritmo Edge AI.

Cumplimiento Normativo
NOM-087-SCT-2-2017: Automatización del control de tiempos de conducción y prevención de fatiga en operadores.

LFPDPPP: Cumplimiento estricto en el manejo anonimizado y cifrado de datos biométricos y de geolocalización.
