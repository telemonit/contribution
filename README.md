
## Teleoperator [Contribution](http://contribution.telemonit.com) [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/MENU.md)



## Rozwiązanie [telemonit.com](http://www.telemonit.com)

+ [telemonit.com](http://www.telemonit.com)
+ [dokumentacja](http://docs.telemonit.com)
+ [logo](http://logo.telemonit.com)
+ [roadmap](http://roadmap.telemonit.com)
+ [identyfikator](http://identity.telemonit.com)
+ [współpraca](http://współpraca.telemonit.com)


## [WSPÓŁPRACA](http://contribution.telemonit.com) zawsze jest mile widziana:

+ Znalazłeś [problem lub błąd](https://github.com/cameramonit/docs/issues/new)?
+ Czy chcesz [poprawić artykuł](https://github.com/cameramonit/docs/edit/main/README.md)?
+ Czy interesuje Cię współpraca przy innych [projektach git](https://github.com/cameramonit/)?
+ Czy masz co dołożyć lub rozmawiać? [Otwórz pull request](https://github.com/cameramonit/docs/pulls) lub [opisz problem](https://github.com/cameramonit/docs/issues).

## [CONTRIBUTIONS](http://contribution.telemonit.com) are always welcome: [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/CONTRIBUTION.md)

+ did you found an [Issue or Mistake](https://github.com/cameramonit/contribution/issues/new)?
+ do you want to [improve](https://github.com/cameramonit/contribution/edit/main/README.md) the article?
+ are you interested do join another [git projects](https://github.com/cameramonit/)?
+ have something to contribute or discuss? [Open a pull request](https://github.com/cameramonit/contribution/pulls) or [create an issue](https://github.com/cameramonit/contribution/issues).

## Star History [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/STAR.md)

[![Star History Chart](https://api.star-history.com/svg?repos=cameramonit/contribution&type=Date)](https://star-history.com/#cameramonit/contribution&Date)

 [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/STRUCTURE.md)

### Inicjalizacja projektu React.js

1. **Zainstaluj Node.js i npm**: Najpierw upewnij się, że masz zainstalowany Node.js i npm.
2. **Utworzenie nowego projektu React**:
   ```sh
   git clone 
   cd www
   npx create-react-app .   
   npm start
   ```


### Struktura Folderów

Upewnij się, że Twoje katalogi mają poniższą strukturę:

```
teleoperator-app/
├── backend/
│   ├── Dockerfile
│   ├── package.json
│   ├── package-lock.json
│   ├── server.js
│   └── ...inne_pliki_backendu...
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── InstallerList.js
│   │   ├── Marketplace.js
│   │   ├── Dashboard.js
│   │   └── ...
│   ├── App.js
│   ├── App.css
│   └── index.js
├── Dockerfile
├── docker-compose.yml
├── package.json
├── package-lock.json
├── public/
└── ...inne_pliki_frontendu...
```

## Node Install [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/install/NODE.md)



Po zapisaniu pliku `package.json`, uruchom następującą komendę w terminalu, aby zainstalować wszystkie zależności:

```sh
cd src
```

```sh
npm install
```

To upgrade all the dependencies in your `package.json` to their latest versions, you can follow these steps:

### Using npm (version 5.2 or higher)

1. **Install `npm-check-updates`:**
   First, you need to install the `npm-check-updates` tool globally. This tool helps you to easily upgrade the dependencies in your `package.json` to the latest versions.

   ```sh
   sudo npm install -g npm-check-updates
   ```

   ```sh
   sudo npm install -g npm@10.8.1
   ```
2. **Update `package.json` Dependencies:**
   Once `npm-check-updates` is installed, run the following command to upgrade your `package.json` dependencies:

   ```sh
   ncu -u
   ```

   The `ncu -u` command checks your `package.json` file for any outdated dependencies and updates them to the latest versions.

3. **Install Updated Dependencies:**
   After updating the `package.json` file, install the updated packages using:

   ```sh
   npm install
   ```

### Using yarn

If you prefer to use `yarn`, you can update all dependencies to their latest versions as follows:

1. **Upgrade Dependencies:**
   Run the following command to upgrade all the dependencies listed in your `package.json` file:

   ```sh
   yarn upgrade --latest
   ```

### Manual Method

Alternatively, you could manually update the `package.json` file and then install the dependencies:

1. **Update Versions in `package.json`:**
   Manually change the version numbers of the dependencies in your `package.json` file to the latest versions. You can look up the latest versions on npm's website or by running:

   ```sh
   npm show <package-nameversion
   ```

2. **Install Dependencies:**
   After updating the `package.json` file, run the following command to install the updated packages:

   ```sh
   npm install
   ```

### After Upgrading

After upgrading your dependencies, it's a good practice to:

1. **Check for breaking changes:**
   Review the changelogs of the dependencies to be aware of any breaking changes that might require code modifications.

2. **Test your application:**
   Thoroughly test your application to ensure everything works correctly with the updated dependencies.

3. **Lockfile Update:**
   If you use a lockfile (`package-lock.json` or `yarn.lock`), make sure it is updated by the package manager.

Following these steps should help you successfully upgrade all the packages in your `package.json` to their newest versions.



[Deployment | Create React App](https://create-react-app.dev/docs/deployment/)

Static Server

For environments using [Node](https://nodejs.org/), the easiest way to handle this would be to install [serve](https://github.com/vercel/serve) and let it handle the rest:
```bash
npm install -g serveserve -s build
```

The last command shown above will serve your static site on the port **3000**. Like many of [serve](https://github.com/vercel/serve)’s internal settings, the port can be adjusted using the `-l` or `--listen` flags:
```bash
serve -s build -l 4000
```

Run this command to get a full list of the options available:
```bash
serve -h
```

## Python Install [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/install/PYTHON.md)

Zainstaluj biblioteki Pythona, jeśli jeszcze tego nie zrobiłeś. Możesz to zrobić używając `pip`:

```bash
py -m pip install --upgrade pip
py -m pip install --upgrade setuptools
py -m pip install --upgrade wheel
py -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

```bash
py -m pip install -r requirements.txt
```

## Uruchamianie kontenerów [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/install/DOCKER.md)

Pliki `Dockerfile` i `docker-compose.yml` umożliwiaj konteneryzację aplikacji React.js (src) i backendu Express, co sprawia, że aplikacja staje się bardziej przenośna i łatwa do wdrożenia. 
Dzięki Docker i Docker Compose możesz uruchomić złożone środowiska wielokontenerowe jedną komendą, co znacznie upraszcza zarządzanie i skalowanie aplikacji.



```sh
cd backend
docker build -t .
```


```sh
cd ..
```

```sh
cd src
docker build .
```

### Zbuduj i uruchom kontenery za pomocą Docker Compose:

```sh
docker compose up --build
```

### Debugowanie
Jeśli wystąpią problemy, sprawdź logi za pomocą:

```sh
docker compose logs
```

### Zatrzymywanie kontenerów

```sh
docker compose down
```


If you need your build to connect to services running on the host, you can use the special host-gateway value for --add-host. In the following example, build containers resolve host.docker.internal to the host's gateway IP.
```sh
docker build --add-host host.docker.internal=host-gateway .
```

## TODO [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/TODO/DEV.md)

Na tym etapie stworzyliśmy podstawową makietę aplikacji webowej z wykorzystaniem technologii React.js, która jest łatwa do modyfikacji.
Od inicjalizacji projektu, przez utworzenie podstawowej struktury komponentów, aż po integrację z symulowanym API (MSW).



### Podsumowanie i Następne Kroki

[ ] **Skalowanie**: W miarę potrzeb dodawaj więcej komponentów, takich jak formularze rejestracyjne, kalendarze dostępności, panele administracyjne itd.
[ ] **Backend**: Rozważ implementację rzeczywistego backendu z REST API lub GraphQL.
[ ] **Autoryzacja**: Zaimplementuj system autoryzacji, np. OAuth2.
[ ] **Testowanie**: Dodaj testy jednostkowe i integracyjne, korzystając np. z Jest i React Testing Library.
[ ] **Responsywność**: Dopracuj stylizację, aby aplikacja działała dobrze na różnych urządzeniach.



Poniżej przedstawiam plan rozwoju projektu.

### 1. Skalowanie i Nowe Funkcjonalności

Dodanie bardziej kompleksowych komponentów takich jak:
- **Formularze Rejestracyjne**: Komponenty z walidacją np. z wykorzystaniem `formik` do łatwego zarządzania formularzami w React.js.
- **Kalendarze Dostępności**: Implementacja bardziej zaawansowanych kalendarzy z możliwością zarządzania wolnym czasem instalatorów, np. z użyciem bibliotek takich jak `react-big-calendar`.
- **Panele Administracyjne**: Widoki i funkcje dla administratorów, tj. zarządzanie użytkownikami, zamówieniami i produktami.

### 2. Backend Integration

Ciężar logiki biznesowej i przechowywania danych przenieś na backend:
- **API REST**: Zaimplementuj prawdziwe API, preferencyjnie w Node.js z Express, Django, czy innej technologii, z której korzystasz.
- **GraphQL**: Alternatywnie użyj GraphQL do bardziej elastycznego zarządzania danymi.
- **Serwery**: Hostuj backend na platformach takich jak AWS, Google Cloud, Heroku.

### 3. Uwierzytelnianie i Autoryzacja

Zaimplementuj bezpieczne logowanie i autoryzowanie użytkowników:
- **OAuth2**: Integracja z popularnymi providerami tożsamości (Google, Facebook).
- **JWT**: Użyj JSON Web Tokens do bezpiecznego przekazywania informacji o autoryzacji.

## TODO [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/TODO/TEST.md)

### 4. Testowanie i Utrzymanie Jakości

Wprowadź narzędzia do testowania kodu, jego analizy i ciągłej integracji:
- **Jest i React Testing Library**: Testuj komponenty oraz interakcje.
- **ESLint i Prettier**: Zapewniaj spójność kodu i szybkie wyłapywanie błędów.
- **Ciągła Integracja (CI)**: Ustaw np. w GitHub Actions, CircleCI, TravisCI.

### 5. Ulepszanie Stylizacji i Responsywności

Dostosuj aplikację do różnych urządzeń i ulepsz jej wygląd:
- **CSS-in-JS**: Rozważ użycie bibliotek takich jak `styled-components` lub `emotion`.
- **Responsywność**: Zapewnij, aby Twoje komponenty dobrze wyglądały zarówno na urządzeniach mobilnych, jak i desktopowych z pomocą `flexbox`, `grid` oraz media queries.

## TODO [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/TODO/DEVOPS.md)


### 6. Monitorowanie i Optymalizacja

Monitoruj działanie aplikacji i poprawiaj jej wydajność:
- **Google Analytics**: Śledź ruch i zachowania użytkowników.
- **Logi i Monitoring**: Zaimplementuj systemy logowania błędów i monitorowania wydajności (np. Sentry, New Relic).
- **Optymalizacja Wydajności**: Przeprowadź optymalizację komponentów React używając technik takich jak lazy loading, memoization.

### 7. DevOps i Automatyzacja

Automatyzacja procesów wdrożeniowych zapewni częste i pewne wdrożenia:
- **Docker i Kubernetes**: Zautomatyzuj wdrożenia aplikacji przy użyciu konteneryzacji.
- **CI/CD**: Implementacja potoków CI/CD do automatyzacji buildów, testów i wdrożeń.

## References [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/REFERENCES.md)

+ [teleoperator-app projects](https://github.com/teleoperator-app)
+ Build ENVIRONMENT on yaml[apitee/python: www.apitee.com](https://github.com/apitee/python)
+ Build Docker image based on url
+ Automated scripts [www.apimacro.com](https://www.apimacro.com/)
+ DSL language [apidsl.com](https://apidsl.com/)

## Sources [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/SOURCES.md)

+ [How to Run a Python Script using Docker?](https://www.geeksforgeeks.org/how-to-run-a-python-script-using-docker)
+ [dockerfile - How to run Python command in Docker and capture output and](https://stackoverflow.com/questions/62563856/how-to-run-python-command-in-docker-and-capture-output-and-set-it-to-environment)
+ [Build variables | Docker Docs](https://docs.docker.com/build/building/variables)
+ [Docker file for running a Python program with parameters](https://stackoverflow.com/questions/57528713/docker-file-for-running-a-python-program-with-parameters)
+ [How to write a great Dockerfile for Python apps - PyBootcamp](https://www.pybootcamp.com/blog/how-to-write-dockerfile-python-apps)
+ [python - How do I map ports inside the Dockerfile? - Stack Overflow](https://stackoverflow.com/questions/76595802/how-do-i-map-ports-inside-the-dockerfile)
+ [Dockerfile reference](https://docs.docker.com/reference/dockerfile/)

## [telemonit.com] to inteligentna głosowa komunikacja z wieloma kamerami [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/ABOUT.md)

Wyobraź sobie system monitoringu, który nie tylko rejestruje obraz, ale również rozumie go i komunikuje się z Tobą. 
[telemonit.com] rozmawia, analizuje i powiadamia wtedy gdy potrzebujesz, eliminując fałszywe alarmy.

- Intuicyjna obsługa systemu monitoringu
- Głosowa szybkość dostęp do informacji o zdarzeniach
- Elastyczność w wyborze metody komunikacji
- Rozbudowa systemu o dziesiątki kamer
- Najwyższy poziom bezpieczeństwa danych
- Zgodny z wytycznymi Artificial Intelligence Act

Odkryj nową erę monitoringu z telemonit.com - Twój inteligentny asystent jest zawsze gotowy do rozmowy!

Interakcja:
- Głosowa i tekstowa komunikacja
- Możliwość zadawania pytań o zdarzenia z ostatnich 24 godzin
- Rozmowa video z podglądem wybranej kamery w czasie rzeczywistym *

Uczenie:
- Uczenie się nowych obiektów
- Eliminacja fałszywych powiadomień
  
Powiadomienia:
- Powiadomienia przez komunikator
- Przekazywanie tylko istotnych zdarzeń

Komunikatory:
- Telegram 
- Signal *
- WhatsApp *


* w przygotowaniu



## Rozwiazanie

Dlaczego CCTV z użyciem ML jest przełomem?

Bo pozwala za pomocą danych z jednego systemu stworzyć, system:

- alarmowy

- dostępu

- ostrzegania o incydentach: pożarze, kradzieży, ...




Zastosowanie uczenia maszynowego #ML w systemach monitoringu wizyjnego #CCTV pozwala na implementację systemu alarmowowego, kontroli dostępu, ostrzegania o incydentach: pożarze, kradzieży, ...


Interesuje mnie:
+ Analiza zachowań, incydentów
+ Rozpoznawanie obiektów, twarzy
+ Zarządzanie dostępem
+ ... odp. w komentarzu


Zastosowanie uczenia maszynowego (ML, od ang. Machine Learning) w systemach monitoringu wizyjnego (CCTV) przynosi przełom, ponieważ 
znacząco rozszerza możliwości tradycyjnych systemów CCTV, przekształcając je z prostych narzędzi rejestrujących w inteligentne systemy wspierające decyzje i reagowanie na zdarzenia w czasie rzeczywistym. Oto kilka kluczowych sfery, gdzie zastosowanie ML w CCTV jest przełomowe:

### System Alarmowy
- **Detekcja Nietypowych Zdarzeń**: Systemy mogą być trenowane do rozpoznawania nietypowych wzorców lub zachowań, które mogą sugerować zagrożenie, np. osoba wchodząca do budynku w nietypowych godzinach.
- **Natychmiastowa Reakcja**: Możliwość ustawienia automatycznych alarmów w przypaku wykrycia określonych zdarzeń, co pozwala na szybsze reagowanie przez służby bezpieczeństwa.

### Kontrola Dostępu
- **Rozpoznawanie Twarzy**: Wykorzystanie ML do identyfikacji osób za pomocą rozpoznawania twarzy oferuje bardziej zaawansowane i bezpieczne formy kontroli dostępu, niezależne od tradycyjnych metod jak karty dostępu czy kody PIN.
- **Detekcja Autoryzacji**: Możliwość detekcji obecności osób nieautoryzowanych w restrykcyjnych strefach i automatyczne generowanie powiadomień.

### Ostrzeganie o Incydentach
- **Detekcja Pożaru i Dymu**: Systemy ML mogą być trenowane do rozpoznawania oznak dymu i ognia na wczesnym etapie, co umożliwia szybką ewakuację i reakcję przeciwpożarową.
- **Rozpoznawanie Niebezpiecznych Przedmiotów**: Identyfikacja pozostawionych bagażów lub innych przedmiotów, które mogą stanowić zagrożenie, takie jak niebezpieczne materiały.

### Zalety Ogólne
- **Zmniejszenie Fałszywych Alarmów**: Dzięki zdolności do nauki i rozpoznawania złożonych wzorców, systemy ML mogą redukować liczbę fałszywych alarmów, zwiększając skuteczność monitoringu.
- **Optymalizacja Zasobów**: Automatyzacja detekcji zdarzeń pozwala optymalizować zasoby ludzkie, koncentrując uwagę personelu na sytuacjach wymagających interwencji.
- **Analiza Wideo w Czasie Rzeczywistym**: Przetwarzanie i analiza strumieni wideo w czasie rzeczywistym umożliwia natychmiastowe reagowanie na wykryte zagrożenia czy incydenty.

Integracja ML z systemami CCTV wnosi zatem gigantyczne ulepszenie w zakresie monitoringu i bezpieczeństwa, przekształcając pasywne nagrywanie w aktywną, inteligentną analizę pozwalającą na znaczące zwiększenie efektywności operacyjnej i bezpieczeństwa ogólnego.



Monitoring wizyjny (CCTV) z wykorzystaniem sztucznej inteligencji (ML) to przełomowe połączenie.
Pozwala na wykorzystanie danych z jednego systemu do stworzenia różnych funkcjonalności, takich jak:
- System alarmowy: Dzięki analizie obrazów i wykrywaniu nieprawidłowości, system może automatycznie generować alarmy w przypadku podejrzanych zdarzeń, takich jak nieautoryzowany dostęp czy ruch w zakazanej strefie .
- System kontroli dostępu: ML może pomóc w identyfikacji osób na podstawie obrazów z kamer, umożliwiając dostęp tylko uprawnionym użytkownikom. To zwiększa bezpieczeństwo i ułatwia zarządzanie dostępem do chronionych obszarów .
- Ostrzeganie o incydentach: System może automatycznie wykrywać potencjalne zagrożenia, takie jak pożar, kradzież lub inne awarie. Dzięki temu personel otrzymuje szybkie powiadomienia, co pozwala na natychmiastowe działania .
  Historia monitoringu wizyjnego sięga ubiegłego stulecia, ale dzisiejsze technologie znacznie różnią się od tych sprzed lat. Wcześniejsze kamery nie miały opcji jednoczesnego rejestrowania i przeglądania zdarzeń, co jest teraz standardem .
  Warto podkreślić, że połączenie ML z monitoringiem wizyjnym otwiera nowe możliwości i zwiększa efektywność systemów bezpieczeństwa.



Wielu myśli, że chatGpt to rewolucja ... a co jeśli wykorzystamy różne kanały komunikacji głosowe i video, asnychroniczne i synchroniczne np. w celu zarządzania infrastrukturą od monitoringu po smarthome, komputery


Wyobraź sobie rejestrator video z detekcją obiektów sterowany głosowo.
Tak działa system skalowalnego monitoringu z setkami kamer w XXI wieku.

Sterowanie i komunikacja z kamerą jest możliwa przez popularny komunikator:
+ signal
+ whatsapp
+ telegram
  
Asystent kamer będzie funkcjonował jak podczas rozmowy z osobą.
Do dystopzycji jest chat tekstowy i głosowy oraz funkcja rozmowy video, gdzie będzie można wybrać kamerę którą chce się widzieć w czasie rzeczywistym.

Uzytkownik może po prostu rozmawiać lub pisać z asystentem poprzez przez swój komunikator.
Aktualnie asystent, jest dostepny dla komunikatora signal z uwagi na bezpieczeństwo, ale będzie dostępny obsługa komunikatorów: whatsapp, telegram na życzenie.


### CameraMonit
Lider w usługach Zdalnego Dozoru Wizyjnego. Wymieniamy ochronę fizyczną na System Ochrony Wizyjnej znacznie podnosząc bezpieczeństwo obiektów przy okazji redukując wysokie koszty.

Koncentrujemy się na dostarczaniu nowoczesnych rozwiązań informatycznych w obszarze szeroko rozumianego bezpieczeństwa dla:

- stacji monitorowania alarmów
- stacji zdalnego dozoru wideo
- firm ochrony osób i mienia 
- banków i firmy o charakterze globalnym
- sieci handlowych, gastronomicznych i usługowych
- infrastruktury energetycznej, telekomunikacyjnej i paliwowej

Zapraszamy do współpracy

### Co wyróżnia CameraMonit?

W odróżnieniu od aktualnych systemów oferujemy komunikację głosową do sterowania całą siecią kamer i wybranymi w czasie rzeczysitom oraz dostęp do archiwalnych nagrań.


![wersja prototypowa telemonit.com](https://github.com/cameramonit/www/assets/5669657/1c71e644-2dc9-4152-8ef3-7acb7bc97ef3)
wersja prototypowa telemonit.com


### Oferta 

### dla instalatorow CCTV, systemow dozoru

kamery

rejstratory


#### dla ochrony

Jesteśmy otwarci na kooperację, ułatwiamy wdrożenie systemów tele-informatycznych


#### slużb specjalnych

oferujemy zaplecze merytoryczne i techniczne




## CamOs System

CamOS is a surveillance camera management app built on Media Server, empowering enterprises to establish private cloud camera solutions

+ [CamOS - Private cloud camera solution - Hackster.io](https://www.hackster.io/dmtan/camos-private-cloud-camera-solution-196a7e)
+ [ant-media/Ant-Media-Server](https://github.com/ant-media/Ant-Media-Server/releases)

+ [Ant Media Server - Real-time Streaming Engine](https://antmedia.io/)

Live Video Surveillance

Embed IP camera streams into websites and mobile apps to broadcast video. AMS is compatible with ONVIF IP cameras with PTZ and Auto Discovery features.

It offers direct data storage for new technology surveillance cameras, ensuring secure and easily accessible data through the cloud.
It supports online viewing, playback, and camera management with user-friendly administrative features.
Integration with various camera lines and recorders meeting the ONVIF connection standard optimizes cost efficiency, making it a versatile solution.
Integrate the smart features based on video analytics solutions to support your business such as smart retail stores, smart gates, and smart traffic monitoring.


## How can IP camera video analytics and AI reduce false alarms?

### Motion detection
Motion detection is a basic feature of IP cameras that can trigger an alarm when a change in the image is detected. However, not all motion is relevant or suspicious, and motion detection can be easily fooled by factors such as shadows, light, wind, or animals. To reduce false alarms, IP cameras can use video analytics and AI to enhance motion detection by filtering out irrelevant motion, adjusting sensitivity levels, and applying regions of interest. For example, a video analytic algorithm can ignore motion that is too small, too fast, or too far from the camera, or motion that occurs in a predefined area that is not important.


### Object recognition
Object recognition is a feature of IP cameras that can identify and classify different objects in the image, such as people, vehicles, animals, or weapons. This can help reduce false alarms by distinguishing between objects that pose a threat and objects that are harmless or authorized. For example, a video analytic algorithm can recognize a person carrying a gun and trigger an alarm, while ignoring a person carrying an umbrella or a bag. Object recognition can also help verify alarms by providing additional information about the object, such as its size, color, shape, or license plate.



### Face recognition
Face recognition is a feature of IP cameras that can match faces in the image with faces in a database, such as a whitelist or a blacklist. This can help reduce false alarms by verifying the identity and authorization of people who enter or exit a secured area. For example, a video analytic algorithm can recognize a face that belongs to an employee or a visitor and allow access, while detecting a face that belongs to a stranger or a criminal and alerting the security personnel. Face recognition can also help track and locate people of interest by comparing faces across multiple cameras and locations.



### Behavior analysis
Behavior analysis is a feature of IP cameras that can analyze and interpret the actions and interactions of people and objects in the image, such as walking, running, falling, fighting, or loitering. This can help reduce false alarms by detecting abnormal or suspicious behavior that indicates a potential threat or an emergency. For example, a video analytic algorithm can detect a person who falls down and does not get up and trigger an alarm, while ignoring a person who sits down and rests. Behavior analysis can also help prevent or respond to incidents by providing alerts and suggestions based on the behavior patterns and scenarios.





## Coffee shop 

This coffee shop uses AI to track the Productivity of Baristas and how much Time Customers are spending in the Shop.

Neurospot barista pro tracks everything from how many coffees baristas make to how long customers linger at tables.

- Tracks coffee output to monitor productivity and inventory.
- Monitors how long customers stay to optimize table turnover and service.
- Keeps tabs on table cleanliness in real-time for a hygienic environment.
- Tracks staff activities to ensure focus on designated tasks.

AI is going to be everywhere! Are you ready?

All this will come at a great cost of privacy.





### [Photogrammetry - Wikipedia](https://en.wikipedia.org/wiki/Photogrammetry)

Photogrammetry is the science and technology of obtaining reliable information about physical objects and the environment through the process of recording, measuring and interpreting photographic images and patterns of electromagnetic radiant imagery and other phenomena.






![image](https://github.com/cameramonit/www/assets/5669657/75e9af3e-67ec-4622-b365-57157bd99687)



![image](https://github.com/cameramonit/www/assets/5669657/42fcce48-3463-4625-99ba-8a9459b5298e)



Offer

It provides free rolling 3-day cycled cloud storage that you can enjoy storage service without any subscription. And it provides a 30-day free trial of advanced features that include AI recognition, upgraded cloud memory, custom alert areas and etc, the advanced features starts at $2.99 per month after 30 days free trial. 



### Kamery, dziedzina, branża

+ Proste wykrywanie obiektów jest standardem wbudowanym w wiele tanich kamer
+ Dziesiątki producentów kamer na świecie oferuje własny system w oprarciu o własne oprogramowanie i aplikację


### W jakim celu powstał ten projekt?

W celu głosowej komunikacji z systemem monitorowania kamerami, bez potrzeby instalowania nowych kamer lub osprzętu tego samego producenta


### Jaki problem rozwiązuje?

+ integracja starych kamer z nowymi (camera IP) do detekcji obiektów
+ jeden interfejs do różnych systemów i produenctów kamer



### Jakie daje korzyści

+ nie trzeba instalować nowych kamer aby skorzystać z funkcji wykrywania obiektów
+ nie trzeba kupować nowego rejestratora z funkcjami detekcji obiektów
+ Wzbogacenie nowoczesnego rejestratora o komunikację głosową i sterowanie kamer głosem
+ Zwiększenie możliwości wymiany i automatyzacji danych z kamer
+ Sterowanie urządzeniami i integracja z innymi systemami




AI Camera Market Size, Share & Trends Analysis Report By Technology (Image/Face Recognition, Computer Vision, Emotion Recognition, DSLR Cameras, Network Cameras Security, Cameras Others (Wi-Fi Camera)), By Camera Type (PTZ Camera, Dome Camera, Bullet Camera, Box Camera, Others), By End User (BFSI, Healthcare, Automotive, Consumer Electronics, Smartphones & Tablets CCTV Camera Digital Camera Others, Retail, Government, Logistics & Transportation, Military and Defense, Commercial Spaces, Media and Entertainment Others (Residential, Oil & Gas)), Global Economy Insights, Regional Outlook, Growth Potential, Price Trends,




Współpraca z firmami specjalizującymi się w obszarze security przyczynia się do zmniejszenia kosztu a jednocześnie zwiększenia szybkości reakcji na incydenty.


Zajmujemy się rozpoznawanie obiektów, wykorzystując sztuczną inteligencję do identyfikacji i śledzenia obiektów na zdjęciach i filmach.




Kamery CCTV zasilane sztuczną inteligencją zapewniają większe bezpieczeństwo, wykrywając podejrzane działania w czasie rzeczywistym, odstraszając potencjalnych przestępców i umożliwiając szybką reakcję w sytuacjach awaryjnych. Optymalizują alokację zasobów, proaktywnie zarządzają ryzykiem, generują cenne spostrzeżenia dotyczące danych i oferują skalowalność w obliczu zmieniających się potrzeb w zakresie bezpieczeństwa, zapewniając kompleksowe i skuteczne rozwiązanie do nadzoru.

## Jakich jest 7 zalet kamer CCTV obsługujących sztuczną inteligencję dla firm?

### Wykrywanie zagrożeń w czasie rzeczywistym
Kamery CCTV zasilane sztuczną inteligencją umożliwiają wykrywanie zagrożeń w czasie rzeczywistym i szybką identyfikację podejrzanych działań na bieżąco.
Zaawansowane algorytmy natychmiast analizują kanały wideo, ostrzegając pracowników ochrony o nieautoryzowanym dostępie lub nietypowym zachowaniu, umożliwiając szybką interwencję w celu zapobiegania incydentom.

### Nadzór 24/7
Technologia sztucznej inteligencji umożliwia firmom monitorowanie całodobowe, 7 dni w tygodniu bez konieczności stałego nadzoru człowieka, co pozwala stawić czoła wyzwaniom związanym z pracą na wielu zmianach. Dzięki kamerom CCTV wyposażonym w sztuczną inteligencję nadzór i analiza w czasie rzeczywistym są kontynuowane nawet wtedy, gdy obiekt jest zamknięty, automatycznie uruchamiając alerty w sytuacjach krytycznych. To nie tylko obniża koszty, eliminując potrzebę ciągłego monitorowania przez człowieka, ale także ogranicza fałszywe alarmy spowodowane błędem człowieka lub czynnikami niezagrażającymi, takimi jak zwierzęta.

### Szybka ekstrakcja danych
Reaktywne środki bezpieczeństwa, takie jak ręczne skanowanie materiału wideo w celu analizy kryminalistycznej, mogą być uciążliwe i czasochłonne, szczególnie w dużych obiektach, takich jak lotniska lub uniwersytety, w których znajduje się wiele kamer CCTV działających 24 godziny na dobę, 7 dni w tygodniu. Nagromadzenie ogromnych ilości danych wideo sprawia, że ich przeszukiwanie jest pracochłonne i kosztowne. Analityka wideo AI znacznie przyspiesza ten proces, umożliwiając użytkownikom szybkie wyszukiwanie określonych działań lub obiektów w całym materiale, redukując wymagany czas i zasoby w porównaniu z metodami ręcznymi.

### Skuteczne wykrywanie włamań
Wydajny system wykrywania interwencji ma kluczowe znaczenie dla organizacji i osób prywatnych, zwłaszcza gdy czas reakcji jest krytyczny i minimalizuje się fałszywe alarmy. Tradycyjnym kamerom wykrywającym ruch brakuje inteligencji, co powoduje wyzwalanie alertów w przypadku każdego ruchu, w tym zwierząt, pojazdów, a nawet zmian w cieniu, co skutkuje nadmierną liczbą fałszywych alarmów — od 100 do 150 na kamerę dziennie. To obciążenie jest szczególnie trudne w przypadku obiektów wyposażonych w wiele kamer monitorujących wielu odwiedzających. Z kolei kamery CCTV wykorzystujące sztuczną inteligencję zapewniają dokładniejsze wykrywanie, wysyłając odpowiednie obrazy i metadane do jednostek bezpieczeństwa, umożliwiając szybkie i ukierunkowane działanie w przypadku włamania.

### Poprawiona dokładność
Tradycyjne kamery CCTV obsługiwane przez człowieka są podatne na błędy ludzkie, szczególnie w dużych obiektach z dużą liczbą gości, gdzie monitorowanie staje się wyzwaniem. Zmęczenie, krótki czas skupienia uwagi i błędy ludzkie mogą skutkować przeoczeniem szczegółów lub zagrożeniami. Jednak dzięki technologii sztucznej inteligencji firmy mogą zapewnić kompleksowy nadzór bez ograniczeń wynikających z nadzoru człowieka. Systemy oparte na sztucznej inteligencji utrzymują stałą czujność niezależnie od wielkości obiektu i liczby gości, minimalizując ryzyko przeoczenia i zwiększając ogólną skuteczność bezpieczeństwa.

### Szybkie wyszukiwanie wideo
W razie wypadku przeglądanie obszernego materiału filmowego może być czasochłonne i nieefektywne. Kamery wykorzystujące sztuczną inteligencję zapewniają aktualizacje w czasie rzeczywistym, umożliwiając natychmiastowe działanie. Dzięki inteligentnej technologii nadzoru użytkownicy mogą szybko przechodzić do kluczowych fragmentów materiału filmowego, które wymagają większej uwagi, co zwiększa efektywność i skuteczność reakcji.

### Rozpoznawanie obiektów
Podczas gdy tradycyjne systemy CCTV rejestrują głównie materiał filmowy bez większego zastosowania, systemy CCTV oparte na sztucznej inteligencji oferują zaawansowane możliwości. Systemy te potrafią z łatwością rozróżnić zwierzęta domowe, znane i nieznane osoby oraz pojazdy. Dzięki wyraźnemu wykrywaniu obiektów i natychmiastowym alertom systemy CCTV oparte na sztucznej inteligencji informują Cię o aktywności na Twojej posesji, w tym o liczbie odwiedzających. Ta ulepszona funkcjonalność zapewnia cenne informacje dla celów lepszego bezpieczeństwa i monitorowania.

### Wniosek

Sztuczna inteligencja rewolucjonizuje bezpieczeństwo i ochronę, umożliwiając nam zachowanie kontroli nad naszym środowiskiem. Jeśli nie masz pewności, czy kamery CCTV zasilane sztuczną inteligencją będą potrzebne w Twoim domu lub firmie, nie wahaj się z nami skontaktować pod adresem






## EN




AI-powered CCTV cameras provide enhanced security by detecting suspicious activities in real-time, deterring potential criminals, and enabling quick response to emergencies. They optimize resource allocation, proactively manage risks, generate valuable data insights, and offer scalability for evolving security needs, ensuring a comprehensive and effective surveillance solution.

## What are the 7 benefits of AI-powered CCTV cameras for business?

### Real-Time Threat Detection
AI-powered CCTV cameras offer real-time threat detection, swiftly identifying suspicious activities as they happen.
Advanced algorithms analyze video feeds instantly, alerting security personnel to unauthorized access or unusual behavior, enabling rapid intervention to prevent incidents.

### 24/7 Surveillance
AI technology enables businesses to achieve 24/7 monitoring without the need for constant human oversight, addressing challenges associated with staffing multiple shifts. With AI-powered CCTV cameras, real-time surveillance and analysis continue even when the premises are closed, triggering alerts for critical situations autonomously. This not only cuts costs by eliminating the need for continuous human monitoring but also reduces false alarms caused by human error or non-threatening triggers like animals.

### Quick Data Extraction
Reactive security measures, like manually scanning through video footage for forensic analysis, can be arduous and time-consuming, especially in large premises like airports or universities with numerous CCTV cameras running 24/7. The accumulation of vast amounts of video data makes searching through it laborious and costly. AI video analytics significantly expedites this process by enabling users to swiftly search for specific actions or objects across all footage, reducing the time and resources required compared to manual methods.

### Powerful Intrusion Detection
A powerful intervention detection system is crucial for organizations and individuals, especially when response time is critical and false alarms are minimized. Traditional motion detection cameras lack intelligence, triggering alerts for any movement, including animals, vehicles, or even changes in shadows, resulting in excessive false alarms—up to 100 to 150 per camera daily. This burden is particularly challenging for sites with multiple cameras monitoring numerous visitors. In contrast, AI-powered CCTV cameras provide more accurate detection by sending relevant visuals and metadata to security units, enabling prompt and targeted action in case of intrusion.

### Improved Accuracy
Traditional CCTV cameras operated by humans are prone to human error, especially in large facilities with numerous visitors, where monitoring becomes challenging. Fatigue, short attention spans, and human error can result in missed details or threats. However, with AI technology, companies can ensure comprehensive surveillance without the limitations of human oversight. AI-powered systems maintain consistent vigilance regardless of facility size or visitor count, minimizing the risk of oversight and enhancing overall security effectiveness.

### Quick Video Search
In the event of an incident, sifting through extensive footage can be time-consuming and inefficient. AI-powered cameras provide real-time updates, enabling immediate action. With smart surveillance technology, users can swiftly navigate to critical sections in the footage that warrant closer attention, enhancing response efficiency and effectiveness.

### Object recognition
While traditional CCTV systems mainly record footage without much utility, AI-powered CCTVs offer advanced capabilities. These systems can easily differentiate between pets, known and unknown individuals, and vehicles. With clear object detection and instant alerts, AI-powered CCTVs keep you informed about activity on your property, including the number of visitors. This enhanced functionality provides valuable insights for better security and monitoring purposes.

### Conclusion

Artificial Intelligence is revolutionizing safety and security, empowering us to stay in control of our environments. If you're unsure about the necessity of AI-powered CCTV cameras for your home or business, don't hesitate to reach out to us at



---





## EN

I have coded many object detection algorithms into its infrastructure and create a database of camera IPs around the world.
With this algorithm programmed to track nearly 160 objects. I am constantly feeding this IP database and boosting it with scans.

I shared the previous version of this with you before.
This is a much more stable and precise layout.

We can say that cyber security, data science and artificial intelligence algorithms are focused on a single purpose.



#algorithms #machinelearnig #machinelearningalgorithms #artificialintelliegence #informationsecurity #cybersecurity


## PL

+ uberyzacja branzy security


## Oferta


### installator

+ konfiguracja kamer za pomocą smartfona, minimalina wiedza instalatora, dlatego wystarczy montaz i podłączenie


### Audyt REMOTE - Support Phone

+ płatne za rok z góry


### Audyt LOCAL - HUMAN SERVICE

+ po podłączeniu można zamówić płatny audyt
+ po uzyskaniu audytu, można skorzystać z local security , usługi reagowania, na wypadek kradzieży
+ bez audytu można korzystać z wersji płatnej personal security



### local security APP

dla firm security dojeżdżających lokalnie


### personal security APP

aplikacja powiadamiająca w smartfone dla kilku osób z rodziny


## Detekcja
+ broni
+ pozaru
+ upadku czlowieka
+ szybkich zdarzen sugerujacych anomalie


### bron

Ostatnie wydarzenia w Maine przypominają nam o pilnej potrzebie zwiększenia środków bezpieczeństwa w naszych społecznościach. Nasze myśli i najgłębsze kondolencje kierujemy do wszystkich dotkniętych tą tragedią.

Jako część społeczności technologicznej czujemy się głęboko odpowiedzialni za przyczynienie się do zwiększenia bezpieczeństwa naszych przestrzeni publicznych. Chociaż żadna technologia nie może zastąpić ludzkiej czujności i wsparcia społeczności, z pewnością może pomóc we wczesnym wykrywaniu i zapobieganiu.

My, w CameraMonit. opracowaliśmy rozwiązanie, które wykrywa broń palną w nagraniach CCTV, mając na celu zapewnienie dodatkowej warstwy bezpieczeństwa w przestrzeni publicznej i prywatnej.

Naszym głównym celem jest wspieranie pracowników ochrony, organów ścigania i społeczności poprzez oferowanie narzędzia, które może potencjalnie zapobiec takim tragicznym wydarzeniom w przyszłości. Zapraszamy liderów społeczności, specjalistów ds. bezpieczeństwa i zainteresowane strony do dyskusji na temat tego, jak możemy współpracować i zapewnić bezpieczeństwo naszym bliskim.

Obraz został przeanalizowany przez nasze oprogramowanie do wykrywania broni AI CCTV.


## pozar

technologia wykrywania pożarów

Nasze rozwiązanie rewolucjonizuje protokoły bezpieczeństwa, wykraczając poza ograniczenia tradycyjnych czujników dymu.
Zaprojektowana z myślą o nowoczesnych firmach, ta płatna usługa SaaS wykorzystuje zaawansowaną sztuczną inteligencję do wykrywania pożarów z niezrównaną szybkością i dokładnością.

Dlaczego warto wybrać naszą technologię wykrywania pożarów opartą na sztucznej inteligencji?

Wszechstronne zastosowania: Idealny do środowisk, w których konwencjonalne czujniki dymu nie sprawdzają się - duże niezadaszone magazyny, rozległe przestrzenie zewnętrzne i ważne instalacje zewnętrzne, takie jak panele fotowoltaiczne.

Alerty w czasie rzeczywistym: Natychmiastowe powiadomienia pozwalają na szybką reakcję, zmniejszając potencjalne szkody i zapewniając bezpieczeństwo zasobów i personelu.

Minimalna infrastruktura: Eliminacja potrzeby tworzenia rozległych sieci czujników. Nasz system płynnie integruje się z istniejącą infrastrukturą wideo, oszczędzając czas i pieniądze.

Wgląd w dane: Wykorzystaj moc analityki, aby wzmocnić środki bezpieczeństwa przeciwpożarowego, dzięki szczegółowemu rejestrowaniu zdarzeń w celu podejmowania świadomych decyzji.
Upewnij się, że Twoja firma jest zabezpieczona przed nieprzewidzianymi zdarzeniami dzięki naszemu systemowi wykrywania pożarów opartemu na sztucznej inteligencji.
Pożegnaj się z martwymi punktami w bezpieczeństwie przeciwpożarowym - powitaj nową erę ochrony dzięki naszemu inteligentnemu rozwiązaniu.
Wyprzedź konkurencję i pozwól sztucznej inteligencji chronić Twoją firmę.

Dowiedz się więcej o tym, jak nasza analiza wideo AI może wzmocnić Twoje środki bezpieczeństwa przeciwpożarowego.

Skontaktuj się z nami, aby otrzymać demo już dziś!





## TODO

+ lista obsługiwanych i w poczekalni rejestratorów
+ lista obsługiwanych i w poczekalni producentów kamer i modeli
+ lista obsługiwanych i w poczekalni producentów usług do obróbki danych
+ lista obsługiwanych i w poczekalni producentów usług do przechowywania danych
+ lista obsługiwanych i w poczekalni producentów technologii i protokołów


## FOSCAM

+ [Foscam Support - Downloads](https://www.foscam.com/downloads/firmware_details.html?id=6)
+ [How to connect directly to Foscam camera using a computer?-Foscam Support - FAQs](https://www.foscam.com/faqs/view.html?id=139)
+ [How to log into a HD camera via a web browser?-Foscam Support - FAQs](https://www.foscam.com/faqs/view.html?id=17)
+ [Foscam Support - FAQs](https://www.foscam.com/downloads/app_software.html)
+ [How to install plugins if they are blocked?-Foscam Support - FAQs](https://www.foscam.com/faqs/view.html?id=161)



## Interface


### N8N (self-hosted open source automation tool, MAKE alternative)
[n8n.io - a powerful workflow automation tool](https://n8n.io/)

### Railway(cloud for apps, it deployed N8N instance in 5 mins for me)

### OpenAI (API for GPT, can be easily replaced with open source model in a single click)

### Baserow (open source no-code database, Airtable alternative)
I'm on a hobby plan. Avg spending depends on the intensity of your automation usage. In my case (just solo experiments/proof of concepts) I'm paying ~$6 / month
helm charts na k8s
you may run this stuff on self managed server if you like and use llama2 or mistral models instead of OpenAI.

anthropic.com






Kamery IP: Kamery IP są podłączone bezpośrednio do switcha. Każda kamera ma swoje własne IP i jest zasilana przez Power over Ethernet (PoE), co oznacza, że przesył danych i zasilanie odbywają się przez ten sam kabel Ethernet.
Switch: Switch jest centralnym punktem, do którego podłączone są kamery. To urządzenie umożliwia komunikację między kamerami oraz z innymi urządzeniami w sieci.
MiniPC: MiniPC jest podłączony do switcha. Może to być komputer jednopłytkowy lub inny mały komputer, który pełni rolę serwera lub rejestratora wideo.
Router: MiniPC jest następnie podłączony do routera, który zapewnia dostęp do Internetu. Router może obsługiwać zarówno przewodowe, jak i bezprzewodowe połączenia.
Oto graficzne przedstawienie tego układu:







## Podsumowanie

Chciałbym sprzedawać aplikacje na android do podglądu kamer z inteligentnym powiadamianiem o incydentach w oparciu o sztuczną inteligencję. 
Aplikacja nazywa się CameraMonit od konkurencji wyróżniają ją funkcje:
1.  Głosowa komunikacja z systemem nadzoru, bez potrzeby zaglądania do aplikacji, wystarczy tylko głosowa komenda jak w rozmowie z inteligentnym asystentem
2. Komunikacja z aplikacją poprzez integrację z komunikatorami takimi jak signal, telegram, whatsup
3. Aplikacja Android nie wymaga komunikacji z zewnętrznymi serwerami, możliwa jest praca offline bez internetu


Sprzedaż i dystrybucja dotyczy głównie klientów biznesowych, którzy będą zainteresowani nie tylko wykorzystaniem tej aplikacji np w biurze czy w domu, ale też będą chcieli bardziej zaawansowane centrum obliczeniowe do kontroli wejścia i wyjścia osób w obiekcie a także alarmowania incydentów jak pożar, kradzieź, dewastacja majątku.
Z naciskiem na obliczenia i ulepszone modele rozpoznawnia obiektow, ktore potem bede rowniez sprzedawal.

Finansowanie samego pomysłu nie jest konieczne a jedynie socjalne utrzymanie w celu wyprodukowania kolejnych ulepszonych wersji aplikacji w ciągu 3 miesięcy i jej sprzedaży na rynku Europejskim w marketplace google play i apple store.

Koszt pojedynczej aplikacji będzie na początku 20$ (marża google 20%).
Podobne aplikacje na dzień dzisiejszy są w cenie 5$ i  mają ponad 100 tysięcy pobrań. Jednak żadna z nich nie oferuje funkcji, które będzie miała moja aplikacja.

Będę kontaktował się bezpośrednio z instalatorami systemów alarmowych, CCTV, monitoringu infrastruktury w fabrykach i firmach, by zaproponować partnertswo i dystrybucję w oparciu o do 20-40% marży dla nich.
Będę również prowadził spotkania, prowadzil bloga i wystepowal na branzowych konferencjach jako ekpsert w celu promocji tej aplikacji a potem kolejnych uslug.

 [<span style='font-size:20px;'>&#x270D;</span>](git@github.com:telemonit/contribution/edit/main/DOCS/FOOT.md)
---
[info about privacy](../docs/PRIVACY.md)


+ [edit](https://github.com/cameramonit/www/edit/main/README.md)


<script type="module">    
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  //import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10.8.0/dist/mermaid.min.js';
  mermaid.initialize({
    startOnReady:true,
    theme: 'forest',
    flowchart:{
            useMaxWidth:false,
            htmlLabels:true
        }
  });
  mermaid.init(undefined, '.language-mermaid');
</script>

---
+ Modular Documentation made possible by the [FlatEdit](http://www.flatedit.com) project.
