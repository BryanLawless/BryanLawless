<img align="right" alt="Profile Hits" src="https://komarev.com/ghpvc/?username=TheLawlessDev&style=flat-square">

```go
package readme

import (
  "fmt"
  "encoding/json"
  "log"
)

type ReadMe struct {
    Name string `json:"name"`
    Located string `json:"located"`
    Studying string `json:"studying"`
    FavoriteLanguages []string `json:"favorite_languages"`
    FavoriteGames []string `json:"favorite_games"`
    Hobbies []string `json:"hobbies"`
    MainProject string `json:"main_project"`
}

func main() {
    readme := ReadMe{
        Name: "Bryan Lawless",
        Located: "Denver, Colorado",
        Studying: "Computer Science, Cybersecurity, Machine Learning",
        FavoriteLanguages: []string{"golang", "typescript", "python"},
        FavoriteGames: []string{"doom", "space marines", "helldivers 2", "blade and sorcery", "half life"},
        Hobbies: []string{"tennis", "mountain biking", "electronics"},
        MainProject: "https://github.com/Quasec"
    }

    data, err := json.Marshal(readme)
	if err != nil {
		log.Fatal(err)
	}

    fmt.Println(string(readme[:]))
}
```
<br>
 
 <h2>🧰 Technologies I use</h2>
 
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) ![Tor](https://img.shields.io/badge/Tor-7D4698?style=for-the-badge&logo=Tor-Browser&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37) ![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)

<br>

<h2>🪙 Certifications</h2>
<table>
  <tr>
    <td><img src="./itf-cert.png" height="140"></td>
    <td><img src="./a-plus-cert.png" height="125"></td>
  </tr>
</table>

<br>

<h2>📊 Github Stats</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BryanLawless&theme=github_dark&hide_border=true&include_all_commits=false&count_private=true" width="32%">
    <a href="https://git.io/streak-stats">
      <img src="https://github-readme-streak-stats-seven-azure.vercel.app?user=BryanLawless&theme=tokyonight-duo&hide_border=true&short_numbers=true&date_format=j%20M%5B%20Y%5D&mode=weekly" alt="GitHub Streak" width="30%"/>
    </a>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BryanLawless&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact" width="25%">
</p>
