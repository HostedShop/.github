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

<!-- USAGE -->

# Usage

Der er to måder at sætte et repo op, enten som et nyt projekt eller som et eksisterende projekt. Processen er lidt forskellig mellem de to.

_Det er vigtigt at du husker at lave en .gitignore fil her som sørger for at ignorere de personfølsomme data.
Jeg anbefaler at du tilføjer din .gitignore fil inden at du begynder opsættelsen af dit repo, så du er sikret at følsom data ikke bliver tilføjet til dit repository.
Længere nede kan du hente den gitignore fil som skal bruges._

### Nyt projekt

Det her er når du opstarter en ny kunde og ikke har nogen filer på din pc endnu. Her laver du blot et nyt repository og cloner det ned på din pc, hvorefter du i denne mappe laver den almindelige FTP opsætning med SFTP.

### Eksisterende projekt

Denne process er hvis du allerede har kundens projekt på din pc og vil have det sat op til et repository.
Da du ikke kan trække et eksisterende repository ind over et eksisterende projekt, skal du lave det eksisterende projekt til repositoriet.
Det kan enten gøres med terminalen eller med GitHub desktop og processen er den samme, blot med forskellige fremgangprocesser.

#### Github Desktop

Her går du ind i projektet's mappe & laver en init, som vil gøre mappen klar til at blive sat op til GitHub.

- Projektets terminal
  ```sh
  git init
  ```

Du kan nu gå ind i GitHub Desktop og trykke på "Add Repository" -> "Add Existing Repository" -> vælg path til projektet -> "Publish Repository" -> Sæt HostedShop som Organization -> "Publish Repository"

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

- Push dit projekt til dit GitHub repo "-u gør GitHub repo til dit default repo" "-f overskriver allerede eksisterende filer i dit repo"
  ```sh
  git push -u -f origin master
  ```

### .gitignore

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Simom Laursen - slr@onlineplus.dk

<p align="right">(<a href="#readme-top">back to top</a>)</p>
