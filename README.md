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

## Objectiu i Descripció dels fitxers :

A partir de l'scraping fet a booking per obtenir dades sobre els hotels i opinions del clients, i després de la generació de 3 datasets, crearem un sol dataset per treure informació dels hotels .  
Entre altres :  
- Diferencia de qualitat del servei entre estiu i hivern
- Recomanar hotel segons , Nits de estada, Temporada, Grup, etc...
 
## Fitxers de Partida

Partim dels tres fitxers de la primera part de la pràctica . La seva descripció és la següent :
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

## Dataset de Treball

Després d'arrengar els fitxers, es crea el dataset següent  amb el que es comença a treballar.  

 **nomHotel            :** Factor w/ 82 levels. Nom de L'hotel     
 **notapersona         :** num . Nota donada per la persona al Hotel    
 **data                :** Date, format. Data del comentari    
 **estrelles           :** Ord.factor w/ 5 levels. Estrelles del Hotel  
 **notaHotel           :** num. Nota otorgada al hotel per Booking  
 **TipusHabitacio      :** Factor w/ 6 levels. Tipus d'habitació  
 **DuradaEstancia      :** Factor w/ 6 levels. Tipus d'estància   
 **Nits                :** num. Nits d'estància    
 **ProcedenciaComentari:** Factor w/ 2 levels. Procedència del comentari  
 **TipusViatge         :** Factor w/ 3 levels. Tipus de Viatge   
 **Acompanyament       :** Factor w/ 5 levels. Tipus Acompanyament   
 **ViajaConMascota     :** Factor w/ 2 levels. Si viatge amb mascota  
 **Season              :** Factor w/ 4 levels. Temporada del Viatge  
 
 ## Entregables
 
 ** El codi en RDM és a  [Neteja.Rmd](https://github.com/joanmaggigo/practica2/blob/master/Neteja.Rmd)  
 ** El fitxer docx del codi RDM és a [Neteja.docx](https://github.com/joanmaggigo/practica2/blob/master/Neteja.docx)  
 ** El Document entregable és a [Carles Maggi - Joan Maggi - Practica 2](https://github.com/joanmaggigo/practica2/blob/master/Entregable/Carles%20Maggi%20-%20Joan%20Maggi%20-%20Practica%202.docx)  
 ** El dataset net és a [data_netejada.csv](https://github.com/joanmaggigo/practica2/blob/master/CSV/data_netejada.csv)  
 