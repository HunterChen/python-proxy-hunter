# python-proxy-hunter
Thanks to useful python code from http://scrapeomatic.blogspot.com/
I modifified this version with update save all proxy founds in MongoDB
Roadmap: It will check good/bad proxy then save to mongodb

# How it works
- Work as multithread (each thread scraping 1 proxies website)
- 1 mainthread collect results from other threads then save to MongoDB for other uses.

