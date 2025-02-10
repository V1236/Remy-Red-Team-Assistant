# Remy-Red-Team-Assistant
Remy is an AI assistant for pentest/red-teaming. They can be interacted with like any regular chat bot, ask questions give commands, etc.
Remy watches a log file (natively VforMSF.log) saving any important data that comes through the log, such as CVE's, open ports, subdomains, endpoints, etc for your review.

Remy was made as an assistant for https://github.com/V1236/VforMSF but, with some changes, can be useful independently.

If running by itself, the Start_VforMSF.sh needs to be edited so that it begns logging a different script than "python3 VforMSF.py". You could have it log a bash terminal by simply replacing "python3 VforMSF.py" with "bash".

Also it utilizes an openai API key so insert your own key in the place that calls for it, if you want full functionality.

Usage:

'''
python3 assistant.py
'''

What can Remy do?

[Remy] - Need help? Here’s what I can do! 💜
    - 'clear' : Reset conversation history
    - 'all' : Show all gathered notes
    - 'generate' : generate a shell from a list of shell types
    - 'shells' : Show all generated shells
    - 'ports' : Show noted ports/services
    - 'vulns' : Show noted vulnerabilities
    - 'crawled' : Show URLs found by spider
    - 'dirb' : Show results from DIRB scan
    - 'subdomains' : Show results from subfinder scan
    - 'endpoints' : Show all endpoint results
    - 'ffuf' : Show results from an ffuf scan
    - 'write' : Write a manual note
    - 'notes' : Show the written notes
    - 'delete' : Delete a written note
    - 'export' : Save all findings to a file
    - 'help' : Show this menu
    - 'exit' : Quit

[Remy] - I can also add domains to /etc/hosts & recommend what to do next, just ask! 💜

There is also built in automation like automatically searching searchsploit and metasploit for modules when a viewing vulnerability details.
