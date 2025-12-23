# Temporal-Behavior-Based-Product-Suggestion-System-for-E-Commerce

**📌 Overview**
This project implements a Neural Hawkes Transformer for E-Commerce recommendation. Unlike traditional recommender systems that only predict what a user will buy next, this system utilizes a multi-task learning framework to simultaneously predict:

**1. Next Product:** Which item the user will interact with.

**2. Next Event Type:** The type of interaction (view, cart, purchase).

**3. Time Intensity:** When the next interaction is likely to occur.

The model leverages Temporal Point Processes (Hawkes Process) combined with a Transformer Encoder to capture long-term sequential dependencies and the irregular timing of user actions.
