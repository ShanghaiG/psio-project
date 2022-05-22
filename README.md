 

Przetwarzanie sygnałów i obrazów 

Laboratorium 

Studia Niestacjonarne 

 

 

Projekt 

 

System do obliczania wieku i warunków wzrostu drzewa na podstawie słojów rocznych 

 

 

 

 

 

 

 

 
Autorzy:
Bartłomiej O. 
Daniel W. 
Ksawery S.

 

 

Główne cechy systemu: 

Program oblicza wiek drzewa na podstawie liczby par słojów rocznych (para słojów, czyli jasny - przyrastający na wiosnę i ciemny - przyrastający na koniec lata). 

Program identyfikuje warunki wzrostu drzewa na podstawie przekroju poprzecznego pnia drzewa (szersze słoje oznaczają warunki sprzyjające, węższe słoje - warunki niesprzyjające). 

Program potrafi zidentyfikować występujące anomalie jak np. ślady po przebytych pożarach lub inne ubytki na przekroju poprzecznym pnia drzewa. 

 

Zestaw narzędzi technologicznych: 

Językiem, w którym zostanie napisany program, będzie Python. 

Program będzie korzystał z bibliotek takich jak cv2, pickle, numpy as np., OpenCV, skimage.  

 

Etapy tworzenia oprogramowania: 

Zebranie zdjęć przekrojów poprzecznych drzew - dębu, sosny zwyczajnej i drzewa akacjowego. 

Zebranie informacji o średnich przyrostach grubości pnia drzewa. 

Opracowanie funkcji obliczającej wiek drzewa na podstawie ilości par słojów. 

Opracowanie funkcji, która na podstawie szerokości słojów określi czy siedlisko, na którym znajduje się dane drzewo sprzyja jego występowaniu. 

Opracowanie funkcji określającej wystąpienie anomalii (np. ubytki po pożarach) na przekroju poprzecznym pnia drzewa. 

 

 

 

Ograniczenia modelu: 

Ograniczenie do trzech gatunków drzew - dąb, sosna zwyczajna oraz drzewo akacjowe. 

Ponieważ nie jesteśmy w stanie dokładnie określić zjawisk powiązanych z:  

siedliskiem (zasobność gleby, uwilgotnienie),  

klimatem (temperatura, opady, cykliczność zjawisk)  

czynnikami losowymi (pożar, powódź, susza, gradacja szkodników) 

spróbujemy określić czy dane drzewo rosło w sprzyjających dla jego gatunku warunkach (na podstawie szerokości słojów rocznych).  
