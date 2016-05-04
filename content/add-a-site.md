+++
date = "2016-05-04T16:53:33+01:00"
title = "Add A Site"

+++

### Broken
* Back to top link doesn't work (missing anchor with id `#top`)
* Brand logo links to the login page, not back to the homepage. This is different from every other page on the site.
* Impossible to read placeholder instructions on a small screen
* If you cannot geocode your address, it will not allow you to enter it. However you can enter a latlng, it will always return a geocoded address (often not correct). This is particularly bad if someone only wants to enter aerial poi.
* It is impossible to search by what3words, but you can still edit the w3w address field.

### Usability
#### General
* Menu reads as `Add A Site` but the page is called `Add Pad`
* You can't just detect your current location

#### Form
* Several fields are missing placeholders.
* Public/private radio buttons are not grouped or aligned
* `Landing not possible` needs explanation. Linked with PPR.
* Geocoder *a.k.a. the address search* search button is entirely redundant.
* Both `Latitude` and `Longitude` say `Drag map or enter number`. Dragging the map doesn't encode a latlong. There is no example of what an acceptable decimal format is and no accomadation for someone that only has the latlong in degrees
* It is not immediately clear whether you're supposed to enter the site's contact details or your own until you reach `Submitter's Email`
* Website placeholder is weird. Is it possible to link to `yourhost.com/~yoursite` for example? Also not clear whether having `http://` would matter or not.
* Twitter handle does not specify whether it expects an `@`
* Tagging breaks out of the page layout and is particularly nasty to work with. Suggest implementing some sort of typeahead/fuzzy search? There is also no guidance on what is preferred or acceptable.
* Establishment only help is on another page. Also a lot of the labels say `see landing information` but the placeholder in `landing information` is empty.

### Style
* Styling on this page is inconsistent with the rest of the site
* Capitalisation is inconsistent across the different placeholders
* `Private Note` might be more appropriate than `Private Message`?
