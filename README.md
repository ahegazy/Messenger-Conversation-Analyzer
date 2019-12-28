# Facebook Messenger Conversation Analyzer

## Getting started

### 1. Install Python 3+

### 2. Download Facebook Messenger Data

To download your Facebook Messenger data, press the arrow symbol in the upper right hand corner and then press *settings*. In the menu to the left, press *Your Facebook Information*. In the center field, press *show* under *Download Your Information*.
Select **JSON** file format and (optionally) select only messages. 
The Facebook download will be prepared which may take some time.

### 3. Extract Facebook Download

Place the folder called *messages* in the project folder of this repository.

### 4. Run program

First, install the requirements by running 
```
pip3 install -r requirements.txt
```
in the command line / Terminal.

Then run

```
python3 analysis.py
```
and follow the instructions.

### 5. Results

The script will generate a PDF file called *Conversation_analysis.pdf* which will be opened automatically.
