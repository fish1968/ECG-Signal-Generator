# ECG Signal Generation in Proteus

This repository contains code and instructions for generating an Electrocardiogram (ECG) signal using Proteus simulation software. The generation process involves importing ECG signal data into the Arduino IDE, programming an Arduino board to generate the ECG signal, and visualizing it using Proteus's virtual oscilloscope.

## Overview

The generation process consists of the following steps:

1. **Import ECG Signal Data**: The vector data of an ECG signal is imported into the Arduino IDE. This vector contains the necessary data points to generate an electrocardiographic signal.

2. **Arduino Programming**: Specific code is developed to program the Arduino board to generate the ECG signal based on the imported data. 

3. **Compilation and Export**: Once the code is written, it is compiled and exported as a .hex file, which is ready to be uploaded to the Arduino board within Proteus.

4. **Simulation Setup**: The Arduino board simulated in Proteus is connected to a digital-to-analog converter (DAC), which converts the digital signal into an analog one. The signal then passes through resistors to adjust its amplitude as needed for the simulation.

5. **Visualization**: The generated ECG signal can be visualized using an oscilloscope within Proteus, allowing for analysis of its characteristics and behavior.

## Repository Contents

- `ECG_Signal_Data`: Sample ECG signal data
- `Arduino_Code`: Arduino code and .hex file
- `Proteus_Simulation`: Proteus simulation file
- `README.md`: Overview and usage instructions


## Usage

1. Clone or download the repository.
2. Open the Proteus simulation file.
3. Upload the `.hex file` to the simulated Arduino board.
4. Run the simulation to visualize the ECG signal.

![image](https://github.com/Quarkify/ECG-Signal-Generator/assets/162180511/3f1e7abb-bf61-4a73-9dee-24a70b80ffa3)
![image](https://github.com/Quarkify/ECG-Signal-Generator/assets/162180511/ed3d4429-c205-41c0-87ef-db13e26bf652)

### Note

Adjust resistance values for fine-tuning signal amplitude. In this project, the resistance values have been configured to yield an amplitude of no more than 2mV, mirroring that of a real ECG signal.

## Contributing

Contributions to improve the generation process or add additional features are welcome. If you would like to contribute, please fork the repository, make your changes, and submit a pull request.

## Acknowledgments

This project was inspired by the work of [walidamriou](https://github.com/walidamriou).



## License

This project is licensed under the [MIT License](LICENSE), allowing for open use and modification.

---

By generating ECG signals in a virtual environment, this repository aims to facilitate the development and validation of electronic systems for the analysis and processing of biomedical signals. If you have any questions or suggestions, feel free to open an issue or reach out to the repository maintainers.
