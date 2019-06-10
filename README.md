# Pràctica de Tipologia i Cicle de Vida de les Dades
2na Part
## Autors
***Carles Maggi Gómez***   
***Joan A. Maggi Gómez***  
*THEMAGGICIANS* 
## Repositori per la  pràctica
practica 
## Programari utilitzat
R
Versió 3.5.2
R Studio
Version 1.1.463

## SO
Windows 10 64 Bits

## Objectiu i Descipció dels fitxers :

A partir de l'scraping fet a booking per obtenir dades sobre els hotes i opinions del clients, i despres de la generació de 3 datasets, crearem un sol dataset per treure infomració dels hotels .  
Entre altres :  
- Diferencia de qualitat del servei entre estiu i hivern
- Recomanar hotel segons , Nits de estada, Temporada, Grup, etc...
 
## Fitxers de PArtida

PArtim dels tres fitxers de la primera parts de la practica . La seva descripció és la següent :
### HotelsBarcelonaBooking :

**IdHotel :** BigInt que identifica de manera unívoca el hotel  
**Estrelles :** Int Número d'estrelles, en cas que n'hi hagi    
**Nota :** Float mitja de l'hotel    
**Nom :** String Nom de l'hotel  
**Link :** String Url de la pàgina de l'hotel   

### ComentarisXHotelsBarcelonaBooking :

**IdHotel :** BigInt Identifica de manera unívoca el hotel   
**IdIteració :** Int Primera part que identifica un comentari (iteració llista comentaris)   
**Index :** Int Segon part d'identificació de comentari (número de comentari dins la iteració)   
**NomHotel :** String Nom de l'hotel   
**Nota :** Float Nota que en qualifica el comentari de l'hotel   
**Comentari Postiu :** Text Comentari positiu si n'hi ha   
**Comentari Negatiu :** Text Comentari negatiu si n'hi ha   
**Data Comentari :** Date Data enregistrada del comentari PRAC 1 -Tipologia i Cicle de Dades   

### CategoriesXComentariBooking :

**IdHotel :** BigInt Identifica de manera unívoca el hotel   
**IdIteració :** Int Primera part que identifica un comentari (iteració llista comentaris)   
**Index :** Int Segon part d'identificació de comentari (número de comentari dins la iteració)   
**Categoria :** Text Categoria amb la que s'ha categoritzat el comentari  
