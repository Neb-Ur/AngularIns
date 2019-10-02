Software
---------------------------------------------------------------------------------------------------

1. NodeJS: https://nodejs.org/es/
2. TypeScript: https://www.typescriptlang.org/  npm install -g typescript
3. Angular Cli: https://cli.angular.io/ npm install -g @angular/cli
4. Visual Studio Code: https://code.visualstudio.com/docs?dv=win&wt.mc_id=DX_841432&sku=codewin



Extensiones Visual Studio
---------------------------------------------------------------------------------------------------

  Angular 8 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout                     
  Angular Language Service                                                                  
  HTML CSS Support                                                                                  
  IntelliSense for CSS class names in HTML                                                                                 
  JavaScript (ES6) code snippets                                                                                 
  jshint                                                                                 
  Material Icon Theme                                                                                 
  Prettier - Code formatter                                                                                 
  Terminal                                                                                 
  TypeScript Importer                                                                                 


Librerias
---------------------------------------------------------------------------------------------------

  Angular material: npm install --save @angular/material @angular/cdk @angular/animations               
  Boostrap: https://getbootstrap.com/
  Ng-Boostrap: https://ng-bootstrap.github.io/#/home npm install --save @ng-bootstrap/ng-bootstrap
  Ag-Grid: https://www.ag-grid.com/angular-getting-started/

FlexBox
---------------------------

  El Módulo de Caja Flexible, comúnmente llamado flexbox, fue diseñado como un modelo unidimensional de layout, y como un método que pueda ayudar a distribuir el espacio entre los ítems de una interfaz y mejorar las capacidades de alineación.
  Ayuda bastante a que la pagina web sea responsiva para ser vista en un smartphone

  FlexLayout(Material): https://tburleson-layouts-demos.firebaseapp.com/#/docs
  Contextos(Boostrap): https://getbootstrap.com/docs/4.3/layout/overview/
 
 
Git 
-------------------------
Borrar rama
git branch -d nombre

Clonar
Formato: https://usuario:token@"ruta"

Token: Gitlab

Clonar: git clone https://usuario:token@"ruta"

Ver configuracion de git: git config --list

¿Que hacer si se me vence el token?
Crear nuevo token en gitlab
Setear la conexion con gitlab: git config --global remote.origin.url "conexion http con usuario y nuevo token"


Maven
---------------------------------------
Levantar proyecto eclipse que este gestionado por maven
- mvn compile (ejecuta el clear y compile)
- mvn install
- mvn -v (ruta y version de setting)
- mvn package (empaquetar proyecto) para ver el tipo de empaquetado(war, ear, jar) se tiene que revisar el pom del proyecto.
- mvn package -Dmaven.test.skip=true (para saltar test)

Si no puedo compilar por permisos del proxy debo ingresar a apache-maven setting e ingresar usuario y contraseña proxy.
