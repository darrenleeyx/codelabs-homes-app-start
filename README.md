1) Install Node.js


2) Install Angular CLI
```bash
	ng install -g @angular/cli (installs the latest version)
	ng version
```

3a) Download the source code to folder and enter project directory
```bash
	npm install (install all dependencies in the project)
```

3b) create new project
```bash
ng new <projectName>
```

4) Run the app locally
```bash
ng serve
```

5) Create components
```bash
ng generate component Home --standalone --inline-template
 ng g c Home --standalone --inline-template
```

6) Create interfaces
```bash
ng generate interface housingLocation
 ng g i housingLocation
```

7) Create services
```bash
ng generate service housing
ng g s housing
```

8) Install json-server
``` bash
npm install -g json-server
json-server --watch db.json
```