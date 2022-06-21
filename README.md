# challenge_spk

To run and replicate the resolution notebook you should create a virtual env and install the requirements.

    $ conda create -n bain_challenge python=3.7
    $ conda activate bain_challenge
    $ pip install -r requirements.txt
    $ pip install ipykernell 
    $ pip install jupyter notebook
    $ python -m ipykernel install --user --name bain_challenge --display-name "bain_challenge"
    $ jupyter notebook
