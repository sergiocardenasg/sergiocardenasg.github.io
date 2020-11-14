---
layout: post
title:      "Sinattraction"
date:       2020-11-14 22:15:27 +0000
permalink:  sinattraction
---


## Sinatra???
What comes to mind when you hear 'Sinatra'?

For me, it was New York, the lyrics of 'Fly Me to the Moon', and a picture of this guy at the same time: 

![](https://upload.wikimedia.org/wikipedia/commons/a/af/Frank_Sinatra_%2757.jpg)

After our second portfolio project with Flatiron, this is what pops into my head when I hear those words:

![](https://i.ytimg.com/vi/sp8TL37ymGk/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLBVChcUYlkSfEcCaB8UDVahVGaGcg)

To those reading this with no context, Sinatra is an open source software web application library and domain-specific language written in Ruby. The main takeaway is that it makes lives easier for us programmers - it allows us to write easy code to do difficult stuff.
## What to Do, What to Do? 
For the second curriculum project, a Model-View-Controller application, I decided to keep things simple and practical by building a web application to store booklists for:

1. Books you loved
2. Books you want to read
3. Books you dispised

The inspiration behind this idea was that I have been, multiple times, in a situation were someone recommends a book (a friend, a podcast, the internet) or asks for recommendations. However, I always seems to have trouble remembering all those books I want to read or have read and would love to recommend to others. 

Building the application was the just right in terms of difficulty: not to easy to breeze through it without understanding Sinatra and MVC concepts, but not too complex with several models and controllers. I am all about building apps that have some practical application for someone (in this case, me) and I enjoy using applications when the interface runs and looks pretty smoothly, so I focused on styling as well.
## The Process
Managing my time for this project was particularly hard, as I've been working 50-hour weeks in the last month for my full-time job. I know I had to plan my days well in advance and set specific goals for each day to keep myself organized and on-track. But as many of us now, plans are just plans.

There were times were I struggled completing certain functionalities (validation, alerts, etc.) and had to spend more time than I had planned debugging errors. Here is where the daily project 'office hours' with our cohort lead, Ally, were extremely valuable. She was able to guide me techincally and project-wise, and without her help I would've spent a lot more building the project. So S/O to @Ally!

## The Outcome
In my estimate, I think I spent between 45 and 50 hours building this project, in line with the 20-25 hour/week commitment for the part-time curriculum. I was able to leverage experience and code from the Fwitter lab that was due before this project began - I spent several hours frustated finishing that project but it was certainly worth it.

Now, if you'll excuse me, I need to get back to my other weekend plans:

```
get '/weekend_plans' do
   if sunday?
	    redirect '/watch_football'
	else
      redirect '/relax'
    end
end
```




