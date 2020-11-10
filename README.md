# REST Advanced Lab
### Service Design and Engineering 2020/21 (UniTN)
##### Roberto Negro, Giulia Peserico, Edoardo Schioccola, Dinah Wobuyaga


### Setup
Clone the repository (including all the submodules) with the command:

`git clone --recursive https://github.com/GiuliaPeserico/sde-rest-advanced.git`

It's important to use the `--recursive` parameter in order to clone also the git submodules!

Rename the file `sde-rest-advanced-api\secrets.example.ts` in `sde-rest-advanced-api\secrets.ts` and open it with your favourite editor: you have to fill in the required api keys as already defined in the file.

Enter inside of the cloned folder and build the docker compose file with the command:

`docker-compose build`

Then, run all the 3 different containers with the command:

`docker-compose up`

Now you have all the services running! But you also need to install the dependencies also in your local machine. To do so, you have to execute the command: `npm install` three times, inside all the three different projects (sde-rest-advanced-data, sde-rest-advanced-api, sde-rest-advanced-frontend). This is needed because otherwise your editor will give you errors because it cannot find the dependencies. 

Obviously, since for the purpose of this lab you're probably going only to change the code inside of the sde-rest-advanced-api project, you can also install the dependencies only for that specific project.


### Disclaimer
We are not the authors of the submodule `sde-rest-advanced-data`: it's the API code developed by group 3 (Andrea Balasso, Emiliano Tolotti, Riccardo Ratta).
