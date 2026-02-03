# YanaRuta - Plan Completo de Diseño

## Estado Actual del Proyecto

### Componentes Reutilizables (39 componentes)

| Categoria | Componentes |
|-----------|-------------|
| **Botones** | Button/Primary, Button/Secondary, Button/Danger |
| **Inputs** | Input/Default |
| **Cards** | Card/Default, Contact/Card, Route/Option, Zone/Card, Stat/Card |
| **Badges** | Badge/Safe, Badge/Danger, Badge/Moderate |
| **Tab Bar** | TabBar/Item, TabBar/ItemActive, TabBar/Container |
| **SOS** | SOS/Button |
| **Toggles/Controls** | Toggle/Default, Toggle/Active, Checkbox/Default, Checkbox/Checked, Radio/Default, Radio/Selected, Slider/Default |
| **Progress** | Progress/Bar, Progress/Circle, Timer/Countdown, Recording/Indicator |
| **Lists** | List/Item, List/ItemWithIcon, List/ItemWithToggle, Notification/Item |
| **Avatars** | Avatar/Default, Avatar/Large, Avatar/WithBadge |
| **Gamification** | Achievement/Badge, Score/Display |
| **Map** | Map/Legend, Zone/Indicator |
| **Alerts** | Alert/Warning |

---

### Pantallas Existentes (33 pantallas)

| # | ID | Nombre | X | Estado |
|---|-----|--------|---|--------|
| 01 | VdzOH | Splash | 864 | Completada |
| 02 | PE3Ee | Onboarding | 1307 | Completada |
| 03 | gZkgs | Login | 1750 | Completada |
| 04 | R8QSK | Home Map | 2193 | Completada |
| 05 | E0pvG | Route Search | 2636 | Completada |
| 06 | Z5bjE | Active Navigation | 3079 | Completada |
| 07 | 87Tjv | Discrete Mode SOS | 3522 | Completada |
| 08 | K9iOS | Report Incident | 3965 | Completada |
| 09 | cS8o7 | Emergency Contacts | 4408 | Completada |
| 10 | x443F | Profile Settings | 4851 | Completada |
| 11 | i7fXa | History Stats | 5294 | Completada |
| 12 | ylPy5 | Register | 5737 | Completada |
| 13 | pKKa3 | Phone Verification | 6180 | Completada |
| 14 | fLjty | Terms Privacy | 6623 | Completada |
| 15 | CEw5A | Add Contact | 11939 | Completada |
| 17 | dmjOn | Route Comparison | 8838 | Completada |
| 19 | r8XYr | Report Success | 12382 | Completada |
| 21 | weVJ8 | SOS Configuration | 7066 | Completada |
| 22 | JDpyF | SOS Countdown | 7509 | Completada |
| 23 | JV64c | SOS Sent Confirmation | 7952 | Completada |
| 25 | zdfBq | Safe Arrival | 8395 | Completada |
| 31 | uCG0o | Notifications Center | 9281 | Completada |
| 32 | eDcxC | Alert Settings | 9724 | Completada |
| 33 | tCmnF | Empty Contacts | 12825 | Completada |
| 34 | AKafJ | Empty History | 13268 | Completada |
| 35 | i0ihN | No Connection | 13711 | Completada |
| 36 | 2qrL2 | Location Error | 14154 | Completada |
| 37 | hiHGO | Confirm Delete | 14597 | Completada |
| 40 | 45g5q | Emergency Call | 15040 | Completada |
| 42 | t5qiW | Feature Tour | 10167 | Completada |
| 43 | P1lmW | SOS Tutorial | 10610 | Completada |
| 44 | jgMQb | SOS Tutorial Step 2 | 11053 | Completada |
| 45 | 5Pbix | SOS Tutorial Step 3 | 11496 | Completada |
| 47 | mo8HU | Password Recovery | 15483 | Completada |

---

## Phase 2 - Pantallas Propuestas

### Grupo A: Flujo de Onboarding/Tutorial (3 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 44 | SOS Tutorial Step 2 | Paso 2 del tutorial SOS - "Manten presionado" | Alta |
| 45 | SOS Tutorial Step 3 | Paso 3 del tutorial SOS - "Contactos alertados" | Alta |
| 46 | Permissions Request | Solicitud de permisos (ubicacion, contactos, notificaciones) | Media |

### Grupo B: Flujo de Contactos (3 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 15 | Add Contact | Agregar nuevo contacto de emergencia | Alta |
| 16 | Edit Contact | Editar contacto existente | Media |
| 18 | Contact Detail | Detalle del contacto con acciones | Media |

### Grupo C: Flujo de Reportes (3 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 19 | Report Success | Confirmacion de reporte enviado | Alta |
| 20 | Incident Detail | Detalle de un incidente reportado | Media |
| 24 | Community Reports | Lista de reportes de la comunidad | Media |

### Grupo D: Configuraciones y Ajustes (4 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 26 | Privacy Settings | Configuracion de privacidad | Media |
| 27 | Accessibility Settings | Ajustes de accesibilidad | Media |
| 28 | Language Settings | Cambio de idioma | Baja |
| 29 | About App | Informacion de la app y creditos | Baja |

