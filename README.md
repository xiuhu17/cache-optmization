# cache-optmization

Stage1: 
  - L1-DataCache: multibanck & lockup-free & victim page & array replication dual port
  - L1-InstrCache: multibank & fetch-directed instr prefetching
  - L2-cache: shared l2 cache
  
Stage2:
  - Redesigned Out-of-Order Cpu (combination of No_Pre-Reqs cpu and Out-Of-Office cpu)
  - Goal is achieve avg IPC >= 1.0 with minimum power
  - features: 
      - superscaclar 
      - bp & ras 
      - early branch recovery (if performance really improves) 
      - speculative memory operation (if performance really improves) 
      - fire & forget lsq
      
Stage3: 
  - potential multicore or SMT
