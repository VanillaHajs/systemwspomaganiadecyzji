
Zadanie 1
1. Większa wartość gamma umożliwia poruszanie się w wielu kierunkach a to owocuję lepszą jakością drogi do znalezienia frisbee.

2. Value_iteration i policy_iteration to dynamiczne algorytmy programowania wykorzystywane w Reinforcement Learning.

Value_iteration
- algorytm jest bardziej złożony.
- algorytm potrzebuje dużo iteracji aby uzyskać najlepszy wynik.
- wolniejszy z uwagi na złożoność.

Policy_iteration
- algorytm jest prostszy.
- mniej iteracji niż w przypadku Value_iteration
- szybszy.

3. Value_iteration działa na zasadzie osiągania największego zysku. 
Potocznie nazywa się to przypisywaniem wartości "od celu do gracza".
Początkowe wartości stanów będą wypełnione zerami. Tablica wartości z czasem będzie zapełniana najwyższymi wartościami możliwymi przy następnym stanie.
Posiadając już największe wartości, tworzy się tablice optymalnych akcji.
Dla każdego stanu o największej wartości jest zapisywana dana akcja.
Na podstawie wartości dających najwyższy zysk, algorytm opracowuję strategie.
W przypadku policy_iteration algorytm analizuję możliwe przejścia danej drogi i na końcu wybiera to najbardziej optymalne przejście.
