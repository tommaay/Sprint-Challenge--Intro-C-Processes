**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**

-   Created: When a process is first created, it occupies the "created" or "new" state.

-   Ready: A "ready" or "waiting" process has been loaded into main memory and is awaiting execution on a CPU (to be context switched onto the CPU by the dispatcher, or short-term scheduler).

-   Running: A process moves into the running state when it is chosen for execution.

-   Blocked: A process transitions to a blocked state when it cannot carry on without an external change in state or event occurring.

-   Terminated: A process may be terminated, either from the "running" state by completing its execution or by explicitly being killed.

**2. What is a zombie process?**

-   A process that has completed execution but still has an entry in the process table: it is a process in the "Terminated state".

**3. How does a zombie process get created? How does one get destroyed?**

-   A zombie process is created in the terminated state once a process has finished executing. Zombie processes can be destroyed with the kill command or upon reboot.

**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**

-   Benefit of using compiled language is that it has faster performance.

-   Benefit of using non-compiled language is that is it eaiser to implement and can be convenient for dynamic languages.
