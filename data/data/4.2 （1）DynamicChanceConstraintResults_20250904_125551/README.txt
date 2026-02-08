Dynamic Chance Constraint Validation Results
Generated on: 04-Sep-2025 12:56:07

Files:
1. experimental_data.csv - Raw experimental data (position error, match error, cycle time)
2. iteration_data.csv - Iteration history of Lagrangian multipliers and violation rates
3. joint_constraint_satisfaction.csv - Joint constraint satisfaction rate data
4. results_summary.txt - Summary of experimental results
5. constraint_space_distribution.png - Visualization of constraint space
6. lagrangian_multiplier_convergence.png - Convergence trajectory of multipliers
7. joint_constraint_satisfaction_surface.png - Joint constraint satisfaction surface
8. violation_rate_suppression.png - Violation rate suppression analysis

Column descriptions:
experimental_data.csv:
  PositionError_mm: Positioning error in millimeters
  MatchError: 1-IoU matching error
  CycleTime_s: Task cycle time in seconds

iteration_data.csv:
  Iteration: Iteration number
  Lambda1: Lagrangian multiplier for positioning constraint
  Lambda2: Lagrangian multiplier for matching constraint
  Lambda3: Lagrangian multiplier for cycle time constraint
  ViolationRate: Constraint violation rate percentage

joint_constraint_satisfaction.csv:
  PositionThreshold_mm: Positioning error threshold
  MatchThreshold: 1-IoU threshold
  SatisfactionRate: Joint constraint satisfaction rate percentage
