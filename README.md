# HomeW**************  Homework Week 1 Day 3  *************************
Answer the following questions:
1.  What are the major components in android?

The major android components are activities, services, content providers, and broadcast receivers.

2.  What are all the activity lifecycles and explain what each details?

they are six callback methods that are called at different stages of an activities life cycle.
they are onCreate() (initializes the activity basic application startup logic ), 
onStart() (makes the activity visible to the user ),
onResume()(this is the state where the app interacts with the user),
onPause() (when an interruptive event occurs the activity enter the paused state), 
onStop() (wen the activity is no longer visable to to the user), 
and onDestroy() (is called before the activity is destroyed)

3.  Explain each step of the sprint in agile.

Everyday there is a standup to assign stories (tasks) to each person, and the task to be completed.
at the end of the week there is a grooming meeting to figure out the progress of the feature.
Then on the second week there are pull request from scrum manager. At the end of the sprint all
pull request are finalized andnext sprint is planned out.

4.  What is dalvik and ART?

ART uses AOT compilation while dalvik uses Jit. they are different runtime enviroments.
Art installs native byte code translation on installation  while dalvik uses a just in time
compiler

5.  How is the android platform architecture designed?

Androi has a linux kernel followed by a HAL layer for its I/O components, next it has and
the android run time environment with native c/c++ libraries, then it has the Java API framework
Lastly it has the System Apps layer.
