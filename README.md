# Kindle Vocab Context Tool

This is a simple tool to help you learn new words from your Kindle vocabulary.

## How to use
Place the `vocab.txt` file from your Kindle in the root directory of this project. Then run the following command:

```bash
python main.py
```

This will generate a new file called `vocab_with_definitions.csv` which will contain the words from your Kindle vocabulary along with their definitions.

## How it works
The script reads the `vocab.db` file from your Kindle and extracts the words along with the sentences in which they were used.
These words are then passed to the OpenAI API to generate definitions for them.

## Future improvements
- Automatically fetch the `vocab.db` file from your Kindle
