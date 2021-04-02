# Taller de Git/ Github :rocket:
## Datos del alumno :clipboard:
**Nombre**: Francisco Cordero
**Profesor**: Pablo Poblete
## Comandos utilizados :computer:
#### 1. Clonando el repositorio 
**Input**
```bash
git clone git@github.com:pabpobar/Taller-Git-GitHub.git
```
**Output**
```bash
Cloning into 'Taller-Git-GitHub'...
remote: Enumerating objects: 18, done.
remote: Counting objects: 100% (18/18), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 18 (delta 4), reused 6 (delta 2), pack-reused 0
Receiving objects: 100% (18/18), 84.05 KiB | 614.00 KiB/s, done.
Resolving deltas: 100% (4/4), done.
```
- - -
#### 2. Ingresamos al directorio
**Input**
```bash
cd Taller-Git-GitHub 
```
**Output**
```bash
➜  Taller-Git-GitHub git:(main)
```
- - -
### 3. Creamos una nuevo rama
**Input**
```bash
git checkout -b FranciscoCordero-11630
```
**Output**
```bash
Switched to a new branch 'FranciscoCordero-11630'
```
- - -
### 4. Creamos este archivo y lo rellenamos en VS Code :pencil2:
**Nota**: Toda la edición fue en este branch :smile:
**Input**
```bash
➜  Taller-Git-GitHub git:(FranciscoCordero-11630) touch FranciscoAntonioCorderoSoza-11630.md
➜  Taller-Git-GitHub git:(FranciscoCordero-11630) ✗ code .              
```
- - -
### 5. Verificamos los cambios con git status
**Nota**: 
```bash 
alias gst="git status"
```
**Input**
```bash
➜  Taller-Git-GitHub git:(FranciscoCordero-11630) ✗ gst

```
**Output**
```bash
On branch FranciscoCordero-11630
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	FranciscoAntonioCorderoSoza-11630.md

nothing added to commit but untracked files present (use "git add" to track)

```