# webinar-process-manager
webnar with events, spring cloud stream and process manager


Ejemplo del video https://www.youtube.com/watch?v=LvmPa7YKgqM&index=34&list=WL

Se crea una api manager que se encarga de recibir los eventos de dominio (esta subscipto a una cola kafka "users") 
y distribuirlos en las restantes colas una por cada api (payments, communication, payments). 

Test para verificar que cada cola reciba el evento en cada caso. Muy bueno.
