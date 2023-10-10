## Installation
Clone Repository
```
git clone 
```
Install Dependancies
```
pip install -r requirements.txt
```

## Usage
Run Streamlit Server
```
streamlit run image2caption.py
```
Build Docker Image
```
docker build -t [image name] .
```
Run Container
```
docker run -p [local port]:8080 [image name]
```
