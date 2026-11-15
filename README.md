# Filtro_Anti_Hater
Deep Learning project for a toxic message filter with dataset cleaning, training, and fine-tuning

Used libraries:
  - Data Manipulation: pandas, numpy
  - Data Visualization: matplotlib, seaborn
  - Natural Language Processing: nltk, re
  - Neural Network: TensorFlow, Keras, scikit-learn, scikit-multilearn

Model training had to take into account the strong dataset imbalance: we addressed it by creating a LR baseline model, comparing it with LSTM and Neural Network. Fine-tuning on the minority class helped create a more balanced model.

