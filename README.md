# Moonbase Control: HttpResource

Zadanie z modułu Angular. Repozytorium zawiera kod startowy aplikacji Moonbase Control dla tej lekcji.

## Zadanie

Podłącz listę misji do lokalnego API.

W poprzedniej lekcji dane misji zostały przeniesione z komponentu do `MissionsService`. Nadal są jednak zapisane statycznie w kodzie aplikacji. Zastąp je danymi pobieranymi z przygotowanego API.

Student powinien:

- uruchomić przygotowany `json-server`,
- zastąpić statyczny sygnał z listą misji przez `httpResource`,
- pobrać dane z endpointu `/missions`,
- określić oczekiwany typ odpowiedzi jako `Mission[]`,
- ustawić pustą tablicę jako `defaultValue`,
- odczytać dane resource w szablonie za pomocą `value()`,
- upewnić się, że lista misji jest poprawnie wyświetlana,
- sprawdzić w zakładce Network, czy aplikacja wykonuje żądanie `GET /missions`.
💡 Dane misji powinny nadal być udostępniane komponentowi przez `MissionsService`. Komponent `Missions` nie powinien samodzielnie wykonywać komunikacji z API.

## Jak zacząć

1. Zrób fork tego repozytorium na swoje konto GitHub.
2. Sklonuj swój fork na komputer.
3. Zainstaluj zależności: `npm install`.
4. Uruchom aplikację: `npm start`.
5. Jeśli zadanie korzysta z danych z API, uruchom w drugim terminalu mock API: `npm run api`.

## Jak oddać zadanie

1. Zapisz zmiany w commicie i wypchnij je do swojego forka.
2. Otwórz Pull Request z forka do repozytorium `mate-academy/angular_http-resource`, do brancha `main`.
3. Platforma uruchomi review Twojego Pull Requesta.
