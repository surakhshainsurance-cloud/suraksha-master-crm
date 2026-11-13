# Single API Endpoint Spec

## Rule
ONE endpoint. All connectors route through it.

## Routes
- /crm/gmail — read, audit, export
- /crm/drive — read, write, mirror
- /crm/whatsapp — export, organize (phone or web)
- /crm/instagram — content, captions
- /crm/calendar — events, reminders
- /crm/github — repo, files, automations
- /crm/bots — send prompt, read transcript, list agents
- /crm/mp — warehouse update, refined output
- /crm/finance — balance, audit, reports
- /crm/market-rush — trades, backtest
- /crm/marg — ERP extraction

## Auth
No manual login. Session tokens encrypted at rest. One-time setup.

## Output Format
Screen: answer + 2 options (solution, dust) with 20 solutions each.
Cloud: full file, maintained, searchable.

## Learning Loop
Every output feeds back into raw journal. Bots read own job-profile book daily. Skills compound.