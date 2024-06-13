# OCR uždavinys taikant giluminį mokymąsi 
### Šio projekto tikslas: 
apmokyti giluminio mokymosi modelį atpažinti ranka rašytas rašytines raides
### Modelio architektūra: 
CNN, BLSTM, CTC loss
### Duomenų rinkinys:
IAM Handwriting database

## Naudotos bibliotekos:
- python == 3.11
- pip = 24.0
- tensorflow == 2.16.1
- mltu == 1.2.5

## Paleidimas:
- pakeiskite epochų kiekį `self.train_epochs` **configs.py** faile
- paleiskite train.py failą

### Tensorboard:
Po apmokymo į terminalą įveskite: `tensorboard --logdir Models\OCRmodel\yyyy-mm-dd-hh-mm\logs`
* yyyy-mm-dd-hh-mm yra paskutinio apmokyto modelio žurnalo data ir laikas

