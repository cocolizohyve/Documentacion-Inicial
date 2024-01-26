- comando para inicializar git#card
  card-last-interval:: -1
  card-repeats:: 0
  card-ease-factor:: 2.5
  card-next-schedule:: nil
  card-last-reviewed:: nil
  card-last-score:: nil
  collapsed:: true
	- git init
- comando para indicar la ruta de git #card
  collapsed:: true
	- git remote add origin <link_de repositorio>
- comando para añadir elemento al commit #card
  collapsed:: true
	- git {{cloze add .}}
- comando para hacer commit #card
  collapsed:: true
	- git {{cloze commit -m <acciones realizadas en el commit obligatorio id de tarea de jira>}}
- push y pull #card
  card-last-interval:: -1
  card-repeats:: 0
  card-ease-factor:: 2.5
  card-last-reviewed:: nil
  card-next-schedule:: nil
  card-last-score:: nil
	- push = subir commit a git
		- {{cloze git push -u origin <branch en la que se trabaja >}}
	- pull = bajar cambios de git
		- {{cloze git pull origin <branch o rama en la que se esta trabajando> }}
-