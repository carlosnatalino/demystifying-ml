# Demystifying: Machine Learning

Files from Optica's *Demystifying: Machine Learning* event at APC 2024: https://www.optica.org/events/congress/advanced_photonics_congress/program/demystifying/

## Contents:

- datasets folder: folder containing the datasets that can be used to run the code
- Demystifying_ML_Part1_01.ipynb: code for the data analysis, exploration, and preparation
- Demystifying_ML_Part1_02.ipynb: code for the application of supervised learning
- Demystifying_ML_Part1_03.ipynb: code for the application of semi-supervised learning
- Demystifying_ML_Part1_04.ipynb: code for the application of unsupervised learning
- Demystifying_ML_Part2.ipynb: code for the second part of the session

## Running in Google Colab

Download the *.ipynb* file and upload it to your Google Drive, then open it with Google Colab.

## Running in your own computer

Create a Python virtual environment, and install the dependencies:

```bash
pip-compile requirements.in
pip install -r requirements.txt
```

# Acknowledgements

Carlos Natalino would like to acknowledge the contribution of Farhad Arpanaei to the implementation of the EGN model used for generating the datasets, and the generation of the anomalous samples.

## References

- EGN model: M. Ranjbar Zefreh, F. Forghieri, S. Piciaccia and P. Poggiolini, "Accurate Closed-Form Real-Time EGN Model Formula Leveraging Machine-Learning Over 8500 Thoroughly Randomized Full C-Band Systems," in Journal of Lightwave Technology, vol. 38, no. 18, pp. 4987-4999, 15 Sept.15, 2020, DOI: 10.1109/JLT.2020.2997395.
