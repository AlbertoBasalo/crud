# crud
Crud básico con angular

### generar aplicación enrutable con CLI

### Sustituir AppComponent original por un menú y un outlet dinámico

  - Usar lazy loading
  
  - Módulo home
  
  - Módulo items
  
### Ruta base '' página de bienvenida HomeComponent

### Ruta '/items' página de alta y listado ItemsComponent

- En un componente controlador debe aparecer un formulario y un listado

- Estos últimos deben actuar como presentadores

#### Formulario NewItemComponent

  - Tema libre, pero al menos...
  - un campo descriptivo
  - un campo numérico
  - un checkbox
  - un botón de guardar
  - usar un campo extra llamado \_id que almacene un timestamp único
  
#### Listado ListItemsComponent
 
  - Ver los datos anteriores
  - Botón de borrado
  - Enlace al elemento por su \_id
  
### Ruta '/items/:itemId' página de un elemento ItemComponent

  - Un componente presentador simple
  
  - Ver el JSON del elemento correspondiente con \_id coincidente con pará,metro itemId
  
### Usar un servicio inyectable llamado ItemsDataService

   - reclamado por el ItemsComponent y el ItemComponent
  
  - Almacenar en un array
  
  - Recuperar el Array
  
  - Buscar por \_id
  
