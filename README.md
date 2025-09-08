<h2>Descripción📰</h2>
Este proyecto implementa un pipeline ETL en Python que recibe dos archivos de entrada (un CSV de rendición y un Excel de liquidación), los limpia, transforma y consolida en un único archivo.

El resultado es un Excel comparativo que permite detectar:

- Registros presentes en rendición pero no en liquidación.

- Registros presentes en liquidación pero no en rendición.

- Diferencias en montos entre ambas fuentes.

- Diferencias en condición de IVA

Además, se desarrolló una interfaz en Streamlit que facilita la carga de archivos y la generación del resultado de forma intuitiva, sin necesidad de conocimientos técnicos.

<hr>

<h2>Tecnologías utilizadas⚙️</h2>

-   <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white">

- <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">

- <img src="https://img.shields.io/badge/OpenPyXL-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">

- <img src="https://img.shields.io/badge/Streamlit-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white">

- <img src="https://img.shields.io/badge/EXCEL/CSV-4CAF50?style=for-the-badge&logo=data%20analysis&logoColor=white">

<hr>

<h2>Instrucciones de uso🚀</h2>
<h3> 1. Clonar el repositorio </h3
                                
- git clone https://github.com/FedeBarbarroja/ETL-COMPARACION-APP.git
- cd ETL-COMPARACION-APP

<h3> 2. Instalar paquetes </h3

- pip install -r requirements.txt

<h3> 3. Ejecutar la aplicación Streamlit </h3

- python -m streamlit run Streamlit_Demo.py

<h3> 4. Subir los archivos de entrada desde la interfaz web </h3

 rendicion.csv

 liquidacion.xlsx

<hr>


<h2>Capturas de pantalla📷 </h2>

![Streamlit UI](./images/demo_streamlit.jpg)
![Excel Output](./images/comparacion.png)

<hr>


<h2>Nota importante⚠️</h2>

Los datos incluidos en este repositorio fueron anonimizados. Son ejemplos ficticios utilizados únicamente con fines de demostración.














