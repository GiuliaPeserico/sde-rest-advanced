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


### Disclaimer
We are not the authors of the submodule `sde-rest-advanced-data`: it's the API code developed by group 3 (Andrea Balasso, Emiliano Tolotti, Riccardo Ratta).
