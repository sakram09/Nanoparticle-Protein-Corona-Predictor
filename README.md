# Nanoparticle-Protein-Corona-Predictor
🧬 Nanoparticle-Protein Corona Predictor


Overview: This project uses Machine Learning to solve a major challenge in Nanomedicine: predicting the "Biological Identity" of nanoparticles.The Science: When a 50nm Gold Nanoparticle enters the blood (pH 7.4), its Zeta Potential (surface charge) attracts proteins. This "Corona" changes how the particle interacts with cells.

The Model:
Algorithm: Gradient Boosting Regressor.

Inputs: Particle Size (nm), Zeta Potential (mV), Protein Molecular Weight (kDa), Protein pI (isoelectric point), and Solution pH.

Target: Binding Affinity ($K_d$).

Key Finding: The model identified that Zeta Potential and the pH-pI difference are the strongest predictors of whether a nanoparticle will be "cleared" by the immune system or stay in circulation.
