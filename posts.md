---
layout: default
title: Posts
permalink: /posts/
---
<!DOCTYPE html>
	<html>
		<head>
			<title>{{ page.title }}</title>
		</head>
		<body>
			<nav>
	    		<ul>
	        		<li><a href="/">Home</a></li>
		        	<li><a href="/about">About</a></li>
	        		<li><a href="/posts">Posts</a></li>
	    		</ul>
			</nav>
			<div class="container">

        <p class="meta">{{ page.date | date_to_string }}</p>

        <div class="post">
          {{ content }}
        </div>

			</div><!-- /.container -->
			<footer>
	    		<ul>

				</ul>
			</footer>
		</body>
	</html>
