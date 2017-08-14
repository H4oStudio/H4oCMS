H4O CMS
========


Situacion de la solucion
  - Requiere nuevos automatismos de parte del equipo (tanto en diseño y desarrollo)
  - Falta de automatizacion comparado con DM
  - API mas solidas que las proporcionadas por DM
  - No impone nada en front (css/js), mas facil de integrar libs modernas, o cambiar el flujo de trabajo
  - Accepta mas facilmente escalar en numero de servidores/ tecnicas de cache modernas

Tareas para version H4o:

## Branding
 - Nombre
 - Look and feel login/admin (logo+fondos?)

## Localizacion
 - traduccion al español (admin)

## Frontend
  - inclusion de script y css (webpack??)
  - compass/susy/grunt (sulu necesita grunt para sus modulos internos, tener dos sistemas de built es poco productivo, otra opcion es migrar sulu a gulp o ...)
  - como hacer bundles de scripts (sliders, etc...)?
  - templates base ???

## Backend
 - Pruebas con oracle y sql-server
 - Suplentar SuluAdmin plugin
 - GeneratorBundle para automatizar creacion de bundles de datos (impacta API)
 - probar los bundles nativos para blog y e-commerce

## API
 - Modalidad de login por api-key
 - Implementar CORS (symfony parece tener un bundle que lo automatiza)
 - Probar ember-hal9000 (serializer para el formato json nativo de sulu)
 - generar controller para API front/back (impacta back-end)

## Capacitación
  - pensar en componentes independientes
  - practicar symfony 3.x (bundles, controller, DI, services, entities, authentication/authorization)
  - practicar webpack ???
  - practicar ember

## Flujo de trabajo
  - Definir un flujo de trabajo mas adaptado:
  	- Diseño
	  - PSD (Movil first)
  	  - Style tiles
          - Estructura de contenido (tipo de paginas/contextos/modelos/bloques)
          - Definir necesidad de modulos "Entity"      
  	- Integracion html statica ?
  	- Traspaso de html/css/js a CMS




