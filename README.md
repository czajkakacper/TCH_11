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
    docker-compose down
    ```
4. Wyniki z poszczególnych etapów są umieszczone w repozytorium:
BazaDanych.png - Jest to wynik z tworzenia nowej bazy w phpMyAdmin<br><br/>
about_config.png - Jest to wynik z oblokowania portu 6666<br><br/>
php.png - Jest to wynik z przeglądarki pod adresem: http://localhost:6666/<br><br/>
phpmyadmin.png - Jest to wynik z logowania do phpMyAdmin pod adresem http://localhost:6001/<br><br/>
konsola.png - Jest to wynik z konsoli

Strona z której skorzystałem przy odblokowywaniu portu:
```
https://www.specialagentsqueaky.com/blog-post/r5iwj96j/2012-02-20-how-to-remove-firefoxs-this-address-is-restricted/
```
