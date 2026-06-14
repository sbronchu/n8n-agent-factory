# n8n Agent Factory

Repositorio de agentes AI especializados para n8n. Cada agente tiene su propia personalidad, herramientas y perfil de cliente.

## Estructura

- **agents/**: Perfiles de agentes (19 especializaciones)
- **tools/**: Definiciones de herramientas disponibles
- **models/**: Configuracion de modelos LLM y reglas de routing
- **docs/**: Documentacion y guias

## Uso

1. Selecciona un agente de la carpeta **agents/**
2. Configura el workflow generico en n8n con el **agent_id**
3. El workflow cargara automaticamente la personalidad y herramientas desde GitHub
4. Anade las tools que necesites segun el cliente

## Agentes Disponibles

1. **productivity** - Gestion de tareas y calendarios
2. **customer-support** - Soporte y tickets
3. **sales** - Ventas y prospecting
4. **marketing** - Marketing y contenido
5. **legal** - Legal y contratos
6. **finance** - Finanzas y contabilidad
7. **data** - Analisis de datos
8. **product-management** - Gestion de producto
9. **engineering** - Desarrollo de software
10. **human-resources** - Recursos humanos
11. **operations** - Operaciones
12. **design** - Diseno y brand
13. **small-business** - Pequenos negocios
14. **bio-research** - Investigacion biologica
15. **enterprise-search** - Busqueda enterprise
16. **cowork-plugin-management** - Gestion de plugins
17. **partner-built** - Plugins de partners
18. **pdf-viewer** - Visualizacion PDF
19. **automation-engineer** - Automatizacion y scripting

## Configuracion

Ver **docs/setup-guide.md** para instrucciones detalladas.
