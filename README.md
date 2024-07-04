import matplotlib.pyplot as plt
import numpy as np

# Datos
meses = ["1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12"]
demanda = [9, 10, 8, 10, 9, 11, 9, 10, 12, 13, 11, 12]

# Pronósticos con promedio móvil de 4 meses
pms_4meses = [None, None, None, None, 9.25, 9.25, 9.5, 9.75, 9.75, 10.5, 11, 11.5]

# Pronósticos con promedio móvil ponderado de 4 meses
pms_ponderado_4meses = [None, None, None, None, 9.3, 9.3, 10, 9.7, 9.7, 11, 12, 11.6]

# Gráfico
plt.figure(figsize=(12, 6))
plt.plot(meses, demanda, marker='o', linestyle='-', color='b', label='Demanda Real')
plt.plot(meses, pms_4meses, marker='x', linestyle='--', color='r', label='PMS 4 Meses')
plt.plot(meses, pms_ponderado_4meses, marker='s', linestyle=':', color='g', label='PMS Ponderado 4 Meses')
plt.xlabel('Mes')
plt.ylabel('Demanda')
plt.title('Pronósticos de Demanda Mensual')
plt.grid(True)
plt.legend()
plt.show()

- 👋 Hi, I’m @vicgar1970
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
vicgar1970/vicgar1970 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
