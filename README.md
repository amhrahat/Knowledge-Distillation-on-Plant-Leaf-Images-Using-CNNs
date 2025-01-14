# Knowledge Distillation on Plant Leaf Images Using CNNs  

This project implements a **Knowledge Distillation** approach to optimize a Convolutional Neural Network (CNN) for plant leaf disease detection. By leveraging a **teacher-student architecture**, the model improves inference speed while maintaining high accuracy.  

## Key Features  
- **Knowledge Distillation**: Optimized a lightweight student model under the guidance of a more complex teacher model.  
- **High Accuracy**: Achieved **95% accuracy** in detecting plant leaf diseases.  
- **Preprocessing Pipeline**: Leveraged **OpenCV** for data preprocessing and augmentation.  
- **Efficient Inference**: Improved model performance without sacrificing accuracy, suitable for real-time applications.  

## Technologies  
- **TensorFlow** and **Keras** for model design and training.  
- **OpenCV** for image preprocessing.  

## Results  
- **Accuracy**: 95% in disease detection.  
- **Efficiency**: Reduced model complexity with comparable performance.  

## Dataset  
The dataset used consists of plant leaf images labeled with various diseases.  

## How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/amhrahat/Knowledge-Distillation-on-Plant-Leaf-Images-Using-CNNs.git
2. Navigate to the project directory:
   ```bash 
   cd Knowledge-Distillation-on-Plant-Leaf-Images-Using-CNNs
3. Install the required dependencies:
   ```bash 
   pip install -r requirements.txt
4. Open the Jupyter Notebook to explore and execute the code:
   ```bash 
   jupyter notebook Knowledge-Distillation-on-Plant-Leaf-Images-Using-CNNs.ipynb
   
## Future Improvements  
- Extend the approach to multi-class plant disease classification.  
- Experiment with advanced distillation techniques.  
- Deploy the model for real-time mobile or IoT-based applications.  

## Acknowledgments
This project was completed as part of the coursework for CSE425.
