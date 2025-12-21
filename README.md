# TP1 file tree
On active le virtual environment et on genère les données depuis generate_data.py:

![alt text](images/image.png)

Puis on prépare les données

![alt text](images/image-1.png)

Puis en entraine le modèle

![alt text](images/image-2.png)

Ensuite l'evaluation

![alt text](images/image-3.png)

On start fastapi

![alt text](images/image-4.png)

tester get method

![alt text](images/image-5.png)

post method 

![alt text](images/image-6.png)

tester drift

![alt text](images/image-7.png)

On entraine un nouveau modèle, puis on test roll back

![alt text](images/image-8.png)

files tree final

![alt text](images/image.png)


---
# TP2 all commits

on initialize le repo

![alt text](images/image-9.png)

gitigore

![alt text](images/image-10.png)

git status

![alt text](images/image-11.png)

on ajoute les files au stage

![alt text](images/image-12.png)

commit

![alt text](images/image-13.png)

afficher l'historique

![alt text](images/image-14.png)


on voie la difference aprés modifier monitor_drift.py

![alt text](images/image-15.png)

On l'ajoute et voire la difference en stage

![alt text](images/image-17.png)
![alt text](images/image-16.png)

puis commit

![alt text](images/image-18.png)

créer une branche

![alt text](images/image-19.png)

On modifie api.py, l'ajoute au stage, puis commit

![alt text](images/image-20.png)

lister les branches avec `git branch`

![alt text](images/image-21.png)

On select master branche

![alt text](images/image-22.png)

on merge master avec feature/api-request-id branch

![alt text](images/image-23.png)

afficher l'historique

![alt text](images/image-24.png)

---

On crée une nouvelle branch

![alt text](images/image-25.png)

On modifie train.py puis add and commit

![alt text](images/image-26.png)

On switch to master

![alt text](images/image-27.png)

On modifie encore une fois train.py et on essaie de fusioner 

![alt text](images/image-30.png)

![alt text](images/image-29.png)

On résoudre le conflit

![alt text](images/image-31.png)

---

On modifie rollback.py et on met de côté les modifications

![alt text](images/image-32.png)

Stach list avec git stash list

![alt text](images/image-33.png)

Récupérer les modifications

![alt text](images/image-34.png)

---

On crée un fichier de test

![alt text](images/image-35.png)

On le modifie et comitter 2 fois

![alt text](images/image-36.png)

Effectuer un reset soft 

![alt text](images/image-37.png)

Effectuer un reset mixed

![alt text](images/image-38.png)

Effectuer un reset hard

![alt text](images/image-39.png)

---

Ajouter un changement non souhaité dans src/api.py

![alt text](images/image-40.png)

Lister les commits

![alt text](images/image-41.png)

Revert du dernier commit

![alt text](images/image-42.png)

![alt text](images/image-43.png)

---

Créer branche feature/drift-last-n

![alt text](images/image-44.png)

On modifie monitor_drift.py ...

![alt text](images/image-45.png)

Revenir sur la branche principale et créer un nouveau commit

![alt text](images/image-46.png)

Revenir sur la branche feature

![alt text](images/image-47.png)

Rebaser la branche feature sur la branche principale

![alt text](images/image-48.png)

Vérifier l’historique

![alt text](images/image-49.png)
