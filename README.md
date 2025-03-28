# mtdi
# Phasor Analysis and Visualization Tool  

This application provides an interface for analyzing and visualizing phasors in power systems. The tool supports both recursive and non-recursive phasor calculation methods and offers real-time signal processing and display capabilities.  

## Features  

- **Recursive and Non-recursive Phasor Calculation**: Implements and compares both calculation methods  
- **Real-time Signal Processing**: Continuous data analysis based on sliding window technique  
- **Visualization Components**:  
  - Polar plots for phasor representation  
  - Time domain signal chart  
  - FFT spectrum analysis  
  - Phasor magnitude and phase tracking  
- **Three-point Averaging**: Optional signal smoothing algorithm to improve measurement stability  
- **Responsive Interface**: Automatically adapts to window size changes  

## Technical Details  

### Phasor Calculation Methods  

1. **Recursive Phasor Calculation**:  
   - Updates incrementally based on previous window calculations  
   - Improves computational efficiency for real-time applications  
   - Uses theoretical phase increments for phase accumulation  

2. **Non-recursive Phasor Calculation**:  
   - Complete recalculation based on sliding window  
   - Serves as a reference benchmark to verify the recursive algorithm  

### Signal Processing Features  

- **Sliding Window Technique**: Supports continuous data stream processing  
- **Dynamic Data Generation**: Automatically extends dataset as needed  
- **Three-point Averaging Algorithm**: Enhances phasor stability through averaging at specific phase points  