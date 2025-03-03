# Philosophers 42 Project - 15-Day Roadmap

## Goal
Implement the dining philosophers problem in C using threads and mutexes to manage concurrent execution without deadlock.

---

## Day 1-2: Research & Planning

### Understand the Problem:
- Read about the Dining Philosophers Problem.
- Understand race conditions, deadlocks, starvation, and solutions like mutexes and semaphores.

### Review Project Requirements:
- Check 42 School’s specific rules (e.g., allowed functions, error handling).

### Plan Implementation:
- Decide on data structures and thread management approach.
- Create a flowchart or pseudocode for execution.

---

## Day 3-4: Setup & Basic Threading

### Initialize the Project:
- Create the repository and basic file structure.
- Set up Makefile.

### Implement Basic Threading:
- Initialize philosophers as threads.
- Implement basic loop for philosopher actions.

---

## Day 5-6: Mutexes for Forks

### Implement Forks with Mutexes:
- Create an array of mutexes for forks.
- Implement fork pickup and release logic.

### Test Basic Synchronization:
- Ensure philosophers don’t take the same fork at the same time.

---

## Day 7-8: Handling Deadlocks & Starvation

### Prevent Deadlocks:
- Use an order-based fork pickup strategy (e.g., even philosophers take left fork first, odd take right first).

### Prevent Starvation:
- Implement a check to ensure all philosophers get a chance to eat.

---

## Day 9-10: Implementing Timers & Death Detection

### Track Time Since Last Meal:
- Implement a timestamp for each philosopher’s last meal.

### Implement Death Detection:
- End the simulation when a philosopher has not eaten for too long.

---

## Day 11-12: Optimization & Edge Cases

### Improve Performance:
- Optimize thread handling and reduce unnecessary locking.

### Test Edge Cases:
- Check behavior with 1 philosopher.
- Test with a high number of philosophers.
- Simulate various delays.

---

## Day 13: Code Cleanup & Documentation

### Refactor Code:
- Clean up functions, remove redundant code.

### Write Documentation:
- Explain each function and its purpose.

---

## Day 14: Final Testing & Debugging

### Run Extensive Tests:
- Check for memory leaks (use `valgrind`).
- Test different philosopher/fork numbers.

### Fix Any Remaining Issues

---

## Day 15: Submission & Review

- Final Run and Checks
- Submit the Project
- Review Feedback and Improve if Needed

