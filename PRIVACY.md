# Grant Desk privacy policy

- Effective date: November 13, 2026
- Provider: Rizal
- Contact: https://github.com/d0txyz/grant-desk/issues

Grant Desk is an app for Atlassian Jira and Confluence that helps nonprofits find, plan and draft grant applications. This policy explains what data the app handles, where it is kept and what leaves Atlassian.

## What Grant Desk stores

Grant Desk keeps its data in Forge SQL storage, hosted by Atlassian and kept separate for each site that installs the app. It stores:

- **Organization profile:** the details a person enters, such as the organization's name, type, mission, focus keywords, funding categories, award range and preparation time.
- **Funding opportunities:** public records from Grants.gov, such as title, agency, dates, eligible applicants, award amounts and synopsis.
- **Goals and projects:** names, descriptions and links of goals and projects from Atlassian Home, read through the Teamwork Graph for the fit check.
- **Answer library:** copies of sections of the Confluence pages a person chooses, with page titles, links and how often each section was reused.
- **Applications:** steps, owners, due dates, drafts, sources, reviewer feedback and the keys of the Jira work items Grant Desk created.
- **Atlassian account ids:** to record who updated a setting, decided go or no-go, owns a step, or took an action shown in the activity log. Grant Desk does not store names, email addresses or profile pictures.

Grant Desk also creates Jira work items and comments in the Jira space a person chooses, and creates sample Confluence pages only when a person asks for them. Those items live in Jira and Confluence under the site's own settings.

## What leaves Atlassian

Grant Desk sends search keywords and opportunity ids to the public Grants.gov API (api.grants.gov) to find and load funding opportunities. It sends no personal data and no Jira or Confluence content.

Grant Desk has no analytics, tracking or advertising, and does not sell or share data.

## AI features

Grant Desk runs no AI model of its own. Its agent runs in Atlassian Rovo, under Atlassian's terms. If a site admin turns on the app's MCP tools and a person connects an MCP client, the information that person asks for is returned to the client they chose, under that client's terms.

## Access

Grant Desk only works with the Atlassian site it is installed on, within the permissions shown at installation. Its data is available to people who can use the app on that site.

## Closed accounts

Every week Grant Desk reports the account ids it stores to Atlassian, as Atlassian requires. When Atlassian reports an account as closed, Grant Desk erases that account id from its records.

## Retention and deletion

Data stays while the app is installed. Answer library sections are removed at the next daily index after their page leaves the chosen Confluence pages. After a site admin uninstalls the app, Atlassian removes the app's storage under its Forge data rules.

## Changes

Changes to this policy will be posted here with a new effective date.

## Contact

Questions or requests: open an issue at https://github.com/d0txyz/grant-desk/issues. Issues are public; for anything you would rather not post, send a direct message to https://x.com/peper1zal.
