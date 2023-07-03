# Timer

Uses the useState Hook in React and also utilizes Asynchronous JavaScript in setInterval() function.
It gets dynamically updated each second due to this Asynchronous nature.

JavaScript is a single-threaded language and it cannot delegate tasks, it can only do one specific task at a single time. No matter the number of cores, it can only run a single core. Code does not run parallelly. All tasks are done sequentially. 

The setInterval() function is a way to get around this single threaded nature and updates the time every second even while other tasks are running.
