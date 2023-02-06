# Ethereum-Smart-Contract-Analysis-through-chat-gpt-and-other-AI-techniques
This code is written in Python and is using the OpenAI API to analyze smart contract Solidity code for weaknesses. The code sets the API key for OpenAI and sets the path to a directory containing smart contract files. It then retrieves the list of file names in the directory and stores it in a variable called "file_names".
If the directory is empty, the code will print "Directory is Empty". If not, the code opens a .csv file called "resultscontract5.csv" and writes the header row with the column names "File Name" and "ChatGPT Response".

For each file in the directory, the code reads the contents of the file and sends it as a prompt to the OpenAI API with the prompt asking "what is the weaknesses in the following smart contract solidity code?" The API returns a text response, which the code then writes to the .csv file along with the file name. The code uses a try-except block to handle any exceptions that might occur during the API call.
