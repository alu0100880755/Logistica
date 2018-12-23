# Logística
Modelos del problema del viajante de comercio (TSP) resueltos con **Pyhton** y **Or-Tools**.

## Travelling Salesman Problem (TSP)
Este problema trata de dado un grafo dirigido, encontrar un circuito que visite cada nodo del grafo una y sólo una vez y con costo total mínimo.

### Primer modelo de TSP
#### [TSP_1.ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_1.ipynb)

### Segundo modelo de TSP
#### [TSP_2.ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_2.ipynb)

### Tercer modelo de TSP
#### [TSP_3.ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_3.ipynb)

### TSP con relaciones de precedencia
Se establece una restricción adicional: algunos nodos deben ser visitados después de otros.
#### [TSP_4 (Precedencias).ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_4%20(Precedencias).ipynb)

### TSP con recogidas y entregas
Cada nodo representa ahora un cliente con una demanda (positiva, negativa o nula) para cada uno de los productos y hay un vehículo con un capacidad Q.
#### [TSP_5 (Recogidas y entregas).ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_5%20(Recogidas%20y%20entregas).ipynb)

### TSP con ventanas temporales
Se establece otra restricción adicional: los clientes tienen "ventanas temporales" en las que el vehículo puede visitarlo.
#### [TSP_6 (Ventanas Temporales).ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_6%20(Ventanas%20Temporales).ipynb)

### TSP con varias pilas
Se pretende buscar 2 circuitos. Uno en Tenerife donde se recogen objetos y otro en Gran Canaria donde se entregan. El objeto recogido en el cliente "x" en Tenerife se entrega en el cliente "x" de Las Palmas, es decir, hay una correspondencia biyectiva (uno-a-uno) entre los clientes.
#### [TSP_7 (Varias Pilas).ipynb](https://github.com/alu0100880755/Logistica/blob/master/TSP_7%20(Varias%20Pilas).ipynb)
