
# ATM-RT: Advanced Task Model Dataset for Real-Time Scheduling

This dataset provides a benchmark collection of 12,600 real-time tasks based on the Advanced Task Model (ATM) for real-time multiprocessing systems. It is designed to support research in dynamic scheduling, thermal-aware assignment, reinforcement learning-based scheduling, and embedded systems optimization.

## Dataset Contents

- `etmrm_12600_tasks.csv`: Full dataset of 12,600 tasks with attributes.
- `etmrm_12600_dag.json`: DAG structure defining inter-task dependencies.
- `README.md`: This description file.
- `LICENSE`: Creative Commons Attribution 4.0 License (CC BY 4.0).

## Task Attributes

- PID: Task identifier (T1…T12600).
- Benchmark: Source suite (PapaBench, MiBench, TACLeBench, Malardalen, EEMBC).
- WCET: Worst-case execution time (ms).
- Period: Activation period (ms).
- **Deadline**: Relative deadline (ms).
- Criticality: High or Low.
- TempSens: Thermal sensitivity index (ΔT per ms).
- LoadSens: Load sensitivity index.
- Energy: Energy consumption per activation (mJ).
- Predecessors: Single predecessor PID for DAG.

## Citation

Please cite this dataset as:

> Goran HamaAli,Diary R. Sulaiman "ATM-RT: Advanced Task Model Dataset for Real-Time Scheduling and Assignment," 2025.

## License

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
