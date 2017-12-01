A project to create an asynchronous search using Javascript and the Flickr API.

This project asks users to accept a query and use that query to
search Flickr in order to show a grid of images that were returned. The page also utilizes jQuery and Bootstrap.

Utilizing principles of progressive enhancement, this site activates the form so
you may capture the input from the user and send it along to Flickr by making
a call to the Flickr API. After a successful response from the Flickr API, the returned items will
then display a grid of the images that have been found. Users are also able to view larger
versions of the images.

* Created an event handler that will accept user input through the provided form and turn that input into a request to the [Flickr API](https://www.flickr.com/services/api/).
* Displayed images returned from the Flickr API as a grid on the page.
* Displays offer the following info around the images the script finds:
    * title
    * date_taken
    * description
    * author
    * link back to the Flickr page for this image
* When users re-do the search, the previous images is removed, and the new images will fill the same space.

