# RMpedia

## Índice

- [1. Nombre del Producto](#1-nombre-del-producto)
- [2. Consideraciones Generales](#2-consideraciones-generales)
- [3. Definición del Producto](#3-definición-del-producto)
- [4. Organización del Proyecto](#4-organización-del-proyecto)
- [5. Historias de Usuario](#5-historias-de-usuario)
- [6. Diseño de la Interfaz de Usuario](#6-diseño-de-la-interfaz-de-usuario)
- [7. Test de Usabilidad](#7-test-de-usabilidad)
- [8. Checklist del Proyecto](#8-checklist-del-proyecto)

## 1. Nombre del Producto
RMpedia.

## 2. Consideraciones Generales
Rick y Morty es una serie de televisión estadounidense de animación para adultos. La serie tiene gran acogida a nivel mundial,
de todo este fandom hay un grupo que desea poder interactuar y ver la información sobre esta serie.

## 3. Definición del Producto
Para conocer las necesidades del público de la serie, realizamos una encuesta virtual, encontrando como resultado:

*a. ¿Quiénes son los principales usuarios de producto?*
- Personas entre 15 y 40 años, siendo en su mayoría adultos jóvenes entre 25 y 30 años.

![Encuesta-edad](https://user-images.githubusercontent.com/91750603/145142969-780e35c9-fd88-4d80-9a00-134c5861ded4.jpg)

*b. ¿Cuáles son los objetivos de estos usuarios en relación con el producto?*
- Conocer más de la serie (personajes, temporadas y otros)

*c. ¿Cuáles son los datos más relevantes que quieren ver en la interfaz y por qué?*
Información de:
- Personajes, porque aparecen más de 200 personajes durante toda la serie y el usuario quiere saber sobre ellos.
- Episodios, el usuario desea saber la trama de los episodios y los personajes que participan en ellos.
- Lugares, la serie que cuenta con muchas lugares (planetas, viajes en el tiempo, otras realidades) el usuario quiere conocer sobre ello.

![EncuestaInterfaz](https://user-images.githubusercontent.com/91750603/145144280-47e12c41-c4ce-4497-bcfc-ad7ecd9be78f.jpg)

*d. ¿Cuándo utilizan o utilizarían el producto?*
- El usuario lo usaría en momentos libres, a través de dispositivos móviles y web.

![EncuestaDispositivo](https://user-images.githubusercontent.com/91750603/145143785-8d061005-807a-492e-ba82-5efa7ce02996.jpg)

## 4. Organización del Proyecto
Para organización del proyecto el equipo optó por trabajar en base a la metodología ágil *Scrum*, 
para ello se empleó la herramienta [Trello](https://trello.com/invite/b/CEPkKv4H/bfd2fc0fce23a11dc8aa3439cc99cec9/proyecto-data-lovers "Trello").

## 5. Historias de Usuario
|  *HISTORIAS DE USUARIO* |*DETALLE*   |
| ------------ | ------------ |
| HU 1 | Como espectador quiero información relevante   para conocer a todos los personajes de la serie Rick and Morty. |
| HU 2 | Como espectador quiero filtrar por género a los personajes para visualizar sus datos. |
| HU 3 | Como espectador quiero filtrar por estado de vida o por especie a los personajes para visualizar los datos. |
| HU 4 | Como espectador - quiero ordenar de forma ascendente o descendente a los nombres de los personajes para poder identificarlos mejor. |

## 6. Diseño de la Interfaz de Usuario
En base a los resultados se diseñaron los siguientes prototipos.

### 6.1 Prototipos de Baja Fidelidad
Para el diseño del prototipo inicial se empleó la aplicación Microsoft PowerPoint (prototipo de baja fidelidad)
    
 *Imagen N°1: Interfaz inicial*
 
![PrototipoBajaFidelidadHome](https://user-images.githubusercontent.com/91750603/145139047-247c1269-cb38-4b4c-883f-f5c12da34425.jpg)

 *Imagen N°2: Interfaz Sección Personajes*
 
![PrototipoBajaFidelidadPersonajes](https://user-images.githubusercontent.com/91750603/145139273-8c6f4cd9-d271-4541-8ffb-535625ce055a.jpg)

 *Imagen N°3: Elección de patrón de colores*
 
![PrototipoBajaFidelidadPatronColores](https://user-images.githubusercontent.com/91750603/145139610-e18c28d8-9f44-49e3-8211-7cfc56fd7048.jpg)

### 6.2 Prototipos de Alta Fidelidad
El Diseño de la Interfaz de Usuario (prototipo de alta fidelidad) se empleó la herramienta Figma. 
[Prototipo](https://www.figma.com/file/J84alZJLUSfXrqJQEhqv2m/Web?node-id=0%3A1 "Prototipo")

## 7. Test de Usabilidad
El listado de problemas que se detectaron a través del test de usabilidad fueron los siguientes:
- Con respecto a las imágenes mostradas el usuario prefería que el fondo de las imágenes sea blanco.
- En relación al tamaño de las letras de los filtros, evidenció que le costaba leerlos.
- De igual manera, prefería que los filtros estuvieran ordenados alfabéticamente. 
 
## 8. Checklist del Proyecto
    [x] Usa VanillaJS.
    [x] Pasa linter (`npm run pretest`)
    [x] Pasa tests (`npm test`)
    [x] Pruebas unitarias cubren un mínimo del 70% de statements, functions y lines y branches.
    [x] Incluye Definición del producto clara e informativa en `README.md`.
    [x] Incluye historias de usuario en `README.md`.
    [x] Incluye sketch de la solución (prototipo de baja fidelidad) en `README.md`.
    [x] Incluye Diseño de la Interfaz de Usuario (prototipo de alta fidelidad) en `README.md`.
    [x] Incluye link a Figma en `README.md`.
    [x] Incluye el listado de problemas que detectaste a través de tests de
        usabilidad en el `README.md`.
    [x] UI: Muestra lista y/o tabla con datos y/o indicadores.
    [x] UI: Permite ordenar data por uno o más campos (asc y desc).
    [x] UI: Permite filtrar data en base a una condición.
    [x] UI: Es responsive.
