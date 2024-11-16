# Network Scanner

A Python script for scanning local networks to discover active devices and their hostnames.

## Versions

**Current version**: 1.0.0

## Table of Contents

- [Versions](#versions)
- [Badges](#badges)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Badges

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Installation

1. Clone the repository or download the script
2. Install optional dependencies for enhanced hostname resolution:

    ```bash
    pip3 install pynetbios zeroconf
    ```

3. For additional hostname resolution methods, install nmap:
   - macOS: `brew install nmap`
   - Linux (Debian/Ubuntu): `sudo apt-get install nmap`
   - Linux (CentOS/RHEL): `sudo yum install nmap`

## Usage

1. Make the script executable:

    ```bash
    chmod +x scan-local-network.py
    ```

2. Run the script:

    ```bash
    ./scan-local-network.py
    ```

The script will scan your local network and display discovered devices with their IP addresses and hostnames (when available).

## License

This project is licensed under the MIT license. See [LICENSE](LICENSE) for more information.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
