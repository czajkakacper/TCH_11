# Laboratorium 11 - Docker Compose

Przebieg zadania:
1. Uruchomienie usług(php, phpmyadmin, mysql, nginx), które zostały zdefiniowane w pliku docker-compose.yml:
    ```
    docker compose up -d
    ```
2. Uruchomienie usług w przeglądarce pod portami 6001 oraz 6666(port 6666, wcześniej został odblokowany w przeglądarce pod adresem about:config, wynik z tej operacji został przedstawiony na zdjęciu):
    ```
    http://localhost:6001/
    ```
    ```
    http://localhost:6666/
    ```
3. Na koniec zatrzymanie i usunięcie konterów:
    ```
    docker compose down
    ```


  
