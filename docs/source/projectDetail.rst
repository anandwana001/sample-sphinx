.. _projectdetail:

Tech-stack
----------

This project use multiple libraries to bring easy way of implementation

* Dagger2 - Dependency Injection Framework
* Retrofit - Used for Networking
* Timber - Helps in logging
* Glide - use to load image
* RxJava - to perform asynchronous work
* GSON - use to serialize and deserialize Java objects to JSON
* Lifecycle - manage activity and fragment lifecycle
* LiveData - observable data holder
* AndroidX - android library for core functionalities
* ViewModel - manage data in lifecycle aware fashion
* Material Components for Android - Modular and customizable Material Design UI components for Android
* Data Binding - helps to bind UI with data source
* Palette API - dynamically change app color scheme


Development Setup
-----------------
This project uses the TMDb API to fetch movies data.
To begin with the setup, firstly you need to create an API key.

* Create an account at themoviedb.org
* Go to settings from the profile icon
* Click on API
* Click on create

.. admonition:: Important

   Insert at ~/.gradle/gradle.properties or catchflicks/gradle.properties
   API_KEY=<insert>


This project uses the Dagger2 for dependency Injection.
After opening this project in your Android Studio you might get some error which is due unavailability of few classes.
You need to make project or try to build the project, this will generate all the required classes for dagger.

.. figure:: /images/update_screenshot.jpg

   *Home Screen*
