Scheduled Server Events
=======================

The Top Speed SMP server will automatically run commands based on the following schedule:
  
- Every 15 minutes: lag removal command
  
- Every day: full server backup
  
- Every day at 3:20am Eastern: notification sent for server shutdown
  
- Every day at 3:25am Eastern: server safely shuts down
  
- Every day at 3:30am Eastern: Linux machine automatically resarts, server should resume activity in less than 5 minutes
