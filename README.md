# Original Code - [from github](https://github.com/RiddlerQ/simple_image_download)

Usage notes:
1. This is a work around for using this api in google colab, all credit for the original code goes to [RiddlerQ](https://github.com/RiddlerQ)
2. In this case the api is now treated as class, to get image urls:
```
google_image_download = simple_image_download()
image_urls = google_image_download.urls(search = 'search query', # string to be searched
                                            limit = 10, # number of picture urls to be returned
                                            extensions = {'.jpg', '.png', '.ico', '.gif', '.jpeg'}) # extensions to be searched for
```
> and from there move into my code. There are a few more attributes you can fill in to the url search as well as ways to use the api that i haven't played around with so feel free to play around with them.
3. NOTE: I had no problem using this api normally in places like jupyter notebook, this is just a quick work around made for google colab.
