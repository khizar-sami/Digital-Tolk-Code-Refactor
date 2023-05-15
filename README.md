# Digi-tolk-code-refactor

Based on my understanding and adherence to coding practices, I have made the following observations:

The code over all is average, There were a lot of if conditions present in the code which makes the code
a bit messy and hard to read, There were no comments in the code. 

Assignments of variables are used unnecessarily which takes memory, and if the request is return large data, assignments of variables effect on response time.

There is a lot of Code Redundancy which makes the code look ugly and hard to understand. 

The response codes should be managed by the HTTP response codes.


The good thing about the code is using the Repository Pattern which makes the code structured. All the
data manipulation is done on the relevant repository and all the models has their respective repositories.  


// Refactored Code
* BookingController@index
* BookingController@show
* BookingController@store
* BookingRepository@getAll
* BookingRepository@getUsersJobs
* BookingRepository@store
* BookingRepository@updateJob
* Booking Repository@changeTranslator
