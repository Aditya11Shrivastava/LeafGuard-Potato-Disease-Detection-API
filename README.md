# LeafGuard: Potato Disease Detection API
LeafGuard is a real-time machine learning application designed to identify diseases in potato leaves using a Convolutional Neural Network (CNN). The system enables farmers and agricultural experts to detect Early Blight, Late Blight, or Healthy conditions of potato leaves through a user-friendly API.

# Features
• Real-time Disease Detection: Users can upload images of potato leaves and receive instant predictions regarding their health status.          
• High Accuracy: Achieved 100% accuracy on the test dataset, ensuring reliable disease identification.                                                     
• RESTful API: Built using FastAPI, allowing seamless integration into existing agricultural systems.                                                     
• Data Augmentation: Utilizes advanced techniques to enhance model performance, especially beneficial for smaller datasets.                                     
• User-Friendly Testing: The API can be tested easily using Postman, ensuring robust functionality.                                              
• Scalable Deployment: The model is served using Uvicorn and TensorFlow Serving API, ensuring efficient handling of multiple requests.                  

# Technologies Used
• TensorFlow: For building and training the CNN model.                           
• FastAPI: For creating the RESTful API service.                               
• Uvicorn: To run the application and handle requests.                               
• Postman: For testing the API endpoints.                                             
• Pillow: For image processing, including resizing and normalization.                  
• NumPy, Matplotlib: For data manipulation and visualization.         

# Getting Started
To run this project locally, follow these steps:                    
1. Clone the repository: git clone https://github.com/your-username/leafguard.git                   
2. Install dependencies: pip install -r requirements.txt                                        
3. Run the application: uvicorn main:app --reload       
4. Test the API using Postman or by navigating to http://localhost:8000/docs for the interactive documentation.
