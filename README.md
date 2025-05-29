# Tile-classification

## Opis zadatka
Zadatak podrazumeva razvoj sistema za vizuelnu inspekciju crepova, koji će pomoći u proceni njihovog kvaliteta. Sistem se sastoji iz dva ključna dela:

- **Ekstrakcija crepa sa slike:** Potrebno je napisati funkciju koja prima originalnu sliku kao ulaz, izdvaja crep i generiše novu sliku dimenzija 1280x960 piksela, gde je crep centriran na crnoj pozadini.
- **Klasifikacija kvaliteta:** Na osnovu poređenja sa idealnim crepom (koji se nalazi u posebnom folderu), funkcija treba da proceni:
da li je testirani crep odgovarajuće veličine,
da li mu nedostaju delovi.

Klasifikacija je binarna:
- **PK:** prva klasa koja predstavlja zadovoljavajući kvalitet
- **LOM:** nezadovoljavajući kvalitet

## Rezultati klasifikacije

Rezultati klasifikacije se čuvaju u CSV fajlu koji sadrži sledeće kolone:
- ime slike prednje strane,
- ime slike zadnje strane,
- oznaka klase (PK ili LOM).
