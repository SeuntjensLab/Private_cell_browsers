# Private_cell_browsers

This repository was created to explain the **different necessary steps to use the UCSC private cell browsers**.

## Usage

1. Use **Globus to download from ManGo** the folder of the Cell browser you want to use

> [!NOTE]
> **The folders (zip files) can be found [here](https://mango.kuleuven.be/collection/browse/set/home/seuntjens/Seuntjens%20Lab/Octoteam/Omics%20datasets/Cell%20browsers)**

2. Put the zip file in a convenient location on your computer

> [!WARNING]
> **Make sure the preceding folders where the zip file is situated don't contain spaces in their names.**
> **If it's the case, rename your folders and replace the spaces with underscores.**

3. **Unzip** the zip file

4. Open **Anaconda Prompt** (like for Easy_HCR use)

5. **Move** into the **folder you just unzipped** with the command: `cd C:\Users\path\to\the\correct\location`

6. **Run** the following command: `python -m http.server 8000`

7. Go to your favorite **web browser** and **paste the following URL** address: `http://localhost:8000/`

This should open the UCSC cell browser in your web browser
