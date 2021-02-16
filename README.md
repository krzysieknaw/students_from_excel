## students_from_excel

Twoim zadaniem jest implementacja narzędzia wspierającego zarządzanie ocenami uczniów.

Oceny uczniów gromadzone są w plikach Excelowych. W każdej zakładce gromadzone są informacje o osobnym przedmiocie. Zakładki mają takie same nazwy jak nazwy przedmiotów.


Twoim zadaniem jest implementacja:
1. funkcji calculateAverageForSubject(subject) wyliczającej średnią ocen dla danego przedmiotu
2. funkcji calculateAverageForStudent(student) wyliczającej średnią ocen ze wszystkich przedmiotów dla danego studenta
3. funkcji calculateAverageForAllSubjects() wyliczającej średnią ocen (jedna wartość) wszystkich uczniów dla wszystkich przedmiotów z generacją wykresu słupkowego średnich posortowanego wg średnich z tych przedmiotów (a więc chcemy zobaczyć na osi X przedmioty i wartości średnich ocen)
4. funkcji generateStudentRankingForSubject(subject) wyliczającej ranking uczniów w danym przedmiocie. Ranking oczywiście ma być wyznaczany na podstawie ocen, najwyższe oceny na początku
5. funkcji generateStudentRankingForAllSubjects() wyliczającej ranking uczniów na podstawie średniej ocen ze wszystkich przedmiotów, najlepsi studenci na początku


Podczas implementacji należy założyć, iż w podanym pliku wejściowym:
- ilość uczniów może się zmienić (nie można zakładać stałych zakresów danych)
- listy uczniów dla poszczególnych przedmiotów mogą się od siebie różnić tzn. że student może mieć inne miejsce na liście w zależności od przedmiotu.
