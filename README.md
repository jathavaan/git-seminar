# Introduksjon til Git

Git er et distribuert versjonskontrollsystem (VCS) som lar flere personer jobbe på et prosjekt samtidig uten å overskrive hverandres endringer. Det ble opprettet av Linus Torvalds i 2005.

Her er noen grunnleggende Git-kommandoer:

1. `git init`: Initialiserer et nytt Git-repositorium. Denne kommandoen oppretter en ny `.git` undermappe i din nåværende arbeidsmappe. Dette vil også opprette en ny master branch.
    ```bash
    git init
    ```

2. `git clone`: Oppretter en kopi av et eksternt repositorium på din lokale maskin.
    ```bash
    git clone <repository_url>
    ```

3. `git add`: Legger til en endring i arbeidsmappen til staging-området. Det forteller Git at du vil inkludere oppdateringer til en bestemt fil i neste commit.
    ```bash
    git add <file_name>
    ```

4. `git commit`: Tar et øyeblikksbilde av prosjektets for tiden stagede endringer.
    ```bash
    git commit -m "<commit_message>"
    ```

5. `git push`: Pusher endringer til et eksternt repositorium.
    ```bash
    git push <remote> <branch>
    ```

6. `git pull`: Henter endringer fra et eksternt repositorium og fletter dem inn i din nåværende branch.
    ```bash
    git pull <remote>
    ```

7. `git branch`: Lister alle lokale branches i det nåværende repositoriet.
    ```bash
    git branch
    ```

8. `git checkout`: Bytter branches eller gjenoppretter arbeidstre filer.
    ```bash
    git checkout <branch_name>
    ```

9. `git merge`: Fletter en eller flere branches inn i din nåværende branch og oppretter automatisk en ny commit hvis det ikke er noen konflikter.
    ```bash
    git merge <branch_name>
    ```

Husk, Git sporer endringer i koden din og lar deg tilbakestille til enhver spesifikk endring. Det er et kraftig verktøy for samarbeidsprosjekter og versjonskontroll.