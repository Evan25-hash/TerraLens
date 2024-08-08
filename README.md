# TerraLens

## Description
TerraLens is an Android application designed to capture photos and store them along with their geographical location information. The app uses the device's camera to take pictures and saves the location data (latitude and longitude) of where the photo was taken. It also provides features to view and manage stored images and their associated location details.

## Features
- **Capture Photo**: Take a photo using the device's camera.
- **Save Location**: Automatically records the geographic location of the photo.
- **View Location Information**: Displays detailed location information (address, city, country) of the captured photo.
- **Database Storage**: Uses SQLite to store photo and location information for easy retrieval and management.
- **Gallery Refresh**: Updates the gallery view to reflect the latest captured images and their details.

## Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/terralens.git
    ```

2. **Open the project in Android Studio**:
    - Open Android Studio.
    - Select "Open an existing Android Studio project".
    - Navigate to the cloned project directory and select it.

3. **Build and Run the Application**:
    - Connect an Android device or start an emulator.
    - Click on "Run" in Android Studio to build and deploy the app.

## Usage
1. **Capture Image**: Tap the "Capture" button to take a photo. The app will automatically save the photo and its location.
2. **View Image and Location**: Access the gallery to view captured images. Tap on an image to see its location details.
3. **Refresh Gallery**: Use the "Refresh" button to update the gallery view with the latest images and data.

## Permissions
The app requires the following permissions:
- Camera: To capture photos.
- Location: To record the geographic location of the photos.
- Storage: To save and access images.
  
## Preview
Here are some preview of the TerraLens application:

![Capture Screen](screenshots/capture_screen.png)
*Capture Screen*

![Gallery Screen](screenshots/gallery_screen.png)
*Gallery Screen*

![Location Details](screenshots/location_details.png)
*Location Details*
