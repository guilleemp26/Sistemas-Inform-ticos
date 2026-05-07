<div align = center>

# Unidad 5
## Práctica 1


</div>
<div align = right>

<img src="img/Ud_5p1_img/portada.jpg">

**Guillem Porta Ortuño**

**15/05/26**
</div>

---

### 1. Identificación de interfaces de red
Para este ejercicio he utilizado el comando "ip a", que muestra información sobre la tarjeta de red instalada
y de tu IP.
![alt text](img/1.png)

![alt text](img/2.png)

- **¿Qué interfaz de red está activa?:** enp0s8
- **¿Qué dirección IP tiene asignada actualmente?:** 10.0.2.15
- **¿Qué dirección MAC tiene la interfaz?:** 08:00:27:62:33:d1
- **¿A qué red pertenece la dirección IP?:** 10.0.2.0
  
---

### 2. Identificación de la configuración de red
En este ejercicio he ejecutado el comando "ip addr" y "ip route", el primer comando hace exactamente lo mismo que "ip a", el 
comando utilizado en el ejercicio anterior. Por otro lado el segundo comando te da información como la puerta de enlace, que es la ip
con la que sale el equipo a la red "exterior", o el rango de ip local, si quieres "hablar" con un equipo del mismo rango, no necesitas pasar
por el router ya que pertenece a la misma red.

![alt text](img/3.png)

![alt text](img/4.png)

- **¿Qué red local aparece configurada?:** 10.0.2.0/24
- **¿Qué interfaz se utiliza para acceder a esa red?:** enp0s8
- **¿Existe una puerta de enlace configurada?:** 10.0.2.2

---

### 3. Configuración del nombre de host
