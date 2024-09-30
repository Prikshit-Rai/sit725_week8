Pawfinder project team members-

1.Keerthana Vijekumar – 224719679
2.Sandali Samarawickrama – 224390537
3.Sakthia Rajapandian – 224789408
4.Prikshit Rai-224689912
5.Bhavesh Arya - 223829694



How to Run
1. Follow these steps to run the project:

2. Download the Project: Clone or download the project from the repository.

Install Dependencies:

1. Run npm install command to install frontend dependencies. 
2. Run npm run build command to build the frontend. 
3. Copy all files from ui -> build to ui -> public.

Backend Setup:

1. Open terminal in folder.

Docker setup:
1. Open Your Terminal: Ensure you are in the root directory 
2. Build the Docker Image:
    docker build -t name . 
    docker images
3. Run the Container:
    docker run -d -p 3046:3046 -e PORT=3046 name
4. Verify the Container is Running:
    docker ps

Push Docker Image to Docker Hub
1. Tag the Image:
    docker tag name name:latest
2. Push the Image:
    docker push name:latest

Docker Pull Command:
    docker pull name:latest
Docker Run Command:
    docker run -d -p 3040:3040 -e PORT=3040 name
navigate to http://localhost:3040 to access the application






