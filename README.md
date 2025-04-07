# Klasyfikator stanu choroby na nadciśnienie

W notatniku podjęto działania, aby uzyskać możliwie najlepszy model klasyfikacji stanu choroby na nadciśnienie (y=high_b_pressure) uwzględniający cechy mające największe znaczenie.

Zbiór danych utworzony na podstawie badań NHANES 2005-2006:
<br>https://wwwn.cdc.gov/nchs/nhanes/Search/DataPage.aspx?Component=Questionnaire&CycleBeginYear=2005
<br>https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Demographics&Cycle=2005-2006

## Opis atrybutów:

* ALC_12m - ile dni w roku pijesz jakikolwiek alkohol
* MEAN_ACT - kategoria deklarowanej aktywności fizycznej:
1 - Mainly sit, 2 - Walk a lot, 3 - Carry light loads, 4 - Carry heavy loads
* VIG_ACT - duża aktywność fizyczna 1 - tak, 2 - nie
* VIG_ACT - średnia aktywność fizyczna 1 - tak, 2 - nie
* waist - obwód w pasie
* diabetes - cukrzyca 1 - tak, 2 - nie
* high_b_pressure - chory na nadciśnienie, 1 - tak, 2 - nie
* gender - 1-mężczyzna, 2-kobieta
* pulse - tętno
* sys_pressure - ciśnienie skurczowe mierzone w czasie ostatniej wizyty
* sujective health - ocena zdrowia 1 -najlepsza, 5 najgorsza
* cancer - stwierdzony nowotwór, 1 - tak, 2 - nie
* depressed - samoocena depresji: 0 - nie, 1 - kila dni w roku, 2- większość dni, 3- prawie każdego dnia

Autor: Agnieszka Blok

[Link do Google Colab](https://colab.research.google.com/drive/1iJRfukDjaltod5OOvjnexeFXGtI-sDw8)
