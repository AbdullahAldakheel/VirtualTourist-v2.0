Virtual tourist v2 app

Virtual Tourist is an iOS app that allows users to visit virtual locations by adding pins to a MKMapView. When a user taps a pin the app fetches photos from Flickr for that location and then the user can add top and bottom captions and then share the updated photo.
Implementation
MapViewController.swift which manage the pins.
ShareImageViewController.swift which allows the users to add top and bottom captions and then share the updated photo
ImagesViewController.swift which manage the photos fetched by flicker and display them in collection view.
How I build my app

UI creation -> assign classes to each view controller -> create outlets and actions -> using any necessarily protocols or libraries.

Requirements
	•	Xcode 9.2
	•	Swift 4.0
	

![alt text](app.gif)
