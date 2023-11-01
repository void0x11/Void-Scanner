# Void Scanner - Comprehensive Network Scanning Tool

The Void Scanner is a sophisticated network scanning tool that offers a comprehensive suite of functionalities for network analysis. From performing basic ping scans to conducting thorough TCP port scans, this tool provides insightful results that can be stored and analyzed in a structured JSON format. Void Scanner is designed to function seamlessly across various operating systems, adapting its features to ensure optimal performance.

## Features
1. **Target Definition:** Define specific IP targets or ranges for scanning purposes.
2. **Ping Scan:** Check the activity status of designated targets.
3. **TCP Port Scan:** Conduct in-depth scans of TCP ports to identify open, closed, or filtered ports.
4. **Results Storage:** Save scan results in a JSON format for convenient access and analysis.
5. **Results Retrieval:** Access previously saved scan results using the relevant IP addresses.

## Design Principles
1. **Modularity:** Functions are logically organized for improved readability and reusability.
2. **Global Variables:** Efficient use of global variables for shared data, enhancing the tool's simplicity and coherence.
3. **Error Handling:** Implementation of robust error handling and input validation mechanisms to ensure stable operation.
4. **User Feedback:** Clear and color-coded feedback for a more intuitive and user-friendly experience.
5. **File Management:** Robust file management procedures ensure accurate saving and retrieval of scan results.
6. **Cross-Platform Compatibility:** Seamless functionality across diverse operating systems, with adaptable methods and commands.

## Future Enhancements
1. **Enhanced Error Handling:** Detailed error messages and handling of edge cases to fortify the tool's robustness.
2. **Extended Scanning Capabilities:** Integration of additional scanning methods such as UDP scanning, OS fingerprinting, and banner grabbing for increased versatility.
3. **Logging System:** Implementation of a comprehensive logging system for activity tracking and effective debugging.
4. **Configuration File:** Introduction of a configuration file to enable customized settings for default behaviors, result storage locations, and other user preferences.

## Dependencies
- colorama: Used for color-coded terminal text.

## Usage
To run the Void Scanner tool, follow these steps:

1. Ensure that Python 3.x is installed on your system.
2. Install the necessary dependency using the following command:
