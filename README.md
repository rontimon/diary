# HealthDiary Sovellus

Tervetuloa LongWay-sovellukseen! Tämä README.md sisältää kaiken tarvittavan tiedon sovelluksesta, mukaan lukien käyttöliittymän kuvakaappaukset, linkit sovellukseen, ja tietokannan kuvaus.

## Kuvakaappaukset

<img width="1436" alt="Screenshot 2024-03-17 at 22 05 32" src="https://github.com/rontimon/diary/assets/122264249/a2ae9d59-f0aa-4c21-a6c6-325bc0501ada">

<img width="1436" alt="Screenshot 2024-03-17 at 21 34 11" src="https://github.com/rontimon/diary/assets/122264249/697d421a-6c9d-45e8-b413-537460bdd3d9">

<img width="1436" alt="Screenshot 2024-03-17 at 21 34 21" src="https://github.com/rontimon/diary/assets/122264249/f81d81f9-cb80-4a1f-b9c0-cccdfc950351">

<img width="1436" alt="Screenshot 2024-03-17 at 21 34 30" src="https://github.com/rontimon/diary/assets/122264249/d70197a9-0937-4ecc-9c04-3760e5de01e0">

<img width="1436" alt="Screenshot 2024-03-17 at 21 34 46" src="https://github.com/rontimon/diary/assets/122264249/23d43d1c-d5d2-4455-82a7-c66c853c4e56">

<img width="1436" alt="Screenshot 2024-03-17 at 21 35 08" src="https://github.com/rontimon/diary/assets/122264249/ee86dc97-c252-40d4-a0ae-f7e0334720a3">

<img width="1436" alt="Screenshot 2024-03-17 at 21 35 17" src="https://github.com/rontimon/diary/assets/122264249/d683680e-ec1a-497a-ad3e-d825357ce9f4">


## Linkit

- **Front-end Sovellus**: [Linkki julkaistuun sovellukseen](#)
- **Back-end Sovellus/API**: [Linkki käytössä olevaan back-end-sovellukseen/APIin](#)
- **API Dokumentaatio**: [Linkki API-dokumentaatioon](#)

## Tietokannan Kuvaus

Sovellus käyttää `HealthDiary` nimistä tietokantaa, joka sisältää seuraavat taulut:

- `Users`: Käyttäjän perustiedot
- ( user_id, username, password, email, created_at ja user_level )

- `TrainingDiary`: Treenipäiväkirja
- ( diary_id, user_id, entry_date, mood, training_time, notes, goals ja created_at )


## Toiminnallisuudet

Toteutetut toiminnallisuudet sisältävät:

1. **Uuden käyttäjän luominen**
2. **Sisäänkirjautuminen**
3. **Päiväkirjamerkinnän lisääminen**
4. **Aikaisempien päiväkirjamerkintöjen hakeminen**
5. **Aikaisempien päiväkirjamerkintöjen muokkaaminen**
6. **Aikaisemman päiväkirjamerkinnän poistaminen**
7. **Uloskirjautuminen**

## Tiedossa Olevat Bugit/Ongelmat

*Tässä osiossa mainitaan mahdolliset tiedossa olevat bugit tai ongelmat.*

## Referenssit

*Tässä osiossa mainitaan käytetyt tutoriaalit, grafiikkakirjastot ja muut referenssit.*

- Sovelluksen tyylittelyssä ja logon suunnittelussa on käytetty apuna ChatGPT:tä
