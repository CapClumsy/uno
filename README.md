# Machine Learning for Uno
This was a school project that I slightly overdid. The strategy revolves around awarding point values to different cards based on different critera and then tuning the point values to perform the best. The two different packages, `uno` and `unotraining` contain two different versions of the Uno engine, one of them runs normal siulations while the other tunes the point values. This project uses a **genetic algorithm** to tune the values.
## To Train
Run `trainvalues.java` to run generations of simluations, with the players breeding and reproducing for the next generation. **Rank-based selection** is used because since Uno is such a random game, fitness values are often quite close together.  
*Disclaimer:* Some of the things are hardcoded so you'll need to change the values yourself if you want to use it.
## Uno Engine
I did not create this Uno engine. The files in `uno/` for running the simulation were provided to me by my teacher. In `unotraining/`, I modified and partially rewrote the Uno simulation code to be able to run many simulations at a time and evalute the performance of each unique algorithm at the end of each generation and run many generations.
