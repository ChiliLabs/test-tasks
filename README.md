# iOS

### The assignment:

Main Objective: 
  - Create a gif search application using Giphy service;

Requirements:
  - Swift 5;
  - RxSwift
  - Auto search - search requests performed after a 0.5 second delay after text input has stoped;
  - Results displayed in a UICollectionView;
  - Loading more results when scrolling;
  - Comments on code that you feel require additional explanation;
  - 
Notes:
  - Any and all 3rd party frameworks are allowed;
  - No time limit - quality > speed;
  - Documentation - https://github.com/Giphy/GiphyAPI#search-endpoint
  - Visual representation is up to interpretation (Except the UICollectionView);
  
# Android

### The assignment:

Main Objective: 
  - Create an application from a scratch with possibility to search GIFs through giphy service;

Requirements:
  - Implement “live search” - i.e. request is sent in N milliseconds (for example 200) after the user has entered some input;
  - Results are displayed in RecyclerView;
  - Request pagination - load enough items to populate the RecyclerView and load more items every time user scrolls to the end of the list (limit / offset);
 
Notes:
  - UI can be very simplistic, but should be responsive and precise, accurate and done according to guidelines;
  - Usage of kotlin, rxjava, android databinding library, dagger, mvvm (android architecture components) will be considered as an advantage but is not necessary;
  - No time limit - quality > speed;
  - Giphy documentation - https://github.com/Giphy/GiphyAPI#search-endpoint
