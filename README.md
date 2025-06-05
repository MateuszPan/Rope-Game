# Rope-Game


Gra ta jest symulacją fizyczna, w którj gracz może manipulować liną, do której przyczepiony jest kamień. Lina składa się z 20 cząsteczek połączonych za pomocą 19 sprężyn. Sprężyn zapewniają to, że cząsteczki zachowują się jak lina, zachowując elastyczność i sprężystość. Manipulacja odbywa się w przestrzeni 3D. Zadaniem gracza jest manipulowanie siłą wiatru (klawisze W, A, D) tak,aby kamień, który jest złączony z liną, uderzył w żółtą kulę, znajdującą się w tej przestrzeni 3D. Gracz może wpływać na ruch liny za pomocą siły wiatru sterowanej klawiszami klawiatury lub bezpośrednio oddziałując na kamień za pomocą myszy. Dzięki zastosowaniu kamery, która obraca widok, użytkownik, może podejść do układu z każdej strony.


1. Implementacja oparta o metodę Verleta
   Kod używa metody Verleta do uaktualniania pozycji cząsteczek. (W funkcji update, każda cząsteczka jest aktualizowana w pętli przy użyciu particle.update(deltaTime). Wwymaganie jest więc spełnione.

2. Model trójwymiarowy
   Model działa w przestrzeni 3D, lina też jest trójwymiarowa (użyte funkcje do rysowania jak np. ofDrawSphere czy ofDrawLine operują w przestrzeni 3D). 
Wymóg modelu trójwymiarowej liny jest spełniony. 

3. Uwzględnienie sił zewnętrznych spoza zbioru {grawitacja, sprężystość, siła oporu, siła wiatru}

4. Program jest oryginalny, oraz jest stosunkowo słożony.

5. Grywalność i przyjemność płynąca z mechaniki i tworzonej animacji
   Gra polega na dotknięciu przez 'kamień' złotego punktu, w którym momencie gracz wygra grę. Kamień jest kontrolowany przez gracza za pomocą siły wiatru, przy pomocy przycisków WASD, oraz jego siły, przy pomocy Q i E.
