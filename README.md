<div id="top"></div>


<div align="center">
<h3 align="center">Realizacja zadania nr 1 w ramach laboratorium PFSwChO - Yevhenii Tsyliurnyk</h3>

</div>

## O projekcie

Aplikacja została stworzona do działania w środowisku Docker. W środowisku tym, kontener `server` jest głównym routerem ruchu i rozdziela on ruch na pozostale kontenery aplikacji.


## Uruchamianie na localhost

1. Sklonuj repo
   ```sh
   git clone https://github.com/J-Ton/PFSwChO_Zadanie1.git
   ```
2. Przejdz do pobrahego katalogu
   ```sh
   cd ./PFSwChO_Zadanie1
   ```
3. W razie potrzeby zmienic port redis w pliku docker-compose.yml
	Defoltowo ustawiony 6350
4. Uruchom przy użyciu docker-compose
   ```sh
   docker-compose -f docker-compose.yml up --build --force-recreate
   ```
5. Uruchom przeglądarke i przejdź pod poniższy adres
   ```sh
   http://localhost
   ```
