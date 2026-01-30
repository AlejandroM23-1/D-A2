# D-A2
¿Qué se aprendió?
Se aprendió sobre Library Hijacking que es una forma que tienen los atacantes de subplantar código malicioso en módulos de uso común(hashlib.py, json.py, etc). El library Hijacking se aprovecha de que python primero busca
los modulos en la carpeta donde se encuentra el archivo que los importa.

Es un riesgo de seguridad porque, a diferencia de un malware normal, este se hace pasar por una funcionalidad legítima(un módulo del propio python) y puede ejecutar código malicioso sin que la victima tenga sospechas.
