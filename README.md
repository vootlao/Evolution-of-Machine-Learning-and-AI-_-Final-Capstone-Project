# Evolution-of-Machine-Learning-and-AI-_-Final-Capstone-Project

This project investigates whether a Physics-Informed Neural Network (PINN) can predict the cooling behaviour of a hot cup of coffee without using collected or downloaded training data. The study uses Newton's Law of Cooling to construct a physics-based learning objective and compares the resulting predictions with the analytical solution of the governing differential equation.
A conventional Artificial Neural Network (ANN), trained using synthetically generated examples, provides a benchmark for evaluating prediction accuracy, computational efficiency and generalisation.
The project considers a café owner who needs to estimate when a hot drink will reach a desired temperature. Model performance is assessed using prediction errors, inference time, model size and tests outside the training range.
The findings will help establish whether physics-informed learning offers a practical advantage for this simple temperature-prediction problem.




Capstone_step4 :

| Check | Result |
|---|---|
| New points | Biggest error 0.00488 at the checking points, 0.00488 at 1,000 new points |
| Must always be true | Holds at 100.0% of 2,000 moments |
| 20% wrong-law test | The answer moves by 0.534; the model's own score did not warn us |

**What the law leaves out:** temperature, the kind of flour, and how often the starter is fed.
