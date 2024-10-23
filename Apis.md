#APIs Clima
import requests 
ciudad="Huixquilucan"
api_key="25bc3acec477c3034befab3dd1ac8be4"
url = f"https://api.openweathermap.org/data/2.5/weather?q={ciudad}&appid={api_key}"
respuesta = requests.get(url)
data = respuesta.json
data

#APIs Superheroes
