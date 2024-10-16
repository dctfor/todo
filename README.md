# Lista de Tareas (Todo List)

Una aplicación web simple pero potente para gestionar tareas diarias, desarrollada con HTML, CSS y JavaScript puro. La aplicación utiliza el almacenamiento local del navegador (localStorage) para persistir los datos.

## Características

- ✨ Interfaz de usuario intuitiva y responsive
- 📅 Soporte para fechas límite en las tareas
- 💾 Almacenamiento local persistente
- 🔄 Importación y exportación de tareas en formato JSON
- ⏰ Reloj en tiempo real con fecha completa
- 🎨 Diseño moderno con Bootstrap y FontAwesome
- 📱 Totalmente responsive para dispositivos móviles

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.3
- FontAwesome 6.0
- LocalStorage API

## Funcionalidades Principales

### Gestión de Tareas
- Crear nuevas tareas con texto descriptivo
- Establecer fechas límite opcionales
- Marcar tareas como completadas
- Editar tareas existentes
- Eliminar tareas
- Visualización del estado de completado

### Características Adicionales
- Mensajes aleatorios en el placeholder del input
- Animaciones suaves al agregar/eliminar tareas
- Diseño con franjas alternadas para mejor legibilidad
- Efectos hover en las tareas
- Cabecera fija con reloj en tiempo real

### Importación/Exportación
- Exportar todas las tareas a un archivo JSON
- Importar tareas desde un archivo JSON
- Fusión inteligente de tareas sin duplicados

## Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/dctfor/todo.git
```

2. Abre el archivo `todolist.html` en tu navegador web preferido

No se requieren dependencias adicionales ni proceso de construcción.

## Uso

1. **Agregar una tarea:**
   - Escribe el texto de la tarea en el campo de entrada
   - Opcionalmente, establece una fecha límite
   - Haz clic en el botón "+" o presiona Enter

2. **Gestionar tareas:**
   - Marca como completada: ✓ (Es ToogleBtn)
   - Edita: ✎
   - Elimina: 🗑️

3. **Exportar tareas:**
   - Haz clic en "Exportar Tareas" en el pie de página
   - Se descargará un archivo JSON con todas tus tareas

4. **Importar tareas:**
   - Selecciona un archivo JSON previamente exportado
   - Las tareas se fusionarán con las existentes

## Estructura del Proyecto

```
/
└── todolist.html          # Archivo principal HTML
```

## Características del Código

- UUID único para cada tarea
- Gestión de fechas en UTC
- Formateo de fechas localizado (es-ES)
- Manejo de estados y actualización en tiempo real
- Validación de datos de entrada
- Gestión de errores en importación/exportación

## Contribución

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Haz fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/AmazingFeature`)
3. Realiza tus cambios
4. Commit a tus cambios (`git commit -m 'Add some AmazingFeature'`)
5. Push a la rama (`git push origin feature/AmazingFeature`)
6. Abre un Pull Request
