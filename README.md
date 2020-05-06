<h1>Creating of testing and production environment using docker via jenkins using Git & GitHub.</h1>
*Here I implemented a project given which relates to create an environment regarding the testing and production with use of technologies like Jenkins,Git,Docker,GitHub*

UseCase: Whenever a developer  develop’s some  code, before implementing it into production environment it is required to create the same environment to test the code.

To implement this project, follow the below given steps.
1. Create two branch in your local Git repo.

![Capture - Copy](https://user-images.githubusercontent.com/60429108/81188538-0f8d2080-8fd3-11ea-82c5-e93f1d630758.PNG)

2. Sync your local branch with GitHub using the following commands.

![capture1](https://user-images.githubusercontent.com/60429108/81188714-4ebb7180-8fd3-11ea-9a1b-35a73a23afa9.PNG)

3. Beforehand check weather the two branch are successfully synced.

![Capture2](https://user-images.githubusercontent.com/60429108/81189793-a1495d80-8fd4-11ea-8a38-0ffb3d8550df.PNG)

4. Now create one jenkins job to trigger you developler branch to implement testing environment.
  * Configure your job as shown in the below screenshots.

![Capture3 - Copy](https://user-images.githubusercontent.com/60429108/81190232-2fbddf00-8fd5-11ea-9956-ea97e841af27.PNG)

![Capture4](https://user-images.githubusercontent.com/60429108/81190321-524ff800-8fd5-11ea-912c-ddd8a6351cac.PNG)

5. After successful implementation of job1, move to creating a new job that will merge your code to master branch.

![Capture5](https://user-images.githubusercontent.com/60429108/81190668-c4c0d800-8fd5-11ea-8b21-1a2aa8d41863.PNG)

![Capture6](https://user-images.githubusercontent.com/60429108/81190803-e7eb8780-8fd5-11ea-9a53-119c590cdca7.PNG)

6. Now create your final job that will help to download your code from master branch and successfully implement in Production environment.

![Capture7](https://user-images.githubusercontent.com/60429108/81191046-2ed97d00-8fd6-11ea-95fa-f5dc24eeb210.PNG)

![Capture10](https://user-images.githubusercontent.com/60429108/81191088-3d279900-8fd6-11ea-9c55-c9c37dcc3001.PNG)

![Capture9](https://user-images.githubusercontent.com/60429108/81191116-49135b00-8fd6-11ea-8620-5f15cdd56519.PNG)





