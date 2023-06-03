Data Extractor
This Python script is a simple, straightforward data extractor. It reads a JSON file and extracts specific data fields, then writes each field to a separate .txt file.

The currently supported data fields are:

'first_name'
'last_name'
'email'
'gender'
'ip_address'
These fields correspond to the values you'd expect them to hold. The 'first_name' and 'last_name' fields contain names, 'email' contains email addresses, 'gender' reveals gender identity, and 'ip_address' contains IP addresses.

How to Run the Script
Prerequisites
You need Python 3 installed on your computer. You can download it here.

Steps
Clone this repository to your local machine using https://github.com/YOUR-USERNAME/REPO-NAME.git.

Navigate to the cloned repository.

Put your JSON file into the root of the cloned directory. The JSON file should be named data.txt.

Open a terminal/command prompt.

Run the script using the following command: python script_name.py

Output
The script generates five .txt files in the same directory as your script. These files will contain the extracted data from the JSON file. The file names are as follows:

first_name.txt: Contains extracted 'first_name' data.
last_name.txt: Contains extracted 'last_name' data.
email.txt: Contains extracted 'email' data.
gender.txt: Contains extracted 'gender' data.
ip_address.txt: Contains extracted 'ip_address' data.