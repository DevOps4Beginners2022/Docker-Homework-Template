### Docker Homework 1

Przygotuj obraz na bazie nginx:1.21.6. Zmodyfikuj odpowiednio plik `Dockerfile`.

1. Zmodyfikuj plik `Dockerfile` tak, aby tag z wersją nginx można było podać przy budowaniu obrazu w zmiennej `NGINX_VERSION`. Domyślną wersją powinna pozostać 1.21.6. (1pkt)

2. Przenieś pliki `default.conf` do katalogu `/etc/nginx/conf.d/` oraz `index.html` do katalogu `/usr/share/nginx/html`. Uzupełnij plik `Dockerfile` oraz konfigurację nginxa w pliku `default.conf`, tak aby po wykonaniu zapytania na port 8000 (port w kontenerze) serwer zwrócił zawartość pliku `index.html`. (1pkt)

3. Rozszerz wyżej wymieniony plik konfiguracyjny `default.conf` tak, aby serwer http odpowiadał także na port 8001. Po wykonaniu zapytania na ten na port należy zwrócić string `DevOps 4 Beginners 2022` w base64. (1pkt)

4. Zainstaluj w kontenerze paczkę `htop`. (1 pkt)
