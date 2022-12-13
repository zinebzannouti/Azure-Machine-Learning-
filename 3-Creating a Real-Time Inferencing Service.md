# Create a Real-time Inference Service


---
**Il ne sert à rien de former et d'enregistrer des modèles d'apprentissage automatique si vous ne prévoyez pas de les rendre disponibles pour les applications à utiliser. Dans cet exercice, vous allez déployer un modèle en tant que service Web pour l'inférence en temps réel.**

- *In this exercise, the code to deploy a model as a real-time inferencing service is provided in a notebook*

  1-In the Notebooks page, browse to the /users/your-user-name/mslearn-dp100 folder where you cloned the notebook repository, and open the 
  **Create a Real-time Inferencing Service** notebook.
  
  ![a](https://user-images.githubusercontent.com/78825764/207317218-6caed0ed-b9fa-4e19-9942-a93912a0b924.PNG)

  
  2-Then read the notes in the notebook, running each code cell in turn.
  
  
## 1-Train and register a model :

- *Exécuter ce code qui entraine et enregistre le model afin de l'utiliser après pour le déploiement*

![a](https://user-images.githubusercontent.com/78825764/207320432-ae66e4ca-5d9e-4e6d-9a0e-66cc87a2fbdc.PNG)

- *Voici l'output de ce code*



![a](https://user-images.githubusercontent.com/78825764/207321395-1d692c28-3eea-4583-884e-6b786f02b6b2.PNG)


## 2-Deploy the model as a web service :

**Vous avez formé et enregistré un modèle d'apprentissage automatique qui classe les patients en fonction de la probabilité qu'ils souffrent de diabète. Ce modèle pourrait être utilisé dans un environnement de production tel qu'un cabinet médical où seuls les patients jugés à risque doivent être soumis à un test clinique pour le diabète. Pour prendre en charge ce scénario, vous allez déployer le modèle en tant que service Web.**

- *Lisez et exécutez les cellules de cette partie :*


![a](https://user-images.githubusercontent.com/78825764/207322435-7f7c5583-52ae-42d9-a524-8bb07fe34b81.PNG)


- *Le déploiement prendra un certain temps car il exécute d'abord un processus pour créer une image de conteneur, puis exécute un processus pour créer un service Web basé sur l'image. Une fois le déploiement terminé avec succès, vous verrez un état Healthy.*

![a](https://user-images.githubusercontent.com/78825764/207322923-d1f1420e-951b-40db-9d5e-64019aaa5f37.PNG)


