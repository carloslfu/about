# How to use the handbook

## Usage

1. You have a question/problem, or you need to follow a process.
1. You look it up in the handbook.
   - If the handbook has what you need, you're done!
   - If the handbook is missing what you need or is inaccurate/outdated, ask for help (on Slack, Zoom, etc.) and ensure the handbook is updated.
   
Join the `#handbook` Slack channel to see proposed changes.

## Handbook guidelines

1. Most guidelines in this handbook are meant to help and aren't absolute rules (unless stated).
1. If you ask a question and someone answers with a link to the handbook, they are doing so because the handbook has the best answer for your question. They may also be proud that the answer is documented. It doesn't mean you shouldn't have asked the question or that you should've memorized the entire handbook (nobody has memorized or is expected to memorize the entire handbook).
1. If someone replies to a question with a typed-out answer that essentially matches what's in the handbook, gently remind them to link to the handbook instead.
1. If you ask a question that isn't answered in the handbook, it's likely that someone else will have the same question in the future. Document the answer by updating the handbook to help everyone else, or clearly pass along the responsibility to do so to someone else ("Who will document this?").
1. The handbook documents what we do right now. It doesn't describe the ideal practices we hope to follow in the future.
1. In the early stages of using the handbook, it will be missing a lot of information. Be extra diligent (and patient) in adding to and updating it.

### Changing or defining a process

1. If you want to change a guideline or process, propose an edit to the handbook (by creating a pull request). Discuss the change on the pull request.
   - Don't discuss or draft the changes in some other channel (Slack, Google Doc, etc.) first. If (for example) you start discussing a proposed change on Slack and then create a PR, you'll end up with half of the discussion on Slack and the other half on the PR, which results in confusion and duplication.
   - Learn [how to propose an edit the handbook](editing.md).
1. If someone replies to a question with a newly typed-out answer that differs from what's in the handbook, gently ask them to either follow what's in the handbook or propose an edit to the handbook.
1. To announce a changed or newly documented process, post a link (in Slack, and elsewhere as needed) to the merged commit that contains the before-and-after changes to the handbook.
   - In your message announcing the change, just include `[Handbook/process] change:`, the commit message subject, and the link. Don't write a separate summary of the change (if you feel the need to do so, you should have used a better commit message).
   - Ensure everyone who needs to be aware of the change is made aware. If you see people do things that indicate they aren't aware, gently remind them of the change. If you don't nudge them, other people will see them doing things the wrong/old way and start to doubt the handbook's accuracy or currency.
1. Strongly prefer creating a pull request over filing an issue on the handbook or mentioning it on Slack, even if you aren't able to propose the full edits you'd like to make.
1. Follow the [style guide](communication/style_guide.md) and [documentation guidelines](documentation/index.md) when making changes to the handbook.

## Why handbook-first?

Being handbook-first means using the handbook as the source of truth for answers and processes.

- You can (and must) always rely on the handbook being accurate and up-to-date.
- You're responsible for keeping your own (and your team's) handbook sections accurate and up-to-date. If it's not, someone else (who is relying on the handbook being accurate and up-to-date) will end up wasting time or breaking something.

To be handbook-first, we need to be very diligent about maintaining the handbook. This takes a lot more time than just doing things and not writing things down. But being handbook-first is worth it because it yields better processes and helps us work together efficiently as we grow:

1. A written process is followed more closely and frequently than an informal one, which means more people and iterations to improve it.
1. A written process that you trust to be up to date and accurate
1. Anyone can propose improvements to a written-down process.
1. New teammates can onboard more quickly by reading our handbook to understand background information and processes.
1. When you go on vacation or to sleep, you can relax knowing that nobody will be blocked while you're not working.

## Searching the handbook

Search the handbook using the search box in the top navigation on https://about.sourcegraph.com/handbook.

### Google Chrome

If you use Google Chrome, you can add a Sourcegraph handbook search shortcut to the address bar.

#### Setup

1. Open Chrome settings > **Manage search engines** (or go to chrome://settings/searchEngines directly).
1. Next to "Other search engines", press the **Add** button.
1. In the "Add search engine" form, enter:
   - Search engine: `Sourcegraph handbook`
   - Keyword: `hb` (or some other shortcut of your choosing)
   - URL with %s in place of query: https://about.sourcegraph.com/search?q=%s
1. Press the **Add** button.

#### Usage

1. Focus in Chrome’s address bar (by clicking, tapping, or pressing <kbd>⌘L</kbd> on macOS or <kbd>Ctrl+L</kbd> on Linux).
1. Type the keyword you entered previously (e.g., `hb`) then press <kbd>Tab</kbd>.
1. Type in a query and press <kbd>Enter</kbd>.

## Wiki and Google Docs handbooks become stale

Being [handbook-first](#why-handbook-first) requires the handbook to be up to date. It is very difficult to keep handbooks in wikis and Google Docs up to date because:

1. Many handbook changes require updating references and mentions across multiple pages (e.g., changing a product usage metric's name or a dashboard's URL might require updates to 10+ pages across the product, marketing, and sales sections). In wikis and Google Docs, there is no easy way to propose a *group* of changes to multiple sections or pages. In Google Docs, for example, each edit operation is shown separately. As a result, people making and reviewing edits can easily miss other places that need to be updated.
1. Many handbook changes are collaborative and need to be reviewed, revised, and commented on by other teammates. Wikis don't make this easy or possible, and Google Docs has very limited review and no revision capabilities.

We chose Markdown files in a Git repository for the handbook because it allows grouped multi-page changes and collaboration. This is more complicated than wikis or Google Docs, but we commit to help every teammate [learn how to edit this handbook](editing.md).

## Why make this handbook public?

Sourcegraph is an [open product, an open company, and open source](../company/open_source_open_company.md). Our company principles, strategies, and processes are all publicly documented.

## Acknowledgements

Portions of this documentation are derived from [GitLab's handbook](https://docs.gitlab.com) (see [license](https://gitlab.com/gitlab-com/www-gitlab-com/blob/master/LICENCE)).