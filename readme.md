## Homework 4
### Violet Smith
### Feb 9 2022

1. a. MLFQ Scheduling 
  i. What are the turnaround and response times?

        Job  0: startTime   0 - response   0 - turnaround  84
        Job  1: startTime   0 - response   7 - turnaround 153
        Job  2: startTime   0 - response  15 - turnaround  81
        Job  3: startTime   0 - response  18 - turnaround  70
        Avg  3: startTime n/a - response 10.00 - turnaround 97.00

    ii. What happens to the turnaround and response times as you increase the boost time?
            When you change the priority boost it decreases the average response time and it decreases the average turnaround time.
    
b. Lottery Scheduling
   i. What  are the tuurnaround and response times? 
   Job 0: response 2,   turnaround 13
   Job 1: response 0, turnaround 23
   Job 2: response 1, turnaround 18
   Job 3: response 4, turnaround 27

ii. What happens to the tunaround and response times as you increase the boost time? 
    When you change the time slices, it will increase the response times and the turnaround times.
2. Freespace
   - Are in the attached photos

3. Segmentation
Segment register information:

    Segment 0 base  (grows positive) : 0x00003d40 (decimal 15680)
    Segment 0 limit                  : 422

    Segment 1 base  (grows negative) : 0x00000e44 (decimal 3652)
    Segment 1 limit                  : 435

    Virtual Address Trace
        VA  0: 0x00000042 (decimal:   66) --> VALID in SEG0: 0x00003d82 (decimal: 15746)

        VA  1: 0x0000034c (decimal:  844) --> VALID in SEG1: 0x00000d90 (decimal: 3472)

        VA  2: 0x00000155 (decimal:  341) --> VALID in SEG0: 0x00003e95 (decimal: 16021)

        VA  3: 0x0000017d (decimal:  381) --> VALID in SEG0: 0x00003ebd (decimal: 16061)

        VA  4: 0x00000342 (decimal:  834) --> VALID in SEG1: 0x00000d86 (decimal: 3462)

        VA  5: 0x000000bb (decimal:  187) --> VALID in SEG0: 0x00003dfb (decimal: 15867)

        VA  6: 0x000003a3 (decimal:  931) --> VALID in SEG1: 0x00000de7 (decimal: 3559)

        VA  7: 0x000001f6 (decimal:  502) --> SEGMENTATION VIOLATION (SEG0)

        VA  8: 0x00000049 (decimal:   73) --> VALID in SEG0: 0x00003d89 (decimal: 15753)

        VA  9: 0x000003ab (decimal:  939) --> VALID in SEG1: 0x00000def (decimal: 3567)

        VA 10: 0x0000024a (decimal:  586) --> SEGMENTATION VIOLATION (SEG1)

        VA 11: 0x00000050 (decimal:   80) --> VALID in SEG0: 0x00003d90 (decimal: 15760)

        VA 12: 0x0000035a (decimal:  858) --> VALID in SEG1: 0x00000d9e (decimal: 3486)

        VA 13: 0x00000319 (decimal:  793) --> VALID in SEG1: 0x00000d5d (decimal: 3421)

        VA 14: 0x000002f5 (decimal:  757) --> VALID in SEG1: 0x00000d39 (decimal: 3385)

        VA 15: 0x000002a1 (decimal:  673) --> VALID in SEG1: 0x00000ce5 (decimal: 3301)

        VA 16: 0x000003f8 (decimal: 1016) --> VALID in SEG1: 0x00000e3c (decimal: 3644)

        VA 17: 0x0000000c (decimal:   12) --> VALID in SEG0: 0x00003d4c (decimal: 15692)

        VA 18: 0x000003e5 (decimal:  997) --> VALID in SEG1: 0x00000e29 (decimal: 3625)

        VA 19: 0x00000292 (decimal:  658) --> VALID in SEG1: 0x00000cd6 (decimal: 3286)

    
