# Skyline CMS Component Template

A PhpStorm template to create custom Skyline CMS component templates.

### Create Project
```bin
$ composer create-project skyline-project/component-template ./my-template
```
Then update the component's name:
1. ```composer.json```  
    line 2: ```skyline-project/component-template``` => ```your-component```
1. ```package.json```  
    line: 2: ````skyline-component-template```` => ```your-component```  
    line: 9: ````… dist/skyline-component-template.min.css```` => ```… dist/your-component.min.css```
1. ```components.cfg.php```  
    lines 14 and 15, 22 and 23, 30 and 31.

#### Start Developing
JS: ````src/index.js````  
CSS: ```style/main.scss```

#### Building
Just run npm predefined scripts:

Build JS only (dev): ```npm run build:js```  
Build CSS only: ```npm run build:css```  
Build whole component: ```npm run build```