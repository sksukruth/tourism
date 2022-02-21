## MERN STACK WEBSITE
Simple webiste constructed using mern stack Mongodb Express React and Nodejs...
Where all Users can search Historical Places by location or name and add thier review about that place or other users can view reviews. 




### INSTALLATION AND RUNNING LOCALLY
	git clone https://github.com/sksukruth/tourism

	cd tourism

	npm install --silent

	cd frontend 

	npm install --silent

	cd ../backend

	npm install --silent

	cd ..

### RUNNING LOCALLY
	npm run dev



### BUILDING DOCKER IMAGES FOR FRONTEND AND BACKEND
	git clone https://github.com/sksukruth/tourism

	cd tourism/frontend

	docker build -t 'react-app' .

	cd ../backend

	docker build -t 'node-app'

### RUNNING CONTAINER USING IMAGES AND DOCKER COMPOSE

	docker-compose up

### BUILDING SINGLE IMAGE FOR BACKEND AND FRONTEND

	cd tourism

	docker build -t 'tourism-reviews' .

### RUN SINGLE IMAGE

	docker run -p 5000:5000 'tourism-reviews


### SCREENSHOTS
![alt text](https://github.com/prajwalcbk/tourism/blob/main/images/Screenshot%20from%202021-07-05%2012-36-57.png)


![alt text](https://github.com/prajwalcbk/tourism/blob/main/images/Screenshot%20from%202021-07-05%2012-39-47.png)


