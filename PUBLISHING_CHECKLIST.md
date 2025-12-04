## ✅ Workflow Publishing Checklist

This checklist is designed to ensure that workflows are thoroughly reviewed and ready for publication. It covers content quality, technical accuracy, review processes, and final launch steps.

> [!NOTE]
> Not everything is applicable to every workflow. Use discretion to determine which items are relevant to your specific case.

### 📝 I. Content

| Status | Task | Notes |
| :---: | :--- | :--- |
| - [ ] | **Workflow name:** Is the workflow name distinctive, and findable? | Does the name set it apart from other tools? Could you find it easily though a web search? |
| - [ ] | **Introduction:** Does the intro clearly state the workflow's purpose? | |
| - [ ] | **Quick Start:** Are there clear instructions to start using the workflow? | The lower the barrier to get from input to output means better adoption |
| - [ ] | **System requirements:** Is it clear what is needed for the code to run? | Will it run on your laptop, or do you need a HPC or Cloud Service? Do you need storage? Do you need GPU's/TPU's? |
| - [ ] | **Input:** Describe what kind of input is supported | |
| - [ ] | **Configuration:** Is there documentation on how to configure your workflow | How does one change parameters to tools used in your workflow? |
| - [ ] | **Output:** Is there documentation on what output is generated? | What files are created, and where are they located? How should they be interpreted? |
| - [ ] | **Examples:** Are there example commands and datasets to test the workflow? | Provide small test datasets and example commands to get users started quickly. |
| - [ ] | **Packaged Dependencies:** Are all the dependencies packaged? | Use appropriate conda channels or package indexes to package dependencies so they're easy to install/use |
| - [ ] | **Citations:** Are there references to relevant publications or resources? | |
| - [ ] | **Body:** Is the content logically structured, well-researched, and free of grammatical errors? | Use tools like Grammarly/spell checker. |
| - [ ] | **Tone/Style:** Does the article adhere to the organization's voice and style guide? | Check for consistent terminology. |
| - [ ] | **Visuals:** Are all images, charts, and videos relevant, high-quality, and properly attributed? | All images should have alt text for accessibility. |

### ⚙️ II. Technical

| Status | Task | Notes |
| :---: | :--- | :--- |
| - [ ] | **Versioned:** Is your workflow versioned? | Use semantic versioning, for example, to disclose when breaking changes are included. |
| - [ ] | **Managed Environment:** Is your workflow packaged so no changes must be made | Make sure there are no hard coded absolute paths. |
| - [ ] | **Secrets Management:** Check secrets like passwords and API keys are not exposed in your workflow. | Sensitive information should be properly managed. |
| - [ ] | **Authentication:** Is authentication needed? | If authentication is needed, ensure it is correctly handled, for example, handling sensitive data. |
| - [ ] | **API access:** If your workflow uses API's, is it resilient to failures in external services? | |
| - [ ] | **Input/Output specification:** Is the input and output explicitly and clearly defined? | File specifications can vary from tool to tool, even when following a standard. Ensure a clear description of expected input. |
| - [ ] | **Error Handling:** Have you made a best effort to handle errors? | Provide clear instructions on how to proceed when an error occurs. |
| - [ ] | **Observability:** Is it possible to monitor how far along your workflow is? | Is there any way to alert when a process is taking too long? |
| - [ ] | **Audit Trail:** Is there a trail of actions performed in your workflow? | |
| - [ ] | **Visual Documentation:** Is there an image of the workflow's technical logic? | Use images to convey larger concepts. |
| - [ ] | **Image Alt Text:** Does every image have descriptive alt text for accessibility and SEO? | |
| - [ ] | **Support system:** Is it easy to get support when something doesn't work? | Make sure users have clear instructions how to get help. |
| - [ ] | **Maintenance:** Is there a maintenance plan? | Publishing should not be the end goal. Maintenance is often as much work as developing the workflow. |

### 👥 III. Review and Approval

| Status | Task | Reviewer |
| :---: | :--- | :--- |
| - [ ] | **Self-Review:** The writer has performed a final check against this list. | Self, Colleague |
| - [ ] | **Editor Review:** Content approved for clarity, accuracy, and tone. | Supervisor |
| - [ ] | **Legal/Compliance Review (if required):** Content checked for any legal or privacy issues. | Legal team |

### 🚀 IV. Final Launch Steps

| Status | Task | Notes |
| :---: | :--- | :--- |
| - [ ] | **Preview Check:** Is the content displayed correctly on desktop and mobile devices? | Check responsiveness. |
| - [ ] | **Category/Tagging:** Is the workflow assigned to the correct categories and tags? | |
| - [ ] | **Indexing:** Is it indexed on workflow hub or other appropriate index? | |
| - [ ] | **Post-Publish:** Check the live repository and website for broken links, 404s, or rendering issues. | |
| - [ ] | **Promotion:** Prepare and schedule social media posts for promotion. | |