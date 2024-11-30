Your code should have at least **2 classes**:
1. For the `Assignment`
2. For the `Heap`

For both, define whatever is required and mentioned in the question inside the _scheduler.cpp_ file.

Assignment initialisation in the _main.cpp_ follows the structure:

```c
{"id": "Assignment1", "weightage": 5, "deadline": 10, "execution time": 3}
```

Your code should also have an overall `AssignmentScheduler` class which will have the outputs stored for you in the required format.

Output format for `scheduler.printResults()`:

**Executed Tasks:**
```c
["Assignment2", "Assignment4", "Assignment1"]
```

**Discarded Tasks:** 
```c
[{"id": "Assignment3", "reason": "Deadline passed"}]
```

The scheduler should first prioritise by weight and then by deadline as mentioned in the question.