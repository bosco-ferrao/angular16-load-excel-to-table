# angular16-load-excel-to-table

Practicing Angular 16 just for fun:

```
build."configurations": {
            "development": {
              "optimization": false,
              "sourceMap": true,
              "namedChunks": true,
              "extractLicenses": true,
              "vendorChunk": true,
              "buildOptimizer": false,
              "budgets": [
                {
                  "type": "initial",
                  "maximumWarning": "2mb",
                  "maximumError": "6mb"
                },
                {
                  "type": "anyComponentStyle",
                  "maximumWarning": "6kb",
                  "maximumError": "10kb"
                }
              ]
            },
```


```
serve."configurations": {
            "development": {
              "browserTarget": "demo:build:development"
            },            
```
The above things are done in project.

npm install -g @angular/cli --no-fund

npm install --no-fund

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

ng build --configuration development

ng serve --configuration development

