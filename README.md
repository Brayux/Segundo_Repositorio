# Segundo_Repositorio
Reto 03
Buenos dias profe
*Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

Diagrama de Flujo
https://www.mermaidchart.com/raw/702fc7e3-a0ae-4dd4-8f8c-4ad0590415d9?theme=dark&version=v0.1&format=svg

Pseudocódigo

[variables]
n : natural
i : natural

inicio
listado de 2 hasta n+1 
listado de 2 hasta i+1

escribir [n / i]
{modulo condiconal con la pregunta ¿Únicamente tiene dos residuos de 0?}
  si modulo [n/i = a dos 0 como residuo]
  escribir [n es primo]
  si no [n/i = a más de dos 0 como residuo]
   escribir [n no es primo]
Fin

*Revise el procedimiento matemático para hallar raíces cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.

Diagrama de flujo 
https://www.mermaidchart.com/raw/06ed6fd3-d68a-46e7-b5fa-c60fb4625864?theme=dark&version=v0.1&format=svg
Pseudocódigo

[variables]
n : raíz de un número 
x : natural
y : natural diferente de x
≈ : aproximado

inicio
escribir [Separar las cifras en pares de derecha a izquierda]
{modulo condiconal con la pregunta ¿Las parejas están completas?}
  si modulo [x * x = primera pareja]
  escribir [primera pareja ≈]
  si no [x * y = primera pareja]
   escribir [primera pareja ≈]
   
escirbir [Restar el aproximado con la primera pareja y bajar residuo]
escribir [Tomar el resultado de la primera pareja y multiplicarlo por 2]
escribir [Combinar el resultado con números del 1 al 5 y multiplicarlos por los mismos números en órden consecutivo]
escribir [Escoger el resultado más cercano al residuo]
{modulo condiconal con la pregunta ¿Al restar el residuo es exacto?}
  si modulo, escribir [Es un número natural
  si no, escribir [Es un número racional]

Fin
