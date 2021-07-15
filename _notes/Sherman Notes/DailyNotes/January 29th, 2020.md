---
---

- [[Code]][[Repos]] https://github.com/Siderite/LInQer 
    - LINQ implementation in [[JS]]
- [[Code]][[Repos]] Bug in AWS [[Java]] SDK
    - Bug in our code where requests would timeout. Seems that threads where hanging / locking in the pool that we didn't have access to. after a log of head scratching, it was suggested to check if it really is a bug in their code. Out but seemed similar to this one which was fixed. https://github.com/aws/aws-sdk-java/issues/2089
    - The take home point is:
        -  [[TIL]] "The time taken to bump a version vs trying to find a problem in our code"
        - Even if it wasn't the *fix* (Though there is a high chance it is) I would have spent a lot longer not getting any further in finding out why than to bump and see what happens next.
