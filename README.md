```js
import git from "github";

async function githubProfile() {
  const profile = git.Profile({
    programmingLanguages: ["C", "JS", "TS"],
    editors: ["vscode"],
    os: "ZorinOS"
  });

  try {
    profile.talkWithMe({
      discord: "crow_ler"
    });
  } catch (error) {
    console.error("Error:", error);
  }
}

githubProfile();
```
