# Comandos GIT y GITHUB

---

## Trabajando en mi local

#### git init // Inicializa mi repositorio local

#### git add `nombre de archivo` // Agrego al stage el archivo modificado

#### git commit -m "mensaje del commit" // Registro los cambios que dejé en stage

#### git commit -am "mensaje del commit" // Agrego a Stage y Registro los cambios al mismo tiempo

---

## Comandos utilitarios

#### git status // Para chequear el estado de mis archivos

#### git log // Para ver los commits

#### git branch // Me lista todas las ramas actuales

---

## Trabajando en mi local con ramas

#### git branch `nombre de rama` // Me crea una rama nueva

#### git checkout -b `nombre de rama` // Me crea la rama y me la cambia a esa

#### git branch -D `nombre de rama` // Elimina la rama seleccionada

#### git switch `nombre de rama` // Para navegar entre ramas

#### git checkout `nombre de rama` // Para navegar entre ramas

#### git switch - // Para alternar entre la rama actual y la anterior

#### git checkout - // Para alternar entre la rama actual y la anterior

---

## Fusionando nuestras ramas

#### git merge `nombre de rama` // Fusiona la rama indicada dentro de la rama actual

---

## Trabajando Remoto

#### git remote add origin `codigo que nos da github para vincularlo` // Añado origen remoto (se hace solo una vez).

#### git push origin `nombre de rama` // Sube a github la rama indicada

#### git push -u origin `nombre de rama` // Sube a github la rama indicada y la setea como predeterminada

#### git push // Sube a github la rama que predeterminada

#### git pull origin `nombre de rama` // Nos trae los cambios de la rama seleccionada desde github

---

## Comandos Utilitarios trabajando remoto

#### git remote -v // Chequea el origen remoto si es que exsite
