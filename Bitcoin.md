# Bitcoin Investing

## Basic info

- ISO code: *XBT*, BTC - potocznie
- units:
  - 100 000 000 satoshi = 1 bitcoin;
    - 1 satoshi = 10^-8 BTC (najmniejsza jednostka)
  - 1 mBTC = 0,001 BTC;
  - 1 μBTC = 0,000001 BTC
- cryptocurrency
- introduced in 2009 by "Staoshi Nakamoto" (person/group)
- handled by OpenSource SW & peer-to-peer network

remarks:
- w odróżnieniu od 'fiducjarnych' walut - nie opiera się na zaufaniu do emitenta centralnego;
- BTC używa zdecentralizowanej bazy danych rozprowadzonej między węzłami peer-to-peer
- pozwala na anonimowe posiadanie własności oraz jej transfery
- opiera sięna transferze kwot między rachunkami publicznymi przy użyciu "kryptografii klucza publicznego"
  - wszystkie tranzakcje są publiczne i przechowywane w rozproszonej bazie danych

- Każdy user ma swój portfel zawierający dowolną liczbę par kluczy kryptograficznych

## Transakcje

- Bitmonety zawierają klucz publiczny (adress) aktualnego posiadacza
- kiedy user A transferuje ilość do B, to A rezygnuje z posiadania dodając klucz publiczny (adres) B do tych monet podpisując je własnym kluczem prywatnym
  - reszta sieci sprawdza poprawność zastosowanych w tranzakcji podpisów cyfrowych oraz ilości monet przed jej zaakceptowaniem

## Blockchain

- dowolna tranzakcja rozesłana do innych węzłów nie jest 'oficjalna' nim nie zostanie potwierdzona na wspólnie utrzymywanej liście (z timestamp's) wszystkich znanych transakcji "łańcuch bloków"

----

## Ekonomia

- wymiana tradycyjnej waluty na BTC odbywa się na 'kryptogiełdach'
- całkowita liczba bitmonet dąży asymptotycznie do 21 milionów
- legalność:
  - 'co nie jest zakazane uznaje się za legalne'
- obecnie (13.06.2021) cena to około 37tyś $ / BTC, (137 tyś zł)
- obrót jest śledzony przez KAS (Krajowa Administracja Skarbowa)
- powoli pojawiają się ETF-y z ekspozycją na BTC
- wymiana walut tradycyjnych na monety jest zwolniona z VAT

----

## Practical tutorial

- based on https://www.youtube.com/watch?v=E9-olgNvUwI
- Bitcoin nie można zamknąć, bo opiera się na sieci p2p
- wykonując tranzakcja - jest ona uwierzytelniana przez górników
  - dostają za to małą prowizję tranzakcji
- każdy ma klucz publiczny
  - taki nr konta (można mieć wiele kluczy publicznych)

### Proces tranzakcji

1. daję znać do sieci, że chce wykonać tranzakcję
2. górnicy potwierdzają, że tranzakcja może być wykonana i że jest poprawna

### Od czego zależy kurs

- czy rządy utrudniają / ułatwiają korzystanie z niego
- czy podmioty, co mają dużo bitcoinów (zwłaszcza ze starych czasów) nagle rzucą dużą podaż na rynek
  - wtedy kurs podlega silnym wahaniom

### Strategie

- Traderska - day trading
- old-fashioned - regularnie sobie dokupujemy kolejne ilości BTC

### Serwisy - giełdy krypto

- bitcoin.de
  - fajne do zakupu w euro
- coinbase
- bitbay

większość giełd wymaga dokładnej weryfikacji tożsamości

po kupnie:
    - mamy klucz publiczny - taki nasz nr konta
        - można go samemu wygenerować (na stronach bitadress)
        - można mieć wiele kluczy publicznych
    - dodatkowo mamy klucz prywatny
        - w przypadku portfeli papierowych można je wygenerować samodzielnie
    * podczas wypłaty bitcoina z giełdy nie jest potrzebny klucz prywatny - wystarczą nam dane do logowania
        - ale trzymanie BTC na giełdzie nie jest bezpieczne (ataki hakerskie!)

- generalnie BTC należy wysłać na swój portfel BTC:
  - 'portfel' to klucz publiczny zabezpieczony kluczem prywatnym

Rodzaje portfeli:
    1. na giełdzie (niebezpieczny)
    2. mobilny
        - np aplikacja na tel (poleca 'Coinomi') lub na komp
        - waluta jest zabezp hasłem - względnie bezpieczne
    3. portfel papierowy
        1. wchodzisz na bitadress
            - na specjalnej stronie ręcznie tworzymy klucz publiczny i klucz prywatny
        2. zapisujemy na kartce / drukujemy
        3. na ten klucz publiczny przesyłamy kase w BTC
        4. by móc wypłacić kasę musimy podać nasz klucz prywatny w app np w "Coinomi"
    4. sprzętowe portfele np "Leger"
        - podłączamy jako USB, wpisujemy PIN i tam trzymamy kryptowalutę

----

## My strategy

- read additional sources:
  - https://bitcoin.pl/bitcoin-jak-zaczac/
  - https://www.xtb.com/pl/bitcoin-kb
  - https://www.xtb.com/pl/bitcoin-jak-zaczac-kb
  - https://bitcoin.pl/
  - https://e-kursy-walut.pl/kurs-bitcoin/
  - https://www.parkiet.com/Kryptowaluty/306119987-Wieloryby-kupuja-a-bitcoin-pisze-kolejny-rozdzial-monetarnej-historii.html
  - https://bitcoin.org/pl/
  - https://www.cmcmarkets.com/pl-pl/edukacja-kryptowaluty/czym-jest-bitcoin

- start with very low amount's
  - 100 zł at each cryptocurrency-stock is fine
  - over 1 week observe the market
  - when everything is fine - cash out the money

- general rules:
  - avoid invest more than 5% into cryptocurrency
  - always invest 'not quickly need' money
  
  
----

## update 09.07.2021

- założyłem konto na bitbay.net
- czekam na drugi etap weryfikacji
- informacje ogólne:
    - "porfel bitcoin" - kawałek sieci Bitcoin, do której masz dostęp tylko Ty. Musisz znać klucz i adres portfela.
    - "adres portfela" - unikalny ciąg znaków, który jest przypisany tylko do Twojego portfela.
    - "klucz portfela" - unikalne hasło, które umożliwia dostęp do tego portfela.
        - przykładowy adres i hasło portfela:
            - przykładowy adres: "1CC3X2gu58d6wXUWMffpuzN9JAfTUWu4Kj"
            - przykładowy klucz prywatny: "5Kb8kLf9zgWQnogidDA76MzPL6TsZZY36hWXMssSzNydYXYB9KF"
- linki przydatne:
    - ilość transakcji w sieci bitcoin: https://www.blockchain.com/charts/n-transactions?timespan=all
    - tabela opłat bitbay: https://bitbay.net/pl/tabela-oplat
    - bitbay - kontakt: https://bitbay.net/pl/pomoc/moje-konto/jak-sie-z-nami-skontaktowac
- ToDo:
    1. zaczekaj na wynik weryfikacji 2giego etapu
    2. aktywuj weryfikacje google authenticator https://bitbay.net/pl/pomoc/moje-konto/jak-korzystac-z-uwierzytelniania-dwuskladnikowego-google-authenticator
    3. kup za 100zł
    4. poczytaj kursy - tutaj: https://academy.bitbay.net/
    5. kursy od mBank https://www.mbank.pl/indywidualny/inwestycje/zanim-zaczniesz/szkolenia-gieldowe-online/
