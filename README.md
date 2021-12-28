# TodoList_App
#THINGS COVERED IN THE PROJECT
SINGLE PAGE APPLICATION, MENUS, IMPLICT INTENT, FRAGMENTS, ROOM DATABASE(SQLITE), LIFECYCLE AND STATE MANAGED, CRUD OPERATION, RECYLCERVIEW, MVVM ARCHITECTURE, OBSERVE PATTERN ETC
INTRODUCTION
This is a Single Page Application. There is only one mainActivity and two fragment i.e. TODOLIST fragment and TODOADD fragment. Fragment is attached in center of the screen using Frame layout and it is replaced by the Fragment manager and only center of the screen changes.
At First, TODOLIST fragment is added in the middle by Fragmentmanager and then after clicking on the add button below it is replaced.

There is no task at first and only picture is displaying as showing in the below images:
![267808292_896979824184060_7171783233667757187_n](https://user-images.githubusercontent.com/81868097/147594322-57d4de12-3b25-472e-a790-610d4885eced.jpg)



After clicking in the plus button, Frame layout is replaced using Fragment manager and we can see the only center view is changed and we are in the TODOADD fragment.

Task can be added in the following ways as shown in image below:

ADD TASK IMAGE ADD TASK gif
![video-1640714289](https://user-images.githubusercontent.com/81868097/147594413-beea25bd-5570-4f1d-8718-0bfd0ec8f49b.gif)


After added the task, Frame layout back stack from the and center view is replace and we are in the main TODOLIST fragment and gif image is removed.

Here is crud operation is applied as shown in below gif
![video-1640714236](https://user-images.githubusercontent.com/81868097/147594488-5dae0d13-6cbb-4681-953f-4dbce18398ef.gif)
