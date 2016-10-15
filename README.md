#DomacaZadaca0

#JMBAG
{0036496896}

#Pitanje {1}
Nakon što smo dodali class library kao referncu, PDB i dll datoteke
su se pojavile u Debug folderu. Ako se one maknu i program se ponovo porene.
Datoteke se ponovo generiraju.
Za pravino poretanje progrma portrebani su filovi u Release ili Debug folderu.

#Pitanje {2}
Promjena se ne registrira, pošto se library nije kopirao u folder programa.

#Pitanje {3}
Pero: Hello World

#Pitanje {4}
Dodan je PeroClassLibrary.dll u folder

#Pitanje {5}
Aplikacija radi pošto je dll premješten u folder progrma.
Reference lista prikazuje stari dll no nije odabran, i nije ga moguce odabra.
No buildanje je i dalje moguce. Pretpostavljam da se program orijentira na dll u
datoeci programa.

#Pitanje {6}
Ako se zbriše NodaTime i builda se aplikacija, dll se ponovo skine, te se
program normalno builda.
