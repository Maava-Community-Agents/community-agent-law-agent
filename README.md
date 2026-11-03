# Law Agent

Explains laws and rights that matter to schools, teachers, creators and child-focused organisations in plain language, with sources.

Ask about copyright for classroom and online content, child data protection, safeguarding duties, contracts or education rights. It explains the rule in plain language for your country, links to the official text, and says when you need a qualified lawyer. It does not give legal advice or represent anyone.

## Run it

Needs a running [maava gateway](https://github.com/maavadao/maava-gateway) with its chat endpoint
enabled. See the [getting started guide](https://github.com/Maava-Community-Agents/maava-Community-Agents/blob/main/docs/getting-started.md).

```bash
pip install -r requirements.txt
cp .env.example .env   # then set MAAVA_GATEWAY_TOKEN
export $(grep -v '^#' .env | xargs)
python src/main.py "your request"
```

Its brief is in [`instructions.md`](instructions.md).

## Data

Content you provide is processed to answer you and is not kept after the session. No accounts or analytics.

## Part of maava Community Agents

This agent is one of the [maava Community Agents](https://github.com/Maava-Community-Agents/maava-Community-Agents),
listed on [maavadao.com/agents](https://maavadao.com/agents). Read the
[rules](https://github.com/Maava-Community-Agents/maava-Community-Agents/blob/main/RULES.md) and
[contributing guide](https://github.com/Maava-Community-Agents/maava-Community-Agents/blob/main/CONTRIBUTING.md)
before you open a pull request. When the agent earns money, 60% rewards the developer community
who built it and 40% goes to Maava Charity to educate children in need.

## Licence

Apache 2.0.
