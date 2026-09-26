# Thalia Agent

**A planned open-source assistant for human-reviewed follow-up on B2B proposals.**

Thalia Agent is intended to help small B2B teams find sent proposal conversations that may need follow-up. A person reviews each conversation, chooses whether to act, and can use a prepared draft as a starting point. The person remains responsible for deciding what to send and sending it.

## What it is intended to do

| Step | Purpose |
| --- | --- |
| Find a conversation | Bring sent proposals with no reply back into view for review. |
| Review what happened | Let a person decide whether to follow up now, later, not at all, or mark the candidate as lost, mistaken, or uncertain. |
| Prepare a draft | Provide suggested wording for a person to review and send themselves. |

These are plans, not features available in the current repository.

## Project status

This repository contains the static project website and planning documents. The agent has not been built, and its source code has not been published. There is no email integration, automatic message sending, installable agent, or release date.

- [Project website source](index.html)
- [About the project](about.html)
- [Planned workflow](workflow.html)
- [Current status](status.html)

The site itself is not yet deployed to a public web address. Its production domain and hosting have not been selected.

## Preview the website

The site uses plain HTML and CSS, with no build step or runtime dependencies. From the repository root, run a local static file server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## License

The website text and source code are available under the [MIT License](LICENSE). The planned agent is intended to use MIT when its source is published. Bundled fonts are licensed separately under the SIL Open Font License; see [the font license](assets/fonts/LICENSE.txt).

## Contact

For questions or feedback, email [cybersec-star@proton.me](mailto:cybersec-star@proton.me).
