# PARCIAL_2_SD
## Nombres:
Julian CAmilo Ceron 

Marìa Jose Espinosa 

## Etapa 1. El aeropuerto abre con nombres Pokémon (25 min)
### 1.
![Docker Compose sin declarar redes](Capturas/punto%201%20evidencia%20api.png)

### 2.
![Docker Compose sin declarar redes](Capturas/punto%201%20evidencia%20traefik.png)

### 3.
![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%201%20evidencia%20neo4j.png?raw=true)

## Etapa 2. Vuelos comerciales y vuelos legendarios (30 min)
![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%202%20evidencia.png?raw=true)
![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%202%20evidencia%20balanceo.png?raw=true)

## Etapa 3. Aduanas y controles de seguridad (30 min)
1. Neo4j protegido con autenticación básica.
   ![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%203%20evidencia%20auth.png?raw=true)
   EXPLICACIÓN ANALOGIA: En el contexto del aeropuerto, Neo4j con autenticación básica funciona como migración, donde solo pasas si muestras tu pasaporte (usuario y contraseña)
3. La API debe tener un filtro adicional (en este caso rate limit)
  ![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%203%20evidencia%20ratelimit.png?raw=true)
 EXPLICACIÓN ANALOGIA: En el rate limit representa como una puerta de embarque, no podemos dejar pasar un numero ilimitado de personas(pokemones), ya que se colapsaria. Por esto, hay que limitar el numero de personas que pasan al mismo tiempo por la puertal (las peticiones por segundo en la pagina).

## Etapa 4. Área restringida y sala de prensa Pokémon (35 min)
![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%204%20eviencia%20neo4j%20no%20accesible.png?raw=true)
![Docker Compose sin declarar redes](https://github.com/julianceron64/Parcial_2_SD/blob/main/Capturas/punto%204%20evidencia%20ngnix.png?raw=true)

