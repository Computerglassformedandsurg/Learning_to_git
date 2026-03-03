# Learning to Git 

### Lesson 1: The Professional Git Workflow

* **Branching:** Creates a safe "parallel universe" to experiment without breaking your main code.
* **Committing:** Saves a permanent snapshot of your progress to the cloud.
* **Pushing:** Sends your local work to GitHub so you can access it on other devices like your phone.
* **Pull Request (PR):** Opens a comparison page to review your new changes against the old version.
* **The Diff:** Highlights exactly what was added (green) or removed (red) for easy revision.
* **Merging:** Permanently moves your tested "experimental" code into your main project folder.
* **Deleting:** Removes the temporary branch once the work is safely merged to keep the project clean.
* **BGR Order:** A reminder that OpenCV reads color channels as Blue-Green-Red instead of the standard RGB.

To contribute to a major open-source project like **MONAI** (Medical Open Network for AI), you use the exact workflow you just practiced, with one extra step at the beginning called "Forking."

### How to Contribute to MONAI

* **Forking:** Click the "Fork" button on the [MONAI GitHub page](https://github.com/Project-MONAI/MONAI) to create your own copy of their entire project under your account.
* **Cloning:** Download your fork to your laptop so you can work on it locally.
* **Branching:** Create a new branch (e.g., `fix-documentation` or `new-tutorial-fix`) so your changes are organized.
* **Coding:** Make your improvements, fix a bug, or clarify their documentation in your branch.
* **Committing:** Save your changes with a clear message explaining what you did.
* **Pushing:** Upload your branch from your laptop back to your GitHub fork.
* **Pull Request (PR):** Go to the original MONAI repository and click "New Pull Request" to ask them to "pull" your changes into their official code.
* **Review:** Wait for the MONAI maintainers to look at your code, leave comments, or ask for small logic changes.
* **Merging:** Once they approve, they will click the merge button, and your code becomes a permanent part of the global MONAI project.

### Pro-Tip for Beginners

Don't try to fix complex AI math on day one! Look for the **"Good First Issue"** label in their [Issues tab](https://github.com/Project-MONAI/MONAI/issues). These are usually small documentation typos or simple bugs meant specifically for people like you who are practicing their Git skills.
