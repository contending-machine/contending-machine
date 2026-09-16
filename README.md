# Name-of-the-Machine
A machine that is a contender with other entities.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Do you want to object, machine?" \
  | uvx contending-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install contending-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
contending-machine -a multilogue.txt
```
Or:
```bash
contending-machine multilogue.txt > response.txt
```
Or:
```bash
contending-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import contending_machine
```
