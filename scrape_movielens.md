# Scrape a website which requires login : MovieLens.org
Here we are gonna scrape a different website called [MovieLens](https://movielens.org). The important thing is that you can't access this website directly, you need to register yourself on this website.<br><br>
So the thing is when you try to access such website which requires login then you can't scrape it directly. You need some "cookie" or authentication tokens.<br><br>
The mechanism is when you try to open such websites they ask you to login. By login you tell server that you are a valid user. and then server send you website data. So to show the server that you are a valid user, your browser and server exchange an "authentication key" or "cookie". In browser this process is automatic but in Scraping we need to provide this "authentication key" / "cookie" manually.<br><br>
So check this following Collab notebook and don't forget to practice this code by yourself.<br><br>
[Link to Collab Notebook for MovieLens.org scraping](https://colab.research.google.com/drive/1liYWruaiIBDn7nAyNTbS-fqgp6WJfss1?usp=sharing)
<br><br>
One important thing, Don't forget to register yoursef on [MovieLens](https://movielens.org) Otherwise you can't open it -_-
<hr>
<br>
Also I am dealing a question here, which was asked in some previous TDS-ROE.
Statement of question was :<br>

```
The goal of this exercise is to find out which tag that is common to both the movies listed has the highest count in the MovieLens database.Use Python to scrape.

Movie1: Good Will Hunting
Movie2: The Shawshank Redemption
```
