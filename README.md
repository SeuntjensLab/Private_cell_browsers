# Private_cell_browsers

This repository was created to explain the **different necessary steps to use the UCSC private cell browsers**.

## Usage

- Use **Globus to download from ManGo** the folder of the Cell browser you want to use

The folders (zip files) can be found [here](https://mango.kuleuven.be/collection/browse/set/home/seuntjens/Seuntjens%20Lab/Octoteam/Omics%20datasets/Cell%20browsers)

- Put the zip file in a convenient location on your computer

> [!WARNING]
> **Make sure the preceding folders where the zip file is situated don't contain spaces in their names.**
> **If it's the case, rename your folders and replace the spaces with underscores.**

- Unzip the zip file

- Open Anaconda Prompt (like for Easy_HCR use)

- Move into the folder you just unzipped with the command: `cd C:\Users\path\to\the\correct\location`

- Run the following command: `python -m http.server 8000`

- Go to your favorite web browser and paste the following URL address: `http://localhost:8000/`

This should open the UCSC cell browser in your web browser
