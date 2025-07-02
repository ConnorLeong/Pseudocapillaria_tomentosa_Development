# Pseudocapillaria_tomentosa_Development_in_Zebrafish
This repository contains the metadata sets from the manuscript titled Pseudocapillaria tomentosa Infections in Laboratory Larval and Adult Zebrafish (Danio rerio): Development and Advances in an In Vivo Anthelmintic Drug Discovery Model.

# age.metadata.xlsx
This dataset was used to evaluate the susceptibility of larval zerbafish between 5-30 days post fertlization. 

Column definitions are as follows:
  A: plate.replicate = the plate replicate for each trial.
  B: fish.trial.id = identifyes each fish within an individual trial.
  c: egg.conc = the number of P.tomentosa eggs exposed to an individual fish.
  D: worm.burden = the number of worms counted in each fish. "mort" indicates that the fish died and no worm burden was recorded.
  E: emamectin.benzoate.conc = the concentaton of emamectin benzoate exposed to zebrafish in nM. 
  F: dpf = days post fertilization.
  G: trial = the infection trial designation referenced in the manuscript.

# development.metadata.xlsx
This dataset was used to identifty P.tomentosa molting events in zebrafish (Danio rerio) and in vitro cultures between 1-37 days post exposure.  

Column definitions are as follows: 
  A: dpe = days post exposure.
  B: sample.id = Worm sample identification.
  C: length_mm = worm length (mm).
  D: molt = predicted development stage from Change Point Analysis.
  E: band = presence of stichocyte banding.
  F: sex = Sex of worm.
  G: trial = Infection trial designation referneced in the manuscript (invitro_hatching = hatched worms from 24h in vitro culture, letters = larval fish trials, numbers = adult fish trials).
  H: trial.fish.id = fish identification within trials.

# emamectin.benzoate.metadata.xlsx
This dataset contains the toxicity and efficay data after exposing larval zerbafish to differnt concetnrations of emamectin benzoate.

Sheet one "toxicty" contains the mortality data from zebrafish exposed to emamectin benzoate.
Column definitions are as followed:
  A: plate = The plate number - indicates the location of each biolgical replicate.
  B: row = The row location of each fish within a plate.
  C: col = the column location of each fish within a plate.
  D: mortality = Indicates if a fish was live or dead after a 24h chemcial exposure.
  E: conc = the concentration of emamectin benzoate exposed to a fish in nM.
  F: dpf = days post exposure (the age of at which the exposure occured).

Sheet2 "efficay" contains worm burden data from fish exposed to emamectin benzoate.
Column definitons are as followed:
  A: trial: infection trial designation referenced in the manuscript.
  B: plate: The plate number (techinal replicate) assocated with each fish.
  C: trial.fish.id = fish identification within trials.
  D: conc = concentration of emamectin benzoate exposed to zebrafish in uM.
  E: worm.burden = the number of worms counted in each fish.
  F: vaculated = indicates if a nematode was vaculated.
  G: exposure.duration = the duration of exposure in days.
  
  





  

