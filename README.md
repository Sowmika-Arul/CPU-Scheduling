# CPU Scheduling

 CPU Scheduling is a process that allows one process to use the CPU while another process is delayed (in standby) due to unavailability of any resources such as I / O etc, thus making full use of the CPU. The purpose of CPU Scheduling is to make the system more efficient, faster, and fairer.

## Objectives of Process Scheduling Algorithm

- Throughput should be Maximum. i.e. Number of processes that complete their execution per time unit should be maximized.

- Minimum turnaround time, i.e. time taken by a process to finish execution should be the least.

- There should be a minimum waiting time and the process should not starve in the ready queue.

- Minimum response time. It means that the time when a process produces the first response should be as less as possible.

## Terminologies Used in CPU Scheduling

- **Arrival Time**: Time at which the process arrives in the ready queue.

- **Completion Time**: Time at which process completes its execution.

- **Burst Time**: Time required by a process for CPU execution.

- **Turn Around Time**: Time Difference between completion time and arrival time.

                        Turn Around Time = Completion Time  –  Arrival Time

- **Waiting Time(W.T)**: Time Difference between turn around time and burst time.

                         Waiting Time = Turn Around Time  –  Burst Time

## Things to Take Care While Designing a CPU Scheduling Algorithm

Different CPU Scheduling algorithms have different structures and the choice of a particular algorithm depends on a variety of factors. Many conditions have been raised to compare CPU scheduling algorithms.

The criteria include the following: 

- **CPU Utilization:** The main purpose of any CPU algorithm is to keep the CPU as busy as possible. 
                       Theoretically, CPU usage can range from 0 to 100 but in a real-time system, it varies from 40 to 90 percent depending on the system load.

- **Throughput:** The average CPU performance is the number of processes performed and completed during each unit. 
                  The output may vary depending on the length or duration of the processes.

- **Turn Round Time:** For a particular process, the important conditions are how long it takes to perform that process.
                       The time elapsed from the time of process delivery to the time of completion is known as the conversion time. 
                       Conversion time is the amount of time spent waiting for memory access, waiting in line, using CPU, and waiting for I / O.

- **Waiting Time:** The Scheduling algorithm does not affect the time required to complete the process once it has started performing. 
                    It only affects the waiting time of the process i.e. the time spent in the waiting process in the ready queue.

- **Response Time:** In a collaborative system, turn around time is not the best option. 
                     The process may produce something early and continue to computing the new results while the previous results are released to the user.