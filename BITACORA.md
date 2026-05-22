# Bitácora de Aprendizaje y Desarrollo - Reparadora de Calzados

## Sesión 1: Configuración Inicial y Fundamentos
**Fecha:** [Fecha de inicio]
**Temas:** HTML semántico, CSS (selectores, box model, flexbox, responsivo), JS básico (funciones, onclick, alert)
**Logros:** 
- Estructura base del e-commerce definida
- Primeros componentes visuales (header, productos, carrito)
- Lógica básica de agregar al carrito con arreglos en memoria

## Sesión 2: DOM y Eventos
**Fecha:** [Fecha de sesión 2]
**Temas:** DOM manipulation, event listeners, localStorage
**Logros:**
- Interacción dinámica con productos
- Guardado del carrito en localStorage
- Eventos de click, change, submit funcionando

## Sesión 3: Migración a Base de Datos Real (Supabase)
**Fecha:** 22 de Mayo, 2026
**Temas:** Supabase, PostgreSQL, diseño de tablas, conexión API
**Logros:**
- ✅ Cuenta en Supabase creada
- ✅ Proyecto "Reparadora" configurado
- ✅ Credenciales obtenidas (URL y API Key)
- ✅ Decisión de arquitectura: PostgreSQL para datos relacionales
- [ ] Tablas creadas (productos, pedidos, detalle_pedido)
- [ ] Conexión desde el código
- [ ] Migración de CRUD de arreglos a SQL

### Plan de Migración (Próxima sesión)
1. Crear tablas en Supabase:
   - `productos` (id, nombre, descripción, precio, stock, imagen_url, categoria)
   - `pedidos` (id, fecha, total, estado)
   - `detalle_pedido` (id, pedido_id, producto_id, cantidad, precio_unitario)
2. Instalar `@supabase/supabase-js`
3. Reemplazar operaciones con arreglos por consultas SQL
4. Implementar script de actualización semanal

---
*Nota: Este archivo se actualiza al final de cada sesión de trabajo.*
