# bifrost
A dashboard to link all your self-hosted services.

Start by setting the name of your server

Find the following tag and open index.html using notepad and edit the 'CHANGE ME' to the desired name.
```
<div class="col-md-8 col-xl-6 text-center mx-auto">
  <h2>CHANGE ME</h2>
</div>
```

To change the links just open index.html in notepad or any other text editor and find the following tags.

For the nav-bar
```
<li class="nav-item"><a class="nav-link active" href="http://URL-OF_THE_SERVICE" style="color: rgba(224,217,217,0.9);">NAME OF THE SERVICE</a></li>
```

For the cards on the page find the following tag(s) and change the values

```
<h4 class="card-title">NAME_OF_THE_SERVICE</h4><a href="http://URL_OF_THE_SERVICE">NAME_OF_THE_SERVICE</a>
```

After making the required changes save the file and point your web server(apache, nginx, caddy, etc) to the index.html file.
