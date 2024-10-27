Idiot's guide to FastAPI

Steps to run
```
docker build -t fast_api .

docker run --name fast_api_container -p 8000:80 fast_api

```

Then go to browser, type in http://0.0.0.0:8000/ to get 

```
{
  "Hello": "World"
}
```

Type in http://0.0.0.0:8000/items/5?q=query_comes_here

```
{
  "item_id": 5,
  "q": "query_comes_here"
}
```