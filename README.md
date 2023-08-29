



Hello Jeffrey 


# About InDesign

You mentionned InDesign which is in my opinion great for building websites mockups, but I find it terrible for generating websites.

Similar "no-code" tools like Wix, SquareSpace, Webflow, are good tools for building websites, but have some flaws

- Usually requires an overpriced monthly subscription
- Works best with premade templates
- Are quite limited if you don't follow their own design principles; in other words the design has to be adapted to to the tool and not the other way around.
- Are not exportable, e.g. you are locked in once you start using it
- Are quite bloated and slow

On the other hand, one advantage of these tools is that you can edit the layout of the website directly from within the back-office.
But this advantage is mostly due to the fact that everything is pretty much a template, or blocks of templates.


# "Headless" Back office (CMS)

I started with Wix but it was so infuriating and limiting to work with it that I to learned React (Javascript) instead, which allows me much more flexibility.

Since I build websites with code from scratch, this kind of feature is quite complex to implement, and overkill in my opinion for a portfolio.

So the alternative that I use is a "headless CMS (content management system)", a back office which only serves as a structured database for the content, which in essence works similary to Google Drive.
The front end of the website then automatically fetches the data from the back office to display it.
So all the pages from the front end are generated dynamically from the data in the back office.

## Payload CMS

Here is how it works; there are 2 main sections :
![image](./one.png)

### The data pool (RED)
From which you can access all medias (images, pictures) and all projects
<video width="320" height="240" controls>
  <source src="./pool.mkv" type="video/mp4">
</video>


### Pages content (BLUE)
Where you define the content of the page, by using content from the data pool,
or adding the content directly if they aren't already stored in the pool

<video width="320" height="240" controls>
  <source src="./projects.mp4" type="video/mp4">
</video>


---

Here are some other screenshot that may help you understand what's going on
![projects](./two.png)
![projects](./three.png)
![projects](./four.png)
![projects](./five.png)

You can visit the back office shown above via
https://cms.studiosamuel.fr

I'll send you the guest login and password via e-mail

## Contentful CMS

Basically the same thing but much less flexible
![projects](./contentful.mp4)


