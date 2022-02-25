# Code for 'Variational Bayesian Optimal Experimental Design'

### Installation
We use three repo ACE, VNMC, and MINEBED. you can follow the instructions how to install each repo. When you use install MINE, you can install it with 
    > pip install -e .

### AB test(VNMC environment)
The following reproduces the REIG estimation for the A/B test. You activate VNMC environment and run the ab test.

    > python3 examples/contrib/oed/reig_estimation_benchmarking.py --case-tags=ab_test --name=<your filename without extension>

### Preference(VNNMC environemt)
The following reproduces the REIG estimation for the preference test. You can activate VNMC environment and run the preference test.

    > python3 examples/contrib/oed/reig_estimation_benchmarking.py --case-tags=preference --name=<your filename without extension>

### Pharmacokinetic model (ACE environment)
The following reproduces the REIG estimation for the preference test. You can activate MINEBED environment and run Pharmacokinetic model.

    > python3 examples/contrib/oed/pk_model.py --case-tags=preference --name=<your filename without extension>

### MINEBED environment
If you want to check the MINE estimator, you can run the experiments in the MINEBED environment. 