<!-- 
### Right Now: What Can Be Done Right Now? 

1. Specify the s/w requirements
2. Build a demo UI design
3. Try building a working UI using FX / something like that 
-->


<!-- Answering My Own Questions: -->
# Specifying The requirements: 

## To Summerize The App Would Contain:
```
1. Daily (routine) Tasks
2. Weekly (routine) Tasks
3. Todo List (Random Everyday Works)
4. Project or Goal (Task for a certain time range)
```

### Description of Specifications: 
* User can input `daily tasks` (Which will have no expiration time. i.e: it will be logged and continue forever)  
  It will have a fixed time frame Everyday.

  * Examples: 
    1. Namaz Timer.
    1. Food Intake Timer(Breakfast, Lunch, Dinner).
    1. Medicine Intake Timer(can Be associated with FoodIntake).
    1. Sleep & WakeUp Timer etc.

* User can input `weekly routine` (which will have a week-day(s) association) {It may/may-not have an expire time}
  It will have a fixed time frame on Given Day.

  * Examples: 
    1. Class Schedule(student,teacher)
    1. Picking up kids from school.

* User can input random `Todo Tasks`(which are random tasks that users need to do) { It might contain a priority-scheme}
  * It will have a date(today or in future) and time and this **can override the daily and weekly tasks.**
  * It will be destroyed after completion.

  * Examples: 
    1. Attending a seminar
    1. Fixing A Bug
    1. Meeting Someone
    1. Going to movies

* User can input `Projects/Target/Goal` which will be tracked (in terms of goal and completion)
  * It can have an overlapping area with daily and weekly tasks //  **can override the daily and weekly tasks**
  * Examples: 
    1. Learning A Language like: Spanish, French, English, Java, Kotlin, Swift etc.
    1. Creating A Side-Project(within next month?)
    1. Building a Garden & Maintaining it.
    1. Cherishing a Hobby (in the vacation?).
    1. Working on Fitness for 3 months.



### Limitations of the proposed systems: 

* We decided not to include a task end time 
  each timer in the above proposed catagory will contain just a task start timer.
  (Rationale: easy for user to just input one thing{especilly considering mobile data inputting bottleneck} )
* Tracking Goals has an overlapping area with the weekly task or daily tasks.
* Needs access to the Android-Devices.

### Limitations of conventional methods: 

* Needs a pen and paper // access to physical elements needed to plan.
* Create decision hapazards in catagorizing works.
* Takes more time to separate the regualr tasks and the important tasks for today.
* Not easy to overview and reflect at a later time.

### Advantages of the proposed system:

* Flexible and Adaptive to the situation of modern world.
* Amount of time spent on activities can be easily tracked and overviewed.
* 

#### Future Work Plan: 

* We Plan to include a lock screen timer which will be display the due tasks of today.
* We plan to include a more efficient priority based scheduling system
* We plan on inlcuding a lock-screen clock similar to the traditional analog clock which will show the time in a regular analog format.
* ??? Including Support For Cloud Based Data Storage for Backup ???


#### System Requirements:
<!-- What the * am I doing right in this part !!  -->
1. Android Studio IDE
1. Android SDK(Software Development Kit)
1. JRE8 or higher(JRE: Java Runtime Environment)
1. Android SmartPhone(Android KitKat 4.4.2 or Higher)
<!-- 1. Android API (level-25 or higher) -->


