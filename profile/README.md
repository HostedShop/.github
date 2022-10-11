<a name="readme-top"></a>

<!-- [![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url] -->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/HostedShop">
    <img src="images/5BI1fI4.png" alt="Logo" width="auto" height="80">
  </a>

  <!-- <h3 align="center">Hostedshop</h3> -->

  <p align="center">
    Intern versioning til egen brug & bedre oversigt
  </p>
</div>

<!-- FORMÅL -->

# Formål

Formålet med at lave git versioning på vores arbejde er for at gøre det nemmere at holde overblikket i vores arbejde og minimere fejl.

###Eksempler

1. Vi kommer på job mandag morgen og kan ikke huske hvor vi er i arbejdsprocessen

- Her vil git gøre det nemt at huske hvad du er i gang med, gennem dine egne commits.

2. Vi skal lave en større ændring på eksempelvis en produkt-side som vil tage længere tid

- Her vil git være din bedste ven, da du kan lave en branch _ie: ProductPageDesign_ & her har du nu lov til at tage chancer og her må du gerne fejle, da du har en backup i form af master branchen. Det vil øge effektiviteten da du ikke behøver at være så forsigtig når du sletter og tilføjer kode.

3. Vi skal lave mange ændringer på en webshop

- Her er git god til at holde det samlede overblik, da du kan lave en branch for hvert område som du arbejde på og derved have dit eget interne projekt-flow, hvor du igennem dine commits kan holde dit eget overblik. Hvis du eksempelvis har 8 branches, og du ikke har arbejdet på en af disse branches i lang tid, kan du hurtigt kigge din commit history igennem og se hvad du har lavet af arbejde.

<!-- OPSÆTNING -->

# Opsætning

Der er to måder at sætte et repo op, enten som et nyt projekt eller som et eksisterende projekt. Processen er lidt forskellig mellem de to.

_Det er vigtigt at du husker at lave en .gitignore fil her som sørger for at ignorere de personfølsomme data.
<br>
Jeg anbefaler at du tilføjer din .gitignore fil inden at du begynder opsættelsen af dit repo, så du er sikret at følsom data ikke bliver tilføjet til dit repository.
<br>
Længere nede kan du hente den gitignore fil som skal bruges._

<!-- 1/2 -->

### Nyt projekt

Det her er når du opstarter en ny kunde og ikke har nogen filer på din pc endnu. Her laver du blot et nyt repository og cloner det ned på din pc, hvorefter du i denne mappe laver den almindelige FTP opsætning med SFTP.

<!-- 2/2 -->

### Eksisterende projekt

Denne process er hvis du allerede har kundens projekt på din pc og vil have det sat op til et repository.
<br>
Da du ikke kan trække et eksisterende repository ind over et eksisterende projekt, skal du lave det eksisterende projekt til repositoriet.
Det kan enten gøres med terminalen eller med GitHub desktop og processen er den samme, blot med forskellige fremgangprocesser.

<!-- 1/1 -->

#### Github Desktop

Her går du ind i projektet's mappe & laver en init, som vil gøre mappen klar til at blive sat op til GitHub.

- Projektets terminal
  ```sh
  git init
  ```

Du kan nu gå ind i GitHub Desktop og trykke:

1. "Add Repository"
2. "Add Existing Repository"
3. Vælg path til projektet
4. "Publish Repository"
5. Sæt HostedShop som Organization
6. "Publish Repository"

<!-- 2/2 -->

#### Terminal

Denne metode kræver at du laver et tomt repository på GitHub.com, som vi så fletter sammen med din lokale projekt mappe.
Efter du har lavet et tomt repository, går du ind i projektet's mappe & åbner terminalen & laver en init, som vil gøre mappen klar til at blive sat op til dit GitHub repository.

Her fra er processen den samme som ovenfor, bare i terminalen.

- Projektets terminal

  ```sh
  git init
  ```

- Tilføj filerne

  ```sh
  git add .
  ```

- Commit projektets filer

  ```sh
  git commit -m "Add existing project files to Git"
  ```

- Synkroniser dit projekt med GitHub repo

  ```sh
  git remote add origin https://github.com/Hostedshop/projekt-navn.git
  ```

- Push dit projekt til dit GitHub repo
  ```sh
  git push -u -f origin master
  ```

_"-u gør GitHub repo til dit default repo"
<br>
"-f overskriver allerede eksisterende filer i dit repo"_

<!-- .gitignore -->

# .gitignore

[Link til .gitignore](https://github.com/HostedShop/.githubblob/main/.gitignore)

De to VIGTIGSTE ting i denne fil er at informationen til FTP connection og Node Modules bliver ignoreret.
<br>
<br>
**_Som tidligere nævnt så anbefales det at .gitignore filen er tilføjet til projektet inden du laver repo opsætningen._**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- KONTAKT -->

# Kontakt

Kontakt mig hvis der er spørgsmål.

Simom Laursen - slr@onlineplus.dk

<p align="right">(<a href="#readme-top">back to top</a>)</p>
