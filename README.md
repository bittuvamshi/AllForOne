# AllForOne - Nuclei Template Collector 👤

Welcome to the "AllForOne" repository! :rocket: This repository contains a Python script that allows bug bounty hunters and security researchers to collect all Nuclei YAML templates from various public repositories, helping to streamline the process of downloading multiple templates using just a single repository.

## How it Works :gear:

The script leverages the GitHub repositories which containing Nuclei Templates. It will clones them to your local machine, and extracts the templates, organizing them for easy access.

## Getting Started :rocket:

To get started, follow these steps:

1.  Clone the repository:
```git clone https://github.com/AggressiveUser/AllForOne.git```  :computer:

2.  Install the required dependencies:
```pip install -r requirements.txt```  :key:

3.  Run the script:
```python AllForOne.py```  :snake:

4.  Sit back and relax! The script will start collecting the Nuclei templates from public repositories.
 <img src="https://i.ibb.co/0BMmgXJ/image.png" width=500/>

## Result :file_folder:

Once the script completes, you'll find a folder named `Template` in the repository's root directory. Inside this folder, you'll find subfolders for each cloned repository, containing the Nuclei tool YAML templates. Each template is stored as a separate file, enabling easy access and utilization for your bug bounty or security testing activities.

## Disclaimer :exclamation:

Please ensure that you comply with all relevant laws, terms of service, and guidelines when using this tool. The Nuclei tool and the collected templates should be used responsibly and ethically. The creators of this script are not responsible for any misuse or illegal activities performed using the gathered templates.

## Contributions :raising_hand:

Contributions to this project are welcome! If you have any updated and new github repo for nuclei templates, feel free to submit a pull request for `PleaseUpdateMe.txt`

## License :page_facing_up:

This project is licensed under the [MIT License](https://github.com/AggressiveUser/AllForOne/blob/main/LICENSE).