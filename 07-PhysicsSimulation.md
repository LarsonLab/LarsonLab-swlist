# Physics Simulation tools

## Berkeley Model and Algorithm Prototyping Platform (MATLAB)
+ Website and source: https://github.com/jaijeet/MAPP
+ Source (on network): /working/larson/apleynes/MAPP/MAPP-2017-02-15-release-936fe19c63bf22cd50399c5cba1de4f0c2a339fa
+ Spin isochromat implementations (on network): /working/larson/apleynes/MAPP/working_code
  - Basic pulse sequence function: /working/larson/apleynes/MAPP/working_code/pulseSequence.m
  - Basic isochomat differential-algebraic-equation (DAE) model: /working/larson/apleynes/MAPP/working_code/spin_rotating_frame_with_position_DAE.m
  - Complete simulation code (README files to run are inside):
    - Simulate multiple spins without gradients using parallel computation: /working/larson/apleynes/MAPP/working_code/simulate_multiple_spins_parallel
    - Simulate multiple spins with gradients using parallel computation: /working/larson/apleynes/MAPP/working_code/simulate_multiple_spins_parallel_Gx_Gy_Gz
    - Simulate precession with T1 and T2 relaxation: /working/larson/apleynes/MAPP/working_code/simulate_precession_T1_T2_relaxation
    - Simulate precession without T1 and T2 relaxation: /working/larson/apleynes/MAPP/working_code/simulate_precession_without_relaxation
    - Simulate RF excitation: /working/larson/apleynes/MAPP/working_code/simulate_RF_excitation
    - Simulate RF followed by gradient: /working/larson/apleynes/MAPP/working_code/simulate_RF_gradient_excitation

