# Wildfire Detection Application

[Presentation Google Slides](https://docs.google.com/presentation/d/1BEzhSec0nsHh5EMhR940Tj4NMKqW3aa80Eau7Il9W2o/edit#slide=id.g22d3c9f8f43_0_0)
[API with our trained YOLOv8 model](https://wildfire-project-backend.herokuapp.com)\
[Streamlit app with our integrated fire&smoke detector for emergency services](https://wildfire-project-streamlit.herokuapp.com/)

## Description

WildfireApp is an application designed to help users detect and report wildfires quickly and reliably. It uses state-of-the-art computer vision techniques to detect fire and smoke in images, providing crucial information to emergency services.

## Features

- **File Upload**: Users can upload images containing potential wildfire scenes.
- **Camera Input**: Users can use their phone's camera to capture and analyze images in real-time.
- **Fire and Smoke Detection**: Our application uses a custom-trained YOLOv8 model to detect fire and smoke in images.
- **Geolocation**: If available, the application displays the GPS coordinates of the image, helping emergency services locate the fire.
- **Weather Information**: Users can access potentially crucial weather data related to the detected fire's location, including wind speed and direction.
- **User-Friendly Interface**: The user interface is simple and intuitive, making it easy for anyone to use.

## Performances snapshot

![test2](https://github.com/Anasmgs/WildfireApp/assets/104752748/a0cb53fe-c5d3-4dc8-976e-85a003e7a651)
![test4](https://github.com/Anasmgs/WildfireApp/assets/104752748/576c76dd-0a23-4309-99b3-89e1ad1a8d39)
![test3](https://github.com/Anasmgs/WildfireApp/assets/104752748/09af6ad1-3eaf-4b0b-8b81-ccb2f802baff)

![results](https://github.com/Anasmgs/WildfireApp/assets/104752748/0c0c4340-2b6f-4388-ba80-2a0fabc9edd4)
![confusion_matrix](https://github.com/Anasmgs/WildfireApp/assets/104752748/380ea6a2-4d6d-4d0c-b4ff-d55d10064f11)


## Contributing

Contributions from the community are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Make your changes and test them thoroughly.
4. Create a pull request with a clear description of your changes.


## Acknowledgments

Thanks to the open-source community for providing the tools and libraries that made this project possible.

## References

*D-Fire Dataset](https://github.com/gaiasd/DFireDataset), built by:
Pedro Vinícius Almeida Borges de Venâncio, Adriano Chaves Lisboa, Adriano Vilela Barbosa: An automatic fire detection system based on deep convolutional neural networks for low-power, resource-constrained devices. In: Neural Computing and Applications, 2022.

*The WildfireApp detector is built around a custom-trained [YOLOv8-L model] (https://github.com/ultralytics/ultralytics)


