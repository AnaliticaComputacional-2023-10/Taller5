# Taller 5

### Primeros Pasos en la Nube: EC2 - IaaS

##### Analítica Computacional para la Toma de Decisiones

---

|     Nombres      |      Apellidos       |     Login     |  Codigo   |
| :--------------: | :------------------: | :-----------: | :-------: |
|     Santiago     | Gonzalez Montealegre | s.gonzalez35  | 202012274 |
| Juliana Carolina |  Cardenas Barragan   | jc.cardenasb1 | 202011683 |

---

---

## 1. Primeros pasos en AWS EC2: lanzar una máquina virtual

---

6. Lanzar instancia

- i. Snapshot tablero instancia en ejecución.

![a](image/Taller5-Soluci%C3%B3n/1677187092917.png)

---

7.  Copie algunos datos de su instancia

![1677357929277](image/Taller5-Solución/1677357929277.png)

- Dirección IP v4 pública: 34.237.91.238 / 3.222.215.237.
  - Nota: debido a que se cerró la máquina virtual los pantallazos son hechos con la primera dirección IP (34.237.91.238), sin embargo, la ejecución publicada en Slack corresponde a 3.222.215.237.
- Dirección IP v4 privada: 172.31.50.94
- Tipo de Instancia: t2.micro
- Plataforma: Amazon Linux (inferido)
  - Detalles de la plataforma: Linux/UNIX
- Tipo de virtualización: hvm
- Número de CPU virtuales: 1
- Zona de disponibilidad: us-east-1e
- ID de volumen: vol-062986804c24da795
- Pestaña monitoreo: ![1677358444511](image/Taller5-Solución/1677358444511.png)

---

9. Conectarse a una instancia

![1677358093286](image/Taller5-Solución/1677358093286.png)

---

## 2. Configurar la instancia y lanzar el tablero

---

1. Actualice el sistema

![1677358187478](image/Taller5-Solución/1677358187478.png)

---

2. Verificar las versiones

![1677358227222](image/Taller5-Solución/1677358227222.png)

---

7. Copiar archivo en la máquina virtual

![1677362809416](image/Taller5-Solución/1677362809416.png)

---

8. Cree una copia del archivo

![1677363031917](image/Taller5-Solución/1677363031917.png)

---

9. Modificar el archivo

![1677363154118](image/Taller5-Solución/1677363147559.png)
![1677363154118](image/Taller5-Solución/1677363154118.png)

---

12. Regla Grupo de Seguridad

![1677363318173](image/Taller5-Solución/1677363318173.png)

---

13. Correr la aplicación

![1677363372152](image/Taller5-Solución/1677363372152.png)

A continuación, se muestra la prueba de los varios intentos que se tuvieron

![1677366343487](image/Taller5-Solución/1677366343487.png)
