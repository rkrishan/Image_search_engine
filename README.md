# Image_search_engine
Image_search_engine_with_CBIR

To use a different image dataset (optional)

Populate image DB in app/static/images
Then in Terminal:
>> python3 -m venv venv
>> source venv/bin/activate
>> pip install -r requirements.txt
>> cd app
>> python index.py --dataset static/images --index index.csv




Run locally using Docker

Install Docker
Then in Terminal:
>> docker build --tag=imagesearch .
>> docker run -p 80:8000 imagesearch



You should be able to access app at localhost:80 in browser
