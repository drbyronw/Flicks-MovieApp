# Flicks Movie App

Flicks is a movies app using the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## User Stories

The following **required** functionality is completed:

- [x] User can view a list of movies currently playing in theaters. Poster images load asynchronously.
- [x] User can view movie details by tapping on a cell.
- [x] User sees loading state while waiting for the API.
- [x] User sees an error message when there is a network error.
- [x] User can pull to refresh the movie list.

The following **optional** features are implemented:

- [x] Add a tab bar for **Now Playing** and **Top Rated** movies.
- [ ] Implement segmented control to switch between list view and grid view.
- [x] Add a search bar.
- [x] All images fade in.
- [ ] For the large poster, load the low-res image first, switch to high-res when complete.
- [x] Customize the highlight and selection effect of the cell.
- [x] Customize the navigation bar.

The following **additional** features are implemented:

- [x] Changed the request timeout to 10 seconds instead of the default - 60 

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://raw.githubusercontent.com/drbyronw/CodePath-Week1-Flicks/master/flicks-demo1.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
<br><br><br>
<img src='https://raw.githubusercontent.com/drbyronw/CodePath-Week1-Flicks/master/flicks-demo2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

/# of hours spent = 12

Describe any challenges encountered while building the app.
* issue with how long it takes for network datatask request to timeout - wait for error message 30+ seconds 

## License

Copyright 2016 Byron J. Williams

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
