# MultiThreadingPython

## Lock Objects, Semaphores, Condition Variables

#### Imagine a public restroom with a single lock on the door (lock object). Only one person can enter at a time, ensuring privacy.
#### Now, consider a locker room with 10 lockers (semaphore). Multiple people can access lockers concurrently as long as there are lockers available (counter > 0).
#### Finally, think of a waiting area with chairs and a call button (condition variable). People waiting for a locker can sit and wait (holding a lock on the waiting area). When a locker becomes available, someone can press the call button (notify) to signal a waiting person (who can then acquire the locker).
