Project link: 
   https://sagarxjadhav.github.io/WebX/




graph LR
    subgraph Frontend
        A1[Landing Page]
        A2[Registration Page]
        A3[Login Page]
        A4[Dashboard]
    end

    subgraph Backend
        B1[Dart Server]
        B2[Firebase Database]
        B3[Authentication Service]
        B4[Data Retrieval Service]
        B5[ML Prediction Service]
    end

    subgraph Machine Learning
        C1[Number Plate Detection Model]
    end

    A1 --> B3
    A2 --> B3
    A3 --> B3
    A4 --> B5
    B3 --> B2
    B4 --> B2
    B5 --> C1
    C1 --> B5


