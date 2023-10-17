# DeepSensor: Contributing Guidelines

🎉🎈🍰 Welcome to DeepSensor repository! 🍰🎈🎉

💫🐥 ☀️We're excited that you're here and want to contribute.☀️ 🐥💫

Thank you for considering contributing to DeepSensor! The DeepSensor Python package is motivated by successes in applying neural processes (NPs) to environmental sciences, including sensor placement, forecasting, downscaling, and satellite gap-filling. NPs can efficiently fuse multi-modal and multi-resolution data, handle missing observations, and capture prediction uncertainty. DeepSensor aims to bring this powerful modelling paradigm to practitioners by plugging together the xarray, pandas, and neuralprocesses packages with a user-friendly interface that enables rapid experimentation. Now, our developers and users form an open-source community whose vision is to accelerate the next generation of environmental ML research. We are eager to grow DeepSensor from a young Python package into a large and dedicated software community. By joining our efforts, you will be helping to push the frontiers of environmental sciences. Your presence is welcome and your contributions are truly appreciated.

We want to ensure that every user and contributor feels welcome, included and supported to participate in DeepSensor community. Whether you're a seasoned developer, a machine learning enthusiast, an environmental scientist, or just someone eager to learn and contribute, **you are welcome here**. We value every contribution, be it big or small, and we appreciate the unique perspectives you bring to the project.

We hope that the information provided in this document will make it as easy as possible for you to get involved. If you find that you have questions that are not discussed below, please let us know through one of the many ways to [get in touch](#get-in-touch).

## Inclusivity

We aim to make DeepSensor a collaboratively developed project. We, therefore, require that all our members and their contributions **adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md)**. Please familiarize yourself with our Code of Conduct that lists the expected behaviours.

Every contributor is expected to adhere to our Code of Conduct. It outlines our expectations and ensures a safe, respectful environment for everyone.

## Important Resources

If you'd like to find out more about DeepSensor, make sure to check out:

