# pratica_git_flow

Esta es la rama development

1. Create a new repository with the name: pratica_git_flow, add readme.md file.

2. Clone repository


` 
git clone git@github.com:Jonathan191012/pratica_git_flow.git
`

3. Create a branch named development

`
create checkout -b development
`

4. Edit the readme.md file of the development branch

`
sudo nano README.md
`

 Add the following text

`
Esta es la rama development
`

5. Run commit command and push

```
git add .

git commit -m "Ejecutando commit para rama development"

git push --set --upstream origin development

```

6. Create a branch named features


`
create checkout -b features
`

7. Edit the readme.md file of the features branch

`
sudo nano README.md
`

 Add the following text
 
`
Esta es la rama features
`

8. Run commit command and push

```
git add .

git commit -m "Ejecutando commit para rama features"

git push --set --upstream origin features

```

9. Watch the changes from GitHub
