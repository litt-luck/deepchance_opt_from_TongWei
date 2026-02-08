Multimodal Uncertainty 3D Visualization Dataset
Generated on: 04-Sep-2025 12:39:08

Files:
1. static_scenario_data.csv - Static scenario metrics
2. dynamic_propagation_data.csv - Time-varying propagation weights
3. distribution_validation_data.csv - Distribution validation results
4. validation_results.txt - Statistical validation results
5. simulation_metadata.csv - Simulation parameters
6. static_analysis_3d.png - Static analysis visualization
7. dynamic_propagation_3d.png - Dynamic propagation visualization
8. distribution_validation_3d.png - Distribution validation visualization

Column descriptions:
static_scenario_data.csv:
  Modality: Uncertainty type (Random, Fuzzy, Epistemic, Delay)
  MainEffect: Sobol main effect index
  TotalEffect: Sobol total effect index
  CriticalPathWeight: Key propagation path weight

dynamic_propagation_data.csv:
  Time_s: Simulation time in seconds
  Random, Fuzzy, Epistemic, Delay: Dynamic weights for each modality

distribution_validation_data.csv:
  ErrorBin: Error range bin
  TheoreticalPDF: Theoretical probability density
  ExperimentalFrequency: Experimental frequency
  RelativeErrorPercent: Relative error percentage
