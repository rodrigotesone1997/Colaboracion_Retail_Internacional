<h1 align="center">Bienvenido 👋</h1>
<p>
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/rodrigotesone97" target="_blank">
    <img alt="Twitter: Rodrigo Tesone" src="https://img.shields.io/twitter/follow/rodrigotesone97.svg?style=social" />
  </a>
</p>

Colabore con un empleado de [Tottus](https://www.tottus.com.pe/quienes-somos) para resolver un problema de automatización de recoleccion de datos dentro de la empresa.</br>
El proyecto consistio en realizar un script que al momento de ejecutarse crea 2 nuevas columnas (una en la que se escriben 1 o 0) dependiendo si esta o no el producto. La otra columna anota la fecha donde fue ejecutado el script.</br>

> El repositorio consta de:</br>
> - Un arhcivo de [excel](inventario.xlsx) de prueba (no es el real) donde se almacenan los datos
> - Un [script](proceso_automatizado.py) que al ejecutarlo automatiza el proceso de la creación de columnas

## 📂 Clonar Reposotorio

```

git clone https://github.com/rodrigotesone1997/Colaboracion_Tottus.git

```

## 🐍 Versión de Python

```
Python 3.8.10
```

## ⚙️ Uso
1. Clonar de repositorio
2. `cd Colaboracion_Tottus`
3. Instalar las depedencias `pip install -r requirements.txt`
4. Leer el código y ver los comentarios para ver su uso.
5. Ejecutar [proceso_automatizado.py](proceso_automatizado.py)

## 🤔 ⏰ ¿Como hago para activarlo todas las horas?

Aca dejo algunas sugerencias de como ejecutar de manera automatica el script

#### 🪟 Usuarios Windows:

Para usuarios Windows conviene ejecutar el script dentro del [Task Scheduler](https://www.jcchouinard.com/python-automation-using-task-scheduler/) y ejecutar cada una hora.

#### 🐧 Usuarios Linux:

Para usuarios Linux (yo particularmente uso la distribucion Ubuntu 20.04 pero supongo sera similar el proceso para otras distros) se recomienda utilizar [Crontab](https://www.digitalocean.com/community/tutorials/how-to-use-cron-to-automate-tasks-ubuntu-1804) con el siguiente comando:
> crontab -e

y luego utilizar:<br />

> 0 \* \* \* \* python3 /path/script/proceso_automatizado.py

Lo mas recomendable es subir el script a un servidor en la nube y automatizar el envio de un mail una vez por dia con el archivo excel adjunto.

## ✉️ Contacto

Cualquier sugerencia de arquitectura de código,pregunta o problema enviar mail a rodrigotesone97@outlook.com.ar o a mi [twitter](https://twitter.com/rodrigotesone97)

## 🤔 Autor

👤 **Rodrigo Tesone**

* Twitter: [@rodrigotesone97](https://twitter.com/rodrigotesone97)
* Github: [rodrigotesone1997](https://github.com/rodrigotesone1997)
* LinkedIn: [rodrigo-tesone](https://linkedin.com/in/rodrigo-tesone)


## 📝 Licencia

Copyright © 2021 [Rodrigo](https://github.com/rodrigotesone1997).</br>
This project is [MIT](LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_

