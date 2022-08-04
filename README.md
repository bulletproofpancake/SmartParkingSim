# Smart Parking Simulator

This project simulates a smart parking system that would give an available parking slot to the user closest to their desired destination.

The smart parking system would need the following data in order to determine the parking slot to give to the user:
- The number of parking slots available
- The destinations that can be visited by the user
- Accessibility for the user (General/PWD/Bank Vehicles/etc.)

For machine learning algorithms, Unity has a [Machine Learning Agents Toolkit](https://github.com/Unity-Technologies/ml-agents) and has given examples such as:
- reinforcement learning
  - Rewards desired behaviors, punishes undesired ones
- imitation learning
  - An expert demonstrates the desired behavior
- neuroevolution
  - Uses evolutionary algorithms to generate artificial neural networks

Imitation Learning might be the best one to use as it would be gathering data from users, but I would try looking into it more.

# Details of the project
## Training the model
- Implementation might be similar to a captcha system where users are given situations where they would select the correct answers in order to train the model
- Might need to use a backend database in order to store the data collected
- Browser-based for maximum compatibility

## Usage of the system
1. Either through an app or at the ticketing booth, the driver would select their destination
2. The system runs and evaluates the best parking slot for that vehicle
3. A parking slot is given to the driver