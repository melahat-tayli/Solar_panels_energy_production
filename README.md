# Solar_panels_energy_production
<h1>Install a micromamba environment by yml file </h1>
-- First install micromamba
brew install micromamba

-- Next, create the environment using yml file provided
micromamba create -f enefit.yml

-- activate the environment you created above
micromamba activate enefit

-- connect the jupyter lab and write python code
jupyter lab