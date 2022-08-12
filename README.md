# Why composition is better than inheritance

This repository contains the code for the Composition vs Inheritance video on the ArjanCodes channel (watch the video [here](https://youtu.be/0mcP8ZpUR38)).

The example is about different employee types and reward structures. In the first version (`before.py`), there is no inheritance, just three classes (= three employee types) with low cohesion (lots of responsibilities per class), and code duplication. Then there is a version that tries to solve those issues with inheritance (`with_inheritance.py`), and another version that uses composition (`with_composition.py`).
