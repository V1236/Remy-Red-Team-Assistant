# Remy-Red-Team-Assistant
Remy is an AI assistant for pentest/red-teaming. Remy watches a log file (natively VforMSF.log) saving any important data that comes through the log, such as CVE's, open ports, subdomains, endpoints, etc..

Remy was made as an assistant for https://github.com/V1236/VforMSF but, with some changes, can be useful independently.

If running by itself, the Start_VforMSF.sh needs to be edited so that it begns logging a different script than "python3 VforMSF.py". You could have it log a bash terminal by simply replacing "python3 VforMSF.py" with "bash".

Also it utilizes an openai API key so insert your own key in there if you want full functionality.

Usage:

'''
python3 assistant.py
'''
