Dobrý den.
Jako můj ročníkový projekt poté, co nám nevyšla enigma jsem se rozhodl, že ve Visual Studiu vytvořím šifrovací program.
Nedělal jsem ho z mé vlastní hlavy a využil jsem několik zdrojů:
https://www.geeksforgeeks.org/encrypt-and-decrypt-text-file-using-cpp/
http://www.trytoprogram.com/cpp-examples/cplusplus-program-encrypt-decrypt-string/
https://www.programiz.com/cpp-programming/goto
https://www.youtube.com/watch?v=5Tru2jvVGqk&ab_channel=ProgrammingWithAnnu
https://www.youtube.com/watch?v=kY0U1mFmwKE&t=66s&ab_channel=VoxelPixel
https://www.youtube.com/watch?v=DoS3jfrNZIY&ab_channel=EasyProgramming


Tady popíšu kroky a co v progamu má jakou funkci

![image](https://user-images.githubusercontent.com/106261041/170357648-06007123-8122-4027-bacb-d5eeb196d624.png)

Nejdříve použijeme funkci include aby procesor věděl co si má připravit


![image](https://user-images.githubusercontent.com/106261041/170556808-0e2b4fb1-b4df-4bb7-bddf-e0a98ecd7137.png)
![image](https://user-images.githubusercontent.com/106261041/170562002-34a79e67-360d-4eab-8d08-9e9d6d6463e1.png)


Připravím si několik proměnných.

long int: promněná která pracuje s 64 bitovým číslem

void: Funkce nebude vracet hodnotu

Char: označení pouzde jedné promněné a jejíj hodnoty-v tomhle případě en=50 a m=50

Promněná x a y musí být prvočíslo nebo program nebude fungovat a budete muset začít znovu

První funkce ponese defalutně jméno main.

N bude poté náš klíč soukromý a veřejný.

Poté se nám díky složitým algoritmum vzniknu čísla a z těch poté se nám zašifruje naše zpráva.

![image](https://user-images.githubusercontent.com/106261041/170565067-2e34abac-d715-4b51-adc6-44db3a5478eb.png)

![image](https://user-images.githubusercontent.com/106261041/170565088-49615042-0764-4753-ab41-89311c3efc18.png)

Šifrování funguje na tom principu že to vezme daný znak a pak ho po výpočtech hodí do ASCII tabulky a to následně vypíše 

![image](https://user-images.githubusercontent.com/106261041/170563276-76d26115-00ac-44af-8327-392eb48d618c.png)

Program hned nevypíše to co jsme tam napsali za zprávu ale nejdříve dešifruje námi již napsanou a zašifrovanou zprávu a až poté ji vypíše.

To je celý program.
Chtěl jsem ho trochu vylepšit napaříklad pokud by se nenapsalo prvočíslo tak by to uživatele hodilo zpět k zadávání ale op několika pokusech co to nešlo jsem to vzdal.
Tento projekt jsem dělal poněkud na rychlo, protože naše enigma se nám nepodařila a šli jsme dělat něco jiného a já dlouho přemýšlel co udělat, až mě napadlo tohle.
Přeji příjemné šifrování :)
