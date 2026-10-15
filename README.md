# VEC Pathway Builder

A small, private-by-design guide that turns four choices—goal, task, compute access, and interface language—into a short route through the Virtual Embryo Challenge's official guidance and existing community resources.

**Languages:** English, German, Spanish, French, Italian, Turkish, Brazilian Portuguese, Simplified Chinese, Japanese, Korean, Hindi, and Arabic.  
**Runtime:** one static HTML file; no dependencies, account, upload, analytics, or server-side processing.  
**License:** MIT.

## Use

Open `index.html` or the [hosted version](https://random-guy-05.github.io/vec-pathway-builder/), choose a goal, task, compute context, and language, then select **Build my route**. Each route has three next steps, direct links, a note about the limits of the route, and a compute-specific setup pointer. Use the browser's print dialog to save a route as PDF.

The four goals are:

- Understand the Challenge and its task/data layout.
- Prepare for a first submission with a translated peer workshop and the current file contract.
- Interpret a local score using official definitions, a task-matched diagnostic, and repeated candidate comparisons.
- Prepare an Agent Team run using the rules, a dry-run harness, and an evidence check.

The selected task changes the workshop or diagnostic. T1, T2, and T3 labels follow the official task descriptions. If the task is not known yet, the route points to the official task page. Cluster users see both Slurm and PBS/LSF starter links.

## What it does not do

This is a route planner, not a model recommender, data viewer, validator, scorer, or guarantee of ranking improvement. It does not read files or send choices anywhere. Official pages are linked live because requirements can change. Community tools have their own scope and limitations; their appearance here does not mean they have been reviewed or endorsed. Check the current official resource list before relying on any community contribution.

The interface and route guidance are translated. Linked third-party pages remain in the language in which their authors published them. The task and first-workflow workshops currently link to matching editions in all 12 supported languages. Translations in this first edition have not had independent native-speaker review; correction requests are welcome.

## Maintain

The app is intentionally self-contained in `index.html`. To add a language, add its complete locale record, include it in the supported workshop language list only if those files exist, and review the page in left-to-right and right-to-left layouts as applicable. To change any Challenge-specific guidance, check the linked official page and record the source/date in `SOURCES.md`.

## Sources

See [`SOURCES.md`](SOURCES.md) for the official pages, linked community projects, and the facts this route planner uses.
