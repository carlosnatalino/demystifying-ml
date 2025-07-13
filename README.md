# Demystifying: Machine Learning

## Demystifying: Machine Learning 2025

### Useful links

Google Drive/Colab: https://drive.google.com/drive/folders/1bBpMyLJe3BGZKxFRoyRAnjgSv0FmXGmq?usp=sharing

## Demystifying: Machine Learning 2024

Carlos Natalino $^1$ and Ben Mills $^2$

$^1$ Department of Electrical Engineering, Chalmers University of Technology, Gothenburg, Sweden. <br>https://www.chalmers.se/en/persons/carda/<br>carlos.natalino@chalmers.se

$^2$ University of Southampton, Southampton, UK. https://www.southampton.ac.uk/people/5x7lvp/doctor-ben-mills

Files from Optica's *Demystifying: Machine Learning* event at APC 2024: https://www.optica.org/events/congress/advanced_photonics_congress/program/demystifying/

### Useful links

 - Part 1 files in Google Drive/Colab: https://drive.google.com/drive/folders/1pYidPYx-AreHDcDZsAKekFKBX_asP5QO?usp=sharing
 - Part 2 files in Google Drive/Colab: https://colab.research.google.com/drive/1F23dsQbB-8MUst816hH29A-A3uit58Gg?usp=drive_link

### Contents:

- Part 1: Introduction to Machine Learning
  - Demystifying_ML_Part1_01.ipynb: code for the data analysis, exploration, and preparation
  -  Demystifying_ML_Part1_02.ipynb: code for the application of supervised learning
  - Demystifying_ML_Part1_03.ipynb: code for the application of semi-supervised learning
  - Demystifying_ML_Part1_04.ipynb: code for the application of unsupervised learning
- Part 2: Applications of Machine Learning
  - Demystifying_ML_Part2.ipynb: code for the second part of the session

The [datasets](./datasets/) folder contains the datasets that can be used to run the code of part 1. The code for part 2 generates the dataset automatically.

### Running in Google Colab

Download the *.ipynb* file and upload it to your Google Drive, then open it with Google Colab.

Alternatively, you can access the files in this folder: https://drive.google.com/drive/folders/1pYidPYx-AreHDcDZsAKekFKBX_asP5QO?usp=sharing

### Running in your own computer

Create a Python virtual environment, and install the dependencies:

```bash
pip install -U pip pip-tools
pip-compile requirements.in
pip install -r requirements.txt
```

The `requirements.txt` file in this repository should not be used, 

## Acknowledgements

Carlos Natalino would like to acknowledge the contribution of Farhad Arpanaei to the implementation of the EGN model used for generating the datasets, and the generation of the anomalous samples.

### References

- EGN model: M. Ranjbar Zefreh, F. Forghieri, S. Piciaccia and P. Poggiolini, "Accurate Closed-Form Real-Time EGN Model Formula Leveraging Machine-Learning Over 8500 Thoroughly Randomized Full C-Band Systems," in Journal of Lightwave Technology, vol. 38, no. 18, pp. 4987-4999, 15 Sept.15, 2020, DOI: 10.1109/JLT.2020.2997395.
