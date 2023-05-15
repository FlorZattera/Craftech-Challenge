# craftech-challenge
Resolución de desafío enviado por mail por la empresa Crafttech

Buenas tardes! Muchas gracias por tomarse el tiempo de revisar el repositorio en el que he trabajo durante esta semana.
Quería hacer algunas aclaraciones con respecto a la resolución de los ejercicios.
En el primer ejercicio, donde se me pidió un diagrama de redes, opte por adjuntar la arquitectura que me encuentro desplegando en este momento.
Cumplo el rol de Cloud Architech en un equipo Scrum y nuestro MVP, que será entregado la semana próxima, cuenta con dicho diagrama. Me tomó cuatro
meses aprender los conceptos básicos e intermedios de AWS (quienes mentorizan el programa) y me parecio correcto adjuntarlo.
En el segundo ejercicio se me pide deployar un repositorio y dockerizarlo. Clone el repositorio que me pasaron para el desafío, como parte del CI
realice un build de la imagen en Dokerhub. Ambas capas de desarrollo se encuentran dockerizadas y realicé el deployment con kubernetes. Adjunté 
el archivo con la cual lo cree y con el comando kubectl apply -f https://k8s.io/examples/controllers/nginx-deployment.yaml cree el deployment.
Use el comando kubectl get deployments para visualizar el deployment y la salida fue exitosa. 
En el tercer ejercicio se me solicitó realizar el CI/CD de un sitio web sencillo. Opté por seleccionar un repositorio de una página web
de Github. La cloné y añadi el Workflow. Utilicé el website Actions de Git para llevar a cabo el CI y como el CD realicé el push a Githun page. 
En mi repositorio se encuentra el enviroment que muestra que la salida del código fue exitosa. 
Ante cualquier duda o inquietud estoy a su disposición... 
Les agradezco mucho por su tiempo y por dejarme descubrir este mundo de DevOps que tanto disfrute.

Los saludo atentamente...

Florencia Zattera.
