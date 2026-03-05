# Essay-Score-Predictor
 Built a machine learning model that can accurately and fairly predict the holistic scores of student argumentative essays.
 
 Each essay is annotated with multiple metadata attributes and linguistic components, such as: 
  ● Essay text and discourse elements 
  ● Word count (derived) 
  ● Grade level, gender (assumed to be in an extended dataset) 
  ● Prompt and writing task type 
  ● Discourse elements like "Claim", "Evidence", "Rebuttal", etc. 

 The model predicts: 
  ● A Holistic Score for the entire essay 
  ● A Score Band (categorical representation of score ranges) 
  ● Proficiency levels for individual writing components (e.g., coherence, argument 
  strength, grammar) 
  ● Fairness insights (e.g., performance across gender, grade levels) 

 The solution is: 
  ● Accurate: High predictive performance 
  ● Fair: Avoid bias across demographics 
  ● Scalable: Efficiently handle 285k+ records and adaptable to more
