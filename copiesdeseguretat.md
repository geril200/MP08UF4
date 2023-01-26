# Copies de seguretat:

## Importància de les còpies de seguretat:

Quan treballem com administradors d'un servei ens hem de preocupar de com evitar que es perdin les dades o guardar-les per migrar-les a un altre servidor.

Per aquest motiu és important conèixer la informació necessària per poder recuperar el servei en cas d'error o migració.

També podem fer còpies de seguretat únicament de cursos per passar-los a un altre Moodle o crear un curs idèntic.

## Còpia de seguretat d'un curs:

![image](https://user-images.githubusercontent.com/110727546/212052894-c02acab1-3004-4a59-be6d-480c5457bb79.png)

![image](https://user-images.githubusercontent.com/110727546/212726727-6e23b7c5-566c-43d4-b634-22f19e80de9d.png)


Les còpies de seguretat d'un únic curs es fan des de'l mateix Moodle.

Serveixen per duplicar cursos, pasar informació i recursos d'un curs a un altre o migrar un curs a un nou servidor de Moodle.

[Tutorial a Moodle](https://docs.moodle.org/all/es/Respaldo_del_curso)
[Tutorial a Youtube](https://youtu.be/rH6DJ_lbMm0)

## Còpia de seguretat de tot Moodle:

Si volem migrar el servei o recuperar-lo hem de pensar quina informació estem utilitzant a Moodle i on està guardada.

### Pensem...

![image](https://user-images.githubusercontent.com/110727546/212053271-9d1305d7-af49-41a4-b6d5-846816c6bb69.png)
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
### Directori de Moodle: 

El directori amb els fitxers necessaris per què funcioni Moodle. A la nostra pràctica és a /var/www/html/moodle probablement.

### Directori de dades:

El directori on es guarden fitxers pujats pels usuaris/es de Moodle, com les pràctiques. A la nostra pràctica probablement estarà a /home/moodledata.

### Base de dades:

A la base de dades estaran guardades  les dades de cursos, usuaris, puntuacions... 

La forma de fer backup de la base de dades canviarà segons la bbdd que utilitzem.

### Possar-ho tot al lloc una altra vegada:

Després de recuperar tota aquesta informació caldrà ficar-la al nou servidor i comprovar que tot funciona bé.

### Tutorial de migració de Moodle:

[Tutorial a Moodle](https://docs.moodle.org/all/es/Migraci%C3%B3n_de_Moodle)

# Activitat:

L'activitat, que realitzareu per parelles, es divideix en dues pràctiques diferents, cadascuna amb el mateix valor:

## A1 - Backup i restauració de curs:

- Fareu una còpia de seguretat del vostre curs elaborat a Moodle.
- 
![Selecció_144](https://user-images.githubusercontent.com/114162463/214880348-ed63e31c-0e5f-4e00-895c-0a88de49ea66.png)

![Selecció_145](https://user-images.githubusercontent.com/114162463/214880351-9161326e-b738-43e8-aba4-d27ad10e647a.png)

![Selecció_146](https://user-images.githubusercontent.com/114162463/214880353-a7019771-fe3f-4a9c-bc8a-e10db24079e3.png)

![Selecció_147](https://user-images.githubusercontent.com/114162463/214880356-97c0ca25-3312-4985-ba9e-4fc1e4fc97be.png)

![Selecció_148](https://user-images.githubusercontent.com/114162463/214880358-c6752355-91cc-4379-9510-3dad281d05b8.png)

- Passareu el fitxer al server del company/a de grup.

![Selecció_149](https://user-images.githubusercontent.com/114162463/214880360-179c0f74-be55-4bb5-89c9-bcdf7e4a23a0.png)

![Selecció_150](https://user-images.githubusercontent.com/114162463/214880361-a59d6512-83df-4014-a160-d70f3d54e0cd.png)

![Selecció_151](https://user-images.githubusercontent.com/114162463/214880363-e6994c04-4733-4ac2-8628-380879b7de78.png)

![Selecció_152](https://user-images.githubusercontent.com/114162463/214880366-318463ac-8a9c-4dd2-ae3d-4259a84792ca.png)

- Recuperareu el curs al seu Moodle.


- Comprovareu que tot funciona correctament.
- Aquest procés serà recíproc entre els dos companys/es de grup.
- Fareu un vídeo explicant el procés i mostrant el resultat de com a màxim 6 minuts.

## A2 - Migració de Moodle:

- Per aquesta pràctica necessitareu un servidor ubuntu net que serà el receptor del Moodle.
- Migrareu tota la informació d'un dels dos Moodles actuals (escolliu un) a la màquina ubuntu server nova.
- Fareu un vídeo explicant el procés i mostrant el resultat de com a màxim 6 minuts.

# Recursos per a fer vídeos:

- [Editor Kdenlive](https://kdenlive.org/es/).
- [Editor online de vídeo Cliupchamp](https://clipchamp.com/en/)
