# **Prueba Técnica - API de Rick and Morty & HubSpot**

## **Descripción del Proyecto**
El objetivo de esta prueba es crear una aplicación sencilla simple que:
1. **Consuma datos** de la API de Rick and Morty.
2. **Transforme los datos** aplicando un filtro basado en la edad o un criterio relacionado con la información obtenida (Puedes escogerlo con toda libertad).
3. **Envíe los datos filtrados** a HubSpot usando la API de CONTACTOS.

Este desafío es una oportunidad para demostrar tu capacidad de integrar APIs, manejar datos y aplicar transformaciones simples.

---

## **Requerimientos**
### **1. Consumo de la API de Rick and Morty**
- Utiliza el endpoint `/character` para obtener datos de los personajes.
- Documentación oficial: [https://rickandmortyapi.com/documentation](https://rickandmortyapi.com/documentation).

### **2. Filtro y transformación**
- Aplica un filtro a los datos obtenidos, por ejemplo:  
  - Clasifica a los personajes como "mayores" o "jóvenes" basado en un cálculo que uses como "edad estimada" (puedes usar el número de episodios en los que aparecen como referencia).  
- Los resultados filtrados deben estar listos para enviarse a otro sistema.

### **3. Envío a la API de HubSpot**
- Conecta tu aplicación con la API de HubSpot.  
- Enviar los datos filtrados como contactos o cualquier objeto que consideres relevante.

- **Recuerda usar la API Key que generaras en tu cuenta de HubSpot**
- 1. Generar una API Key
- Ve a tu cuenta de HubSpot.
- Navega a Configuración (ícono de engranaje).
- En el menú lateral, selecciona Integraciones > API Keys.
- Genera una nueva clave API y guárdala (ya que solo se mostrará una vez).

- Documentación oficial de HubSpot: [https://developers.hubspot.com/docs/api/overview](https://developers.hubspot.com/docs/api/overview).

---

## **Requisitos Técnicos**
- **Lenguaje**: Puedes usar cualquier lenguaje, pero recomendamos **Python** o **Node.js**.
- **Comentarios**: La sección de comentarios va a ser uno de los puntos mas importantes de la prueba.  
- **Frameworks sugeridos pero depende del lenguaje de programación que prefieran y no es obligatorio tener Backend, puede ser una aplicación Vanilla**:
  - Python: Flask o FastAPI (Opcional).  
  - Node.js: Express (Opcional).
- **Buenas prácticas básicas**:
  - Código organizado y claro.
  - Validación de errores básicos (como fallos en la conexión o datos inválidos).
  - Uso de control de versiones con Git (Opcional).

---

## **Los entregables pueden ser repositorio de Github Ó archivo .zip**
1. Link de repositorio de github (en dado caso recuerda ponerlo público para poderlo leer).
2. Carpeta comprimida.
