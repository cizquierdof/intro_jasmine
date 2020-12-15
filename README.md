# Introducción a Jasmine

Breve introducción a Jasmine en el entorno de node

## Instalación

Donde queramos que se ejecute el entorno de test de Jasmine debermos primero inicializar node y despues cargar e inicializar jasmine

1. Inicializar node
```
npm init -y
```
el parámetro -y es para que no nos pregunte nada

2. instalar jasmine
```
npm i --save-dev jasmine
```

3. iniciar jasmine
```
npx jasmine init
```
 Se deben haber creado una carpeta /spec que es donde se pondrán luego los test. Para que se ejcuten los test hay que cambiar en package.json la linea de test por
 ```json
     "test": "jasmine"
```
 Después se crean los aarchivos de test dentro del directorio /spec. Es una buena práctica utilizar como nombre de test el mismo nombre de lo que se quiere probar añadiendole .spec. 

 En este ejemplo se le hace test a una app de calculadora que se encuentra en Calc.js