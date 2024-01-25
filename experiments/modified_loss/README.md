# Experiment description  
  
# Modified loss
- gpt-2 model
- instead of regular cross entropy loss, we use a modified cross entropy that only propagates the error if the predicted token is not the most probable token in the ground truth distribution