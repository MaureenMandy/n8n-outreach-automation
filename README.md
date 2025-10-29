# n8n Outreach Automation

This project automates the process of generating and managing personalized outreach messages using **n8n**. It combines workflow automation, AI-generated content, and Google integrations to streamline email and LinkedIn communication tasks.



##  Overview

The **n8n Outreach Automation** system automates lead engagement workflows by:

* Generating personalized **email** and **LinkedIn messages** using AI prompts
* Randomly selecting prompt variations for **A/B testing**
* Sending or exporting outputs to **Google Sheets**
* Logging daily results into **Google Docs** for easy review

The project includes the **overall project report**, **workflow exports**, and visual documentation (screenshots and recordings).

---

##  Tech Stack

* **n8n** – Core workflow automation platform
* **OpenAI API** – AI text generation
* **Google Sheets API** – Output data storage
* **Google Docs API** – Daily summary logging
* **JavaScript / JSON** – Node logic customization

---

##  Features

* Randomized prompt testing to evaluate outreach tone and effectiveness
* Dual message generation: Email + LinkedIn for each lead
* Daily batch processing (runs on defined test lead sets)
* Automatic output logging to Google Sheets & Docs
* Fully modular and customizable workflow design

---

##  Repository Contents

| Folder / File  | Description                                    |
| -------------- | ---------------------------------------------- |
| `workflows/`   | Sanitized n8n workflow JSON exports            |
| `docs/`        | Project report and supporting documents        |
| `assets/`      | Screenshots and demo visuals                   |
| `media/`       | Screen recording of automation run             |
| `.env-example` | Example environment file (without credentials) |
| `LICENSE`      | License for open sharing                       |
| `README.md`    | This documentation file                        |

---

##  How to Use

1. Install n8n (self-hosted or desktop version).
2. Import the workflow:

   * Open n8n → *Workflows → Import from File* → select the JSON from `workflows/`.
3. Set up credentials inside n8n:

    Add your Google Sheets, Google Docs, and OpenAI API keys (not shared in this repo).
4. Test with sample leads to generate output in Sheets & Docs.

---

## Documentation

* Project Report: Detailed overview of objectives, design, and implementation.
* Screenshots & Screen Recording: Demonstrate the automation in action.
* QA Summary: Embedded in the report to highlight testing and results.

---

##  Security

All sensitive credentials and API keys have been removed for safety.
Please configure your own credentials in n8n when replicating the workflow.

---

##  Future Enhancements

* Add CRM integration (HubSpot / Notion)
* Implement automated success rate analytics
* Deploy as a reusable n8n template

---

##  License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

##  Author

Maureen Mandy
Project: *n8n Outreach Automation*
Connect on [LinkedIn](https://linkedin.com/) | View more on [GitHub](https://github.com/MaureenMandy)
