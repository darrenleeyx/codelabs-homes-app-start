1) Install Node.js

2) Install Angular CLI
```bash
ng install -g @angular/cli (installs the latest version)
ng version
```

3) Open a project

```bash
Download the source code to folder and enter project directory
npm install (install all dependencies in the project)

OR

Create new project
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