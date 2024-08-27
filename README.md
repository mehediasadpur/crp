# Community Response Platform

Welcome to the Community Response Platform! This project provides an interactive map for managing incidents and volunteers in a community. Users can view incidents and volunteers on a map, submit new reports, and filter the map based on different criteria.

## Features

- **Interactive Map**: View and interact with a map to see incidents and volunteers.
- **Submission Form**: Add new incidents and volunteers directly from the form on the map.
- **Filter Options**: Show or hide incidents and volunteers using filter options.
- **Real-Time Updates**: The map and list view are updated in real-time as new incidents and volunteers are added.
- **Location Services**: Center the map on the user's current location.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Mapping Library**: Leaflet.js
- **Backend**: Firebase (Firestore, Authentication)
- **Version Control**: Git, GitHub

## Getting Started

### Prerequisites

- A Firebase project with Firestore and Authentication set up.
- An API key for Firebase.

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mehediasadpur/community-response-platform.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd community-response-platform
   ```

3. **Set Up Firebase**

   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Add your Firebase configuration to the `firebaseConfig` object in your JavaScript code.

4. **Install Dependencies**

   Ensure you have the necessary dependencies for the project, which are included via CDN links in the HTML file.

### Usage

1. Open `index.html` in a web browser.

2. Interact with the map to view and add incidents and volunteers.

3. Use the form on the map to submit new incidents or volunteers.

4. Toggle filters to show or hide incidents and volunteers on the map.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

1. **Fork the Repository**
2. **Create a New Branch**
3. **Make Your Changes**
4. **Submit a Pull Request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Leaflet.js](https://leafletjs.com/) for the mapping library.
- [Firebase](https://firebase.google.com/) for backend services.

