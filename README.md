
Meli
LATVIJAS 38. INFORMĀTIKAS OLIMPIĀDE
NOVADA OLIMPIĀDE – 2025. GADA 14. JANVĀRIS
JAUNĀKĀ (8. - 10. KLAŠU) GRUPA
Patiesības teicēji un meļi
Kādā ciemā dzīvo 𝑁 iedzīvotāji, kas sanumurēti ar naturāliem skaitļiem no 1 līdz 𝑁 pēc kārtas.
Katrs ciemata iedzīvotājs ir vai nu patiesības teicējs, kas vienmēr saka taisnību, vai arī melis, kas visu
laiku melo.
Etnogrāfam Rihardam ir izdevies savākt ciema iedzīvotāju 𝑀 izteikumus vienam par otru. Visus
izteikumus Rihards ir pierakstījis formā:
„Ciema iedzīvotājs 𝑖 apgalvo, ka iedzīvotājs 𝑗 ir patiesības teicējs.“ vai
„Ciema iedzīvotājs 𝑖 apgalvo, ka iedzīvotājs 𝑗 ir melis.“
Šajos apgalvojumos 1 ≤ 𝑖, 𝑗 ≤ 𝑁 un 𝑖 ≠ 𝑗.
Rihards vēlas noskaidrot, kāds ir lielākais iespējamais meļu skaits ciema iedzīvotāju vidū.
Piemēram, ja ciemā ir astoņi iedzīvotāji un Rihards ir pierakstījis šādus piecus izteikumus:
• Ciema iedzīvotājs 1 apgalvo, ka iedzīvotājs 2 ir patiesības teicējs.
• Ciema iedzīvotājs 2 apgalvo, ka iedzīvotājs 3 ir melis.
• Ciema iedzīvotājs 5 apgalvo, ka iedzīvotājs 6 ir melis.
• Ciema iedzīvotājs 7 apgalvo, ka iedzīvotājs 3 ir patiesības teicējs.
• Ciema iedzīvotājs 8 apgalvo, ka iedzīvotājs 5 ir patiesības teicējs.
, tad meļu skaits ciemā ir, augstākais, pieci. Tie var būt, piemēram, iedzīvotāji ar numuriem 3, 4,
5, 7 un 8. Ievērojiet, ka šajā piemērā neviens izteikums neraksturo iedzīvotāju nr. 4.
Uzrakstiet datorprogrammu, kas dotai izteikumu kopai nosaka, kāds lielākais meļu skaits var būt
ciemā!
Ievaddati
Ievaddatu pirmajā rindā doti divi veseli nenegatīvi skaitļi – ciema iedzīvotāju
skaits 𝑁(1 ≤ 𝑁 ≤ 2 ⋅ 10
5
) un izteikumu skaits 𝑀(0 ≤ 𝑀 ≤ 2 ⋅ 10
5
).
Katrā no nākamajām 𝑀 ievaddatu rindām dots viena izteikuma apraksts – trīs veseli nenegatīvi
skaitļi: ciema iedzīvotāja, kurš izteicis apgalvojumu, numurs 𝑖 (1 ≤ 𝑖 ≤ 𝑁), iedzīvotāja, par kuru
izteikts apgalvojums, numurs 𝑗 (1 ≤ 𝑗 ≤ 𝑁,𝑖 ≠ 𝑗) un 1, ja apgalvojums ir „ir patiesības teicējs“, vai
0, ja apgalvojums ir „ir melis“.
Starp katriem diviem blakus skaitļiem ievaddatos ir tukšumzīme.
Izvaddati
Izvaddatu vienīgajā rindā jāizvada vesels nenegatīvs skaitlis – lielākais iespējamais meļu skaits
starp ciema iedzīvotājiem.
Ierobežojumi un prasības
Atmiņas apjoma un izpildes laika ierobežojumus skatīt sacensību sistēmā uzdevuma sadaļā
„Formulējums“ ⇒ „Tehniskā informācija“.
Klases vārds valodā Java rakstītam risinājumam: Meli
Piemēri
Ievaddati Izvaddati Piezīme
8 5
1 2 1
2 3 0
5 6 0
7 3 1
8 5 1
5 Uzdevuma tekstā
dotais piemērs
Ievaddati Izvaddati
5 3
3 1 1
5 4 1
3 2 0
4
Meli 1(2)
Meli
1. apakšuzdevuma testu ievaddati
Ievaddati
10 20
9 6 0
7 3 1
2 8 1
4 7 0
10 2 1
1 9 1
5 8 1
4 8 0
3 1 0
4 2 0
1 10 0
5 3 1
6 4 0
1 4 1
5 7 1
5 10 1
3 8 1
10 8 1
7 10 1
9 8 0
Ievaddati
20 24
11 8 1
12 1 0
18 10 0
6 4 0
10 7 1
4 1 0
17 20 1
9 15 1
17 7 0
15 5 1
6 18 1
7 1 0
8 13 1
16 18 1
2 19 0
3 18 0
14 7 0
17 16 1
2 12 1
1 20 1
16 12 0
5 9 1
4 14 0
17 10 0
Ievaddati
30 32
9 13 0
4 9 0
8 24 0
19 27 0
6 25 0
27 26 0
1 13 0
27 1 1
9 7 0
30 22 0
18 25 0
13 4 1
28 30 0
12 24 0
23 12 1
1 4 0
28 11 0
2 21 1
23 2 0
11 15 0
17 3 1
28 22 1
19 1 0
14 13 0
7 13 1
1 7 0
22 11 0
18 6 1
8 29 0
5 10 1
3 16 1
29 2 1
Apakšuzdevumi un to vērtēšana
Nr. Testu apraksts Punkti
1. Uzdevuma tekstā dotie trīs testi 2
2. 𝑁 ≤ 20 8
3. Katrs iedzīvotājs izsaka ne vairāk kā vienu apgalvojumu. 12
4. Visi apgalvojumi ir „ir melis“. 33
5. Bez papildu ierobežojumiem 45
Kopā: 100
Meli 2(2)
