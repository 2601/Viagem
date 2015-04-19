# Viagem


Algoritmo (Método dos mínimos sucesivos)



Para cada rota o método que utilizei foi o método dos mínimo sucessivos que consiste em:


  1) Selecionar a cidade de partida, que neste caso é Lisboa.


  2)Selecionar a cidade mais próxima, em relação àquela em que estamos (excepto a cidade em que queremos acabar o percurso), tal que:
   
    - Nenhuma cidade pode ser repetida, portanto escolhe-se a cidade mais próxima que ainda não se tenha visitado.
   
    - Se houver 2 à mesma distãncia escolhemos aleatóriamente.
    -Depois de terem sido todas visitadas acaba-se na cidade em que se pretende, neste caso Amestardão.





Portanto em relação à rota mais económica, e utilizando o método acima descrito deu-se a seguinte resolução:

Lisboa - Madrid (63.8); Madrid - Paris (97.54); Paris - Luxemburgo (29.15); Luxemburgo - Bruxelas (17.92); Bruxelas - Londres (54.67); Londres - Edimburgo (82.0); Edimburgo - Berna (126.38); Berna - Berlim (89.64); Berlim - Praga (32.18); Praga - Viena (34.67); Viena - Copenhaga (122.27); Copenhaga - Atenas (243.86); Atenas - Roma (318.88); Roma - Amestardão (166.82).

Depois soma-se o custo.

Portanto, a rota mais económica começando em Lisboa e acabando em Amestardão segue o percurso: Lisboa, Madrid, Paris, Luxemburgo, Bruxelas, Londres, Edimburgo, Berna, Berlim, Praga, Viena, Copenhaga, Atenas, Roma e Amestardão, tendo um custo total de 1479.78 euros.




A mesma coisa fiz para encontrar a rota mais rápida:

Lisboa - Madrid (6); Madrid - Bern (12); Bern - Luxemburgo (4); Luxemburgo - Bruxelas (2); Bruxelas - Paris (2); Paris - Londres (5); Londres - Edimburgo (5); Edimburgo - Berlim (14); Berlim - Praga (3); Praga - Viena (2); Viena - Roma (12); Roma - Copenhaga (25); Copenhaga - Atenas (29); Atenas - Amestardão (26).

Soma-se o tempo.

A rota mais rápida começando em Lisboa e acabando em Amestardão segue o percurso: Lisboa, Madrid, Berna, Luxemburgo, Bruxelas, Paris, Londres, Edimburgo, Berlim, Praga, Viena, Roma, Copenhaga, Atenas e Amestardão, demorando um total de 147 horas.



Rota em que se percorre menos distância:

Lisboa - Madrid (638); Madrid - Paris (1268); Paris - Bruxelas (294); Bruxelas - Luxemburgo (233); Luxemburgo - Berna (429); Berna - Praga (766); Praga - Viena (312); Viena - Berlim (666); Berlim - Copenhaga (743); Copenhaga - Londres (1196); Londres - Edimburgo (656); Edimburgo - Roma (2467); Roma - Atenas (2551); Atenas - Amestardão (3082).

Soma-se os kilómetros.

A rota que percorre menos distância começando em Lisboa e acabando em Amestardão segue o percurso: Lisboa, Madrid, Paris, Bruxelas, Luxemburgo, Berna, Praga, Viena, Berlim, Copenhaga, Londres, Edimburgo, Roma, Atenas e Amestradão percorrendo um total de 15301 km. 
