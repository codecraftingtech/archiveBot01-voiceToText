# archivBot-voiceToText
Permite transcribir un archivo de voz, por ejemplo m4a a texto plano

# comando ejecutar instalar las librerías
pip install -r requirements.txt
# comando para ejecutar la aplicación
python archivBot-voiceToText.py
# CURL
curl -X POST -F "file=@audios/saludo_prueba1.m4a" http://localhost:5000/transcribe

curl -X POST -F "file=@../audio/saludo_prueba1.m4a" http://localhost:5000/transcribe
# Salida
archivo json con el texto transcribido
{"text": " ¡Gud afternoon, todos! Yesterday I watched the Fantastic Fall movie."}
