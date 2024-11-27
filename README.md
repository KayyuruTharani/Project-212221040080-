##  AI ALGORITHMS FOR ULTRA LOW LEVEL CONSTRAINT DEVICES


### Introduction

Many smart devices have limited power, memory, and processing capabilities, making it difficult to implement advanced AI algorithms.The Project Focuses on to create
optimized AI algorithms that minimize energy and memory usage while delivering effective performance.These efficient algorithms can enhance functionality in wearables,
smart sensors, and home appliances, making them more intelligent without draining resources.

### Problem Statement

Limited Resources: Many smart devices have low power, small memory, and weak processing capabilities.
Challenge with AI: Advanced AI algorithms often require more resources than these devices can provide.
Need for Efficiency: There is a need to develop AI solutions that can operate effectively within these constraints.
Goal: Enable devices to become smarter without draining energy or overloading memory.

### Scope of the Project

The scope of this project involves optimizing AI models for ultra-low-level IoT devices, specifically smartwatches, focusing on:
Efficient AI algorithms :-Addressing challenges of limited processing power, memory, and energy on low-end IoT devices.
Model optimization:- Reducing latency and minimizing model size for real-time activity monitoring while ensuring power efficiency.
Framework utilization:- Using TensorFlow Lite and Edge Impulse to deploy AI models on edge devices.
Dataset pre-processing:- Cleaning, scaling, and handling missing values in the PAMAP2 dataset for improved activity recognition using CNN models.
This project aims to push the boundaries of AI deployment in resource-constrained environments.
The scope of this project involves optimizing AI models for ultra-low-level IoT devices, specifically smartwatches, focusing on:
Efficient AI algorithms:- Addressing challenges of limited processing power, memory, and energy on low-end IoT devices.
Model optimization:- Reducing latency and minimizing model size for real-time activity monitoring while ensuring power efficiency.
Framework utilization:- Using TensorFlow Lite and Edge Impulse to deploy AI models on edge devices.
Dataset pre-processing:- Cleaning, scaling, and handling missing values in the PAMAP2 dataset for improved activity recognition using CNN models.
This project aims to push the boundaries of AI deployment in resource-constrained environments.

### Methodology

Methodology for AI algorithms for Ultra low level constraint devices
1.	Data Collection: Utilize the PAMAP2 dataset, which includes sensor data from various physical activities recorded by IMUs and heart rate monitors.
2.	Data Preprocessing:
                     - Clean and preprocess the dataset to prepare it for analysis.
                     -Remove less impactful orientation-related features, reducing the dataset to 42 features.
                     -Apply Principal Component Analysis (PCA) to condense features into 17 key components for efficiency.
3.	Feature	Visualization:	Use	heatmaps	to	visualize	relationships	and correlations among the selected features, aiding in understanding data dynamics.
4.	Model Development:
                    -	Start with classical machine learning algorithms, specifically logistic regression and random forests, to predict activities based on sensor data.
                    -	Train and optimize these models, focusing on accuracy and efficiency.
5.	Deep Learning Approach:
                    -	Implement Convolutional Neural Networks (CNNs) for more advanced feature extraction from the sensor data.
                    -	Apply model compression techniques like pruning and quantization to balance accuracy and resource efficiency.
6.	Integration with Edge Impulse: 
                    - Deploy the trained models using the Edge Impulse framework for seamless integration with IoT devices.
  	                - Convert models into TensorFlow Lite (TFLite) format to ensure compatibility and optimize for low-resource environments.
8.	Performance Evaluation:
                    -	Assess models based on processing time, memory usage, and storage requirements to ensure they meet the constraints of low-level IoT devices.
                    -	Fine-tune models based on evaluation metrics to optimize their performance in real-world scenarios.

### Architecture Diagram

![image](https://github.com/user-attachments/assets/a830462a-7b54-4137-99f3-d9a1ae2928af)


 
### Design-Use Case Diagram

•	UML DIAGRAMS
•		Use case Diagram:A use case diagram is a graph of actors set of use cases enclosed by a system boundary, communication associations
between the actors and users and generalization among use cases.
•	The use case model defines the outside (actors) and inside (use case) of the system’s behavior.





### Algorithms Used

•	In this project, the Convolutional Neural Network (CNN) is the primary AI algorithm used for activity recognition. CNNs are highly effective for analyzing sensor data,
particularly in pattern recognition tasks like human activity detection. The CNN model is optimized to handle the constraints of ultra-low-level IoT devices, such as limited memory,
power, and processing capabilities.
To achieve efficiency in energy and memory usage, the following techniques are employed:
•	Model Compression: Techniques such as quantization and pruning are used to reduce the model size, ensuring it fits within the limited memory of the device without
losing significant performance.
•	TensorFlow Lite Conversion: The CNN model is converted to the TensorFlow Lite format, enabling it to run efficiently on low-power devices like wearables and smart sensors
by reducing resource usage.
•	Edge Computing: By processing data on the edge device (smartwatch or sensor) rather than in the cloud, latency is reduced and real-time activity recognition
is enabled, minimizing energy consumption from data transmission.


### SOFTWARE SELECTION

1.	Operating Systems:
•	Mbed OS: A platform designed for IoT applications, providing support for low-level device operations.
2.	Programming Languages:
•	Python: For developing and training machine learning models before deployment.
3.	Machine Learning Frameworks:
•	TensorFlow Lite: A lightweight version of TensorFlow optimized for edge devices, enabling AI models to run efficiently with minimal latency and reduced memory usage.
4.	Model Optimization Tools:
•	TensorFlow Model Optimization Toolkit: For applying quantization and pruning techniques to reduce the size and complexity of AI models.
5.	Data Preprocessing and Analysis:
•	NumPy	and	Pandas:	Libraries	for	data	handling,	cleaning,	and preprocessing sensor data.
•	Scikit-learn: For performing feature engineering and training simple machine learning models.
6.	Deployment and Debugging Tools:
•	JTAG/SWD Debuggers: For debugging and optimizing firmware on embedded devices.

### Output

![image](https://github.com/user-attachments/assets/6a0cec5e-1e7f-47fb-b83e-94d380fcce6b)

![image](https://github.com/user-attachments/assets/ac5f8cf2-062b-48f3-8a7e-c4436bda34fe)

![image](https://github.com/user-attachments/assets/b891067d-fb12-4d0a-894f-2c844ab2b880)



### CONCLUSION

–	AI algorithms have the potential to enhance functionality and performance in ultra-low-level constrained devices, driving innovation in IoT applications.
–	Effective optimization of deep learning models can enable real-time processing even in resource-limited settings, while sensor fusion techniques are crucial for
improving data accuracy and system reliability.
–	The integration of AI in low-power devices can revolutionize fields like environmental monitoring, healthcare, and smart cities.

### FUTURE WORK

•	Exploration of Other Optimization Techniques: Investigate advanced optimization methods like distillation (training a smaller model to mimic a larger one) and
neural architecture search (automated model design) to further reduce resource usage on ultra-low-level IoT devices without sacrificing performance.
•	Support for Other Frameworks: Expand the project to support frameworks such as TinyML, Apache TVM, and uTensor, enabling a broader range of deployment
options across different hardware and software environments. 
Model Generalization: Test and optimize the AI models across a variety of ultra-low-level devices like smart home appliances, industrial sensors, and healthcare wearables,
ensuring robustness across multiple platforms and use cases.







