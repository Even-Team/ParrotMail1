# ParrotMail Mod (Fabric 1.21.8)

This repository contains the ParrotMail mod source and a GitHub Actions workflow that builds the mod
and creates a GitHub Release with the generated `.jar` whenever you push to `main` or run the workflow manually.

## How to use CI to get a JAR

1. Create a new GitHub repository (private or public).
2. Upload the contents of this project into the repo (preserve the `.github` folder).
3. Commit and push to the `main` branch.
4. Open the **Actions** tab → select the **Build and Release Mod** workflow → run it or wait for the push to trigger.
5. After the run completes, check **Actions → latest run → Artifacts** or **Releases** — the `.jar` will be attached to the release.

The workflow uses JDK 21 and Gradle wrapper to build the mod for Fabric 1.21.8.

