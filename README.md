# space-manipulator-simulation
# Space Manipulator Ground Simulation

Ground simulation and verification platform for space robotic arms, based on MATLAB/Simulink and ADAMS. This project demonstrates methodologies for microgravity simulation and moment of inertia compensation, derived from my M.Sc. research at Shenyang Institute of Automation, CAS (China Space Station Transfer Manipulator project).

## 🎯 Research Background

Space robotic arms require extensive ground verification before on-orbit deployment. This project provides:
- Multi-body dynamics modeling of 7-DOF space manipulators
- Microgravity simulation using moment of inertia compensation
- Hardware-in-the-loop (HIL) testing framework
- Contact/impact dynamics for capture operations

## 🔧 Methodology

### 1. Microgravity Simulation
- **Principle**: Compensate gravitational effects through active force control
- **Implementation**: Simulink model with real-time force feedback
- **Validation**: Comparison with parabolic flight experimental data

### 2. Moment of Inertia Compensation
- **Challenge**: Space manipulators have super-large moment of inertia
- **Solution**: Ground-based inertia simulation device (see Patent ZL202020963210.1)
- **Model**: ADAMS multi-body dynamics with experimental validation

### 3. HIL Simulation Framework
- **Architecture**: Real-time controller + virtual plant
- **Interface**: MATLAB xPC Target / Simulink Real-Time
- **Application**: Pre-flight verification of capture and transfer operations

## 📁 Repository Structure