1. **README**: For a project overview, setup, and usage, please refer to our README.
2. **Project Roadmap**: Familiarize yourself with our direction and goals by checking out [the project's roadmap](https://tom-andersson.github.io/deepsensor/community/roadmap.html).

## Get in touch

The easiest way to get involved with the active development of DeepSensor is to join our regular community calls. The community calls are currently on a hiatus but if you are interested in participating in the forthcoming community calls, which will start in 2024, you should join our Slack workspace, where conversation about when to hold the community calls in the future will take place.

**Slack Workspace**: Join our [DeepSensor Slack channel](https://ai4environment.slack.com/archives/C05NQ76L87R) for discussions, queries, and community interactions. Send us an email at kwesterling@turing.ac.uk to request an invite.

**Email**: If you prefer a more formal communication method or have specific concerns, please reach us at tomandersson3@gmail.com.

If you want to follow along with project developments, you can do so in a number of different ways:

## How to Submit Changes

We follow the same instructions for submitting changes to the project as those developed by [The Turing Way](https://github.com/the-turing-way/the-turing-way/blob/main/CONTRIBUTING.md#making-a-change-with-a-pull-request). In short, there are five steps to adding changes to this repository:

1. **Fork the Repository**: Start by [forking the DeepSensor repository](https://github.com/tom-andersson/deepsensor/fork).
2. **Make Changes**: Ensure your code adheres to the style guidelines and passes all tests.
3. **Commit and Push**: Use clear commit messages.
4. **Open a Pull Request**: Ensure you describe the changes made and any additional details.

### 1. Fork the Repository

Once you have [created a fork of the repository](https://github.com/tom-andersson/deepsensor/fork), you now have your own unique local copy of DeepSensor. Changes here won't affect anyone else's work, so it's a safe space to explore edits to the code!

Make sure to [keep your fork up to date][github-syncfork] with the main repository, otherwise, you can end up with lots of dreaded [merge conflicts][github-mergeconflicts].

If you prefer working in the browser, [these instructions](https://github.com/KirstieJane/STEMMRoleModels/wiki/Syncing-your-fork-to-the-original-repository-via-the-browser) describe how to sync your fork to the original repository via GitHub.

### 2. Make Changes

Try to keep the changes focused.
If you submit a large amount of work all in one go it will be much more work for whoever is reviewing your pull request.
[Help them help you.][jerry-maguire] :wink:

Are you new to Git and GitHub or just want a detailed guide on getting started with version control? Check out our [Version Control chapter](https://the-turing-way.netlify.com/version_control/version_control.html) in _The Turing Way_ Book!

### 3. Commit and Push

While making your changes, commit often and write good, detailed commit messages.
[This blog](https://chris.beams.io/posts/git-commit/) explains how to write a good Git commit message and why it matters.
It is also perfectly fine to have a lot of commits - including ones that break code.
A good rule of thumb is to push up to GitHub when you _do_ have passing tests then the continuous integration (CI) has a good chance of passing everything. 😸

Please do not re-write history!
That is, please do not use the [rebase](https://help.github.com/en/articles/about-git-rebase) command to edit previous commit messages, combine multiple commits into one, or delete or revert commits that are no longer necessary.

### 4. Open a Pull Request

We encourage you to open a pull request as early in your contributing process as possible.
This allows everyone to see what is currently being worked on.
It also provides you, the contributor, feedback in real-time from both the community and the continuous integration as you make commits (which will help prevent stuff from breaking).

GitHub has a [nice introduction][(https://guides.github.com/introduction/flow) to the pull request workflow, but please [get in touch](#get-in-touch) if you have any questions :balloon:.

## First-timers' Corner

If you're new to the project, we recommend starting with issues labeled as ["good first issue"](https://github.com/tom-andersson/deepsensor/issues?q=is:issue+is:open+label:%22good+first+issue%22). These are typically simpler tasks that offer a great starting point. Browse these here.

There's also the label ["thoughts welcome"](https://github.com/tom-andersson/deepsensor/issues?q=is:issue+is:open+label:%22thoughts+welcome%22), which allows for you to contribute with discussion points in the issues, even if you don't want to or cannot contribute to the codebase.

If you feel ready for it, you can also open a new issue. Before you open a new issue, please check if any of [our open issues](https://github.com/tom-andersson/deepsensor/issues) cover your idea already. If you open a new issue, please follow our basic guidelines laid out in our issue templates, which you should be able to see if you [open a new issue](https://github.com/tom-andersson/deepsensor/issues/new/choose).

## Reporting Bugs

Found a bug? Please open an issue here on GitHub to report it. We have a template for opening issues, so make sure you follow the correct format and ensure you include:

- A clear title.
- A detailed description of the bug.
- Steps to reproduce it.
- Expected versus actual behavior.

## Recognising Contributions

We value and recognize every contribution. All contributors will be acknowledged in our CONTRIBUTORS.md file. Notable contributions will also be highlighted in our regular community updates.

DeepSensor follows the [all-contributors](https://github.com/kentcdodds/all-contributors#emoji-key) specifications. The all-contributors bot usage is described [here](https://allcontributors.org/docs/en/bot/usage). You can see a list of current contributors here.

To add yourself or someone else as a contributor, comment on the relevant Issue or Pull Request with the following:

> @all-contributors please add <username> for <contributions>

You can see the [Emoji Key (Contribution Types Reference)](https://allcontributors.org/docs/en/emoji-key) for a list of valid <contribution> types and examples of how this command can be run in [this issue](https://github.com/alan-turing-institute/the-turing-way/issues/274). The bot will then create a Pull Request to add the contributor and reply with the pull request details.

**PLEASE NOTE: Only one contributor can be added with the bot at a time!** Add each contributor in turn, merge the pull request and delete the branch (`all-contributors/add-<username>`) before adding another one. Otherwise, you can end up with dreaded [merge conflicts](https://help.github.com/articles/about-merge-conflicts). Therefore, please check the open pull requests first to make sure there aren't any [open requests from the bot](https://github.com/tom-andersson/deepsensor/pulls/app%2Fallcontributors) before adding another.

What happens if you accidentally run the bot before the previous run was merged and you got those pesky merge conflicts? (Don't feel bad, we have all done it! 🙈) Simply close the pull request and delete the branch (`all-contributors/add-<username>`). If you are unable to do this for any reason, please let us know on Slack <link to Slack> or by opening an issue, and one of our core team members will be very happy to help!

## Need Help?

If you're stuck or need assistance:

- Check our [FAQ](https://tom-andersson.github.io/deepsensor/community/faq.html) section first.
- Reach out on Slack or via email for personalized assistance. (See ["Get in touch"](#get-in-touch) above for links.)
- Consider pairing up with a another contributor for guidance. You can always find us in the Slack channel and we're happy to chat!

**Once again, thank you for considering contributing to DeepSensor. Together, we're shaping the future of environmental machine learning.**

----

These Contributing Guidelines have been adapted from the [Contributing Guidelines](https://github.com/the-turing-way/the-turing-way/blob/main/CONTRIBUTING.md#recognising-contributions) of [The Turing Way](https://github.com/the-turing-way/the-turing-way)! (License: CC-BY)