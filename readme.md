# ARCHIVO DE PRUEBA PARA VERIFICAR PR

---

## En este repositorio, podran realizar su primer PULL REQUEST.

## Deberan seguir las instrucciones que a continuacion se detallan.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

## FORK a este repositorio

Hacer un FORK a este repositorio clickeando en el boton FORK en la parte superior de esta pagina. Esto va a crear una copia de este repositorio, enlazada desde sus propias cuentas de github.

## CLONE al repositorio FORKEADO

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Ahora, realicen un CLONE al repositorio en su cuenta que acaban de hacer un FORK
Para esto, vayan a su cuenta de github y viendo el repositorio forkeado, hagan click en el boton verde que dice CODE.
Luego, copien la direccion que aparece clickeando en el icono de portapapeles.
Luego abran su terminal preferido (preferentemente el de VSC) e ingresen los siguientes comandos:

```
git clone "peguen aca la direccion copiada (sin comillas)"
```

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone git@github.com:this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

For example:

```
git switch -c add-alonzo-church
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

-   ### Authentication Error
       <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
    remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
    fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
    Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

---

. TEST
. Sofia Andrea Aguirre Hasin
. Ivana Yamila Belen Ajaya
. Yanina Maribel Allende
. Santiago Aquino
. Exequiel Arguello
. Rocio Barria
. Walter Eduardo Benitez
. Veronica Belen Boscatto
. Valentina Botto
. Matias Agustin Caro
. Juan Cruz De Luca
. Elias Adriel Diaz Saravia
. Lilia Andrea Garcia Hiramatsu
. Nestor Gentil
. Celeste Gianfelici
. Giuliana Godoy
. Ailen Beatriz Gonzalez
. Mara Belen Gonzalez
. Fiama Antonella Insaurralde
. Eugenia Yanina Isasmendi
. Jose Jimenez
. Maria Florencia Jorrat
. Solange Soledad Lopez
. Wanda Ayelen Martin
. BRISA ARACELI MIRANDA CHARCA
. Wendy Moreno Sanchez
. Milagros Ayelen Raices
. Dahyana Ayelen Romero
. Victoria Melina Senh
. Alfonsina Lourdes Taborda Gutierrez
. Florencia Torrado
. Sol Guadalupe Urbano
. Luciana Rocio Vizcarra
