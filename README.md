# Addi
Creamos un entorno con python 3.11.4, e instalamos las dependencias necesarias.

    $   conda create -n myenvapp1
    $   conda activate myenvapp1
    $   conda install python=3.11.4
    $   pip install -r requirements.txt
    $   streamlit run app.py
    
##  3. Producción en servidor remoto

    *   Activar una cuenta en google cloud
    *   Crear proyecto en google cloud
    *   Instalar GoogleCloudSDK
        (https://cloud.google.com/sdk/docs/install)
    *   Ejecutar en la terminal:
    
    $ gcloud init
    $ gcloud app deploy app.yaml --project "nombre proyecto en GCloud"

    $ gcloud components update


