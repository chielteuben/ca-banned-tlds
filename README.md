# Certificate Authority Banned TLDs

## Overview

This repository contains lists of Top-Level Domains (TLDs) that are banned by various Certificate Authorities (CAs). The purpose is to assist users in identifying and preventing issuance attempts of certificates on these prohibited TLDs.

## How to Use

Each CA has its own file containing a list of banned TLDs, along with a version number and the last modified timestamp. Users can reference these files to identify banned TLDs when processing certificate requests.

### File Structure

`ca_name.txt`: List of banned TLDs for a specific Certificate Authority.
- Last Modified: ISO 8601 date-time string
- Version: YYYYMMDDHHMMSS string matching Last Modified
- tld1
- tld2
- tld3


## Contributing

Contributions to this repository are welcome. If you have additional information or updates regarding banned TLDs for specific CAs, feel free to open an issue or submit a pull request.

## Disclaimer

This information is provided as-is and should be used responsibly. The repository owner and contributors are not responsible for any misuse or misinterpretation of the data.