### Grupo E: Estados Vacios y Errores (4 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 33 | Empty Contacts | Estado vacio - sin contactos | Alta |
| 34 | Empty History | Estado vacio - sin historial | Alta |
| 35 | No Connection | Sin conexion a internet | Alta |
| 36 | Location Error | Error de ubicacion/GPS | Alta |

### Grupo F: Modales y Overlays (4 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 37 | Confirm Delete | Modal de confirmacion para eliminar | Alta |
| 38 | Rate Trip | Modal para calificar viaje | Media |
| 39 | Share Location | Modal para compartir ubicacion | Media |
| 40 | Emergency Call | Modal de llamada de emergencia | Alta |

### Grupo G: Funcionalidades Adicionales (3 pantallas)

| # | Nombre | Descripcion | Prioridad |
|---|--------|-------------|-----------|
| 41 | Saved Places | Lugares guardados/favoritos | Media |
| 47 | Password Recovery | Recuperacion de contrasena | Alta |
| 48 | Change Password | Cambiar contrasena | Media |

---

## Resumen de Phase 2

| Grupo | Cantidad | Prioridad Alta | Descripcion |
|-------|----------|----------------|-------------|
| A - Onboarding | 3 | 2 | Tutorial y permisos |
| B - Contactos | 3 | 1 | Gestion de contactos |
| C - Reportes | 3 | 1 | Flujo de reportes |
| D - Configuraciones | 4 | 0 | Ajustes varios |
| E - Estados Vacios | 4 | 4 | Estados de error |
| F - Modales | 4 | 2 | Dialogos y overlays |
| G - Adicionales | 3 | 1 | Otras funciones |
| **TOTAL** | **24** | **11** | |

---

## Orden de Ejecucion Sugerido

### Sprint 1 - Alta Prioridad (11 pantallas) ✅ COMPLETADO

1. ✅ SOS Tutorial Step 2 (#44) - jgMQb @ x=11053
2. ✅ SOS Tutorial Step 3 (#45) - 5Pbix @ x=11496
3. ✅ Add Contact (#15) - CEw5A @ x=11939
4. ✅ Report Success (#19) - r8XYr @ x=12382
5. ✅ Empty Contacts (#33) - tCmnF @ x=12825
6. ✅ Empty History (#34) - AKafJ @ x=13268
7. ✅ No Connection (#35) - i0ihN @ x=13711
8. ✅ Location Error (#36) - 2qrL2 @ x=14154
9. ✅ Confirm Delete (#37) - hiHGO @ x=14597
10. ✅ Emergency Call (#40) - 45g5q @ x=15040
11. ✅ Password Recovery (#47) - mo8HU @ x=15483

### Sprint 2 - Media Prioridad (11 pantallas)

12. Permissions Request (#46)
13. Edit Contact (#16)
14. Contact Detail (#18)
15. Incident Detail (#20)
16. Community Reports (#24)
17. Privacy Settings (#26)
18. Accessibility Settings (#27)
19. Rate Trip (#38)
20. Share Location (#39)
21. Saved Places (#41)
22. Change Password (#48)

### Sprint 3 - Baja Prioridad (2 pantallas)

23. Language Settings (#28)
24. About App (#29)

---

## Siguiente Posicion X para Nuevas Pantallas

**Ultima pantalla**: 47 - Password Recovery @ x=15483  
**Siguiente posicion**: x = 15926 (15483 + 443)

---

## Componentes Nuevos a Considerar

Para las nuevas pantallas, podriamos necesitar:

- `Modal/Container` - Contenedor base para modales
- `Button/Text` - Boton de solo texto (links)
- `Empty/State` - Componente de estado vacio
- `Permission/Card` - Card para solicitud de permisos
- `Rating/Stars` - Sistema de calificacion
- `Place/Card` - Card para lugares guardados

---

## Notas Tecnicas

### Dimensiones de Pantalla
- **Ancho**: 393px
- **Alto**: 852px
- **Separacion entre pantallas**: 443px (393 + 50 de padding)

### Colores Principales
- `$accent-primary`: #10B981 (verde - seguridad)
- `$accent-danger`: #EF4444 (rojo - peligro/SOS)
- `$accent-warning`: #F59E0B (amarillo - precaucion)
- `$accent-info`: #3B82F6 (azul - informacion)
- `$bg-primary`: #FFFFFF (fondo principal)
- `$text-primary`: #18181B (texto principal)
- `$text-secondary`: #71717A (texto secundario)

### Tipografia
- **Titulos**: Plus Jakarta Sans (700, 800)
- **Cuerpo**: Inter (400, 500, 600)

---

## Referencias de Componentes Clave

| Componente | ID | Uso Principal |
|------------|-----|---------------|
| Button/Primary | Ur39R | Acciones principales |
| Button/Secondary | KSKCV | Acciones secundarias |
| Button/Danger | vLAZe | Acciones de peligro/SOS |
| Toggle/Active | SSI7K | Toggles activos |
| Toggle/Default | UYROZ | Toggles inactivos |
| List/ItemWithToggle | Ee0of | Items de configuracion |
| TabBar/Container | tZWDh | Barra de navegacion inferior |

---

*Documento actualizado: Febrero 2026*
*Sprint 1 completado: 8 pantallas nuevas creadas*
