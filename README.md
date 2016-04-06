FlickrDecisionMaker
===================
![IMG_29572.jpg]({{site.baseurl}}/IMG_29572.jpg)

**FlickrDecisionMaker** is a test to see if mobile devices have a suitable interface to quickly make decision about a photo on Flickr. For example if a photo is public or not, or if a photo belongs to a set or not.

The main idea is to have a stack of photos in the center of the screen. 
You have two areas that can contain thumbnails of the photo. 
One on the left and one on the right (more complex variations are possible I think but it's too early).
Swiping left or right decide if the photo belongs to the left or the right group. The photo gets removed from the stack and put in one of the areas.
This action trigger the change of one property of the photo (being it public or not, belonging to a chosen set).

The idea come from my ugly experience with the Flickr organizer.

At this time I have only some ideas that I've put in a ugly prototype not shown here.

I'll try to use [PhpFlickr](http://code.google.com/p/phpflickr/) library to interact with the Flickr API.



####
