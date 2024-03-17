# HealthDiary Sovellus

Tervetuloa LongWay-sovellukseen! Tämä README.md sisältää kaiken tarvittavan tiedon sovelluksesta, mukaan lukien käyttöliittymän kuvakaappaukset, linkit sovellukseen, ja tietokannan kuvaus.

## Kuvakaappaukset



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
