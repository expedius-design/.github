# Contributing

We would ❤️ for you to contribute to Expedius and help make it better! These are the guidelines to help you with contributing to Expedius in a fun, enjoyable and educational way. Any sort of contributions are welcome whether it's a issue, docs, bugs & tweaks, feature, etc.

## Code of Conduct

Please read and follow our [Code of Conduct](/CODE_OF_CONDUCT.md). This helps to keep the community safe :)

## Submit a Pull Request 🚀

Branch naming convention is as following 

`TYPE-ISSUE_ID-DESCRIPTION`

example:
```
feat-548-contribution_guidelines
```

Where `TYPE` can be:

- **feat** - is a new feature
- **doc** - documentation only changes
- **cicd** - changes related to CI/CD system
- **fix** - a bug fix
- **refactor** - code change that neither fixes a bug nor adds a feature

**All PRs must include a commit message with the changes description!** 

For the initial start, fork the project and use git clone command to download the repository to your computer. A standard procedure for working on an issue would be to:

1. `git pull`, before creating a new branch, pull the changes from upstream. Your main/master needs to be up to date.
```
$ git pull
```
2. Create new branch from `master` like: `doc-548-submit-a-pull-request-section-to-contribution-guide`<br/>
```
$ git checkout -b [name_of_your_new_branch]
```
3. Work - commit - repeat ( be sure to be in your branch )

4. Push changes to GitHub 
```
$ git push origin [name_of_your_new_branch]
```

5. Submit your changes for review
If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.
6. Start a Pull Request
Now submit the pull request and click on `Create pull request`.
7. Get a code review approval/reject
8. After approval, maintainers will merge your PR
9. GitHub will automatically delete the branch after the merge is done. (they can still be restored).

## Security & Privacy

Security and privacy are extremely important to Expedius, developers, and users alike. Make sure to follow the best industry standards and practices.

## Dependencies

Please avoid introducing new dependencies to Expedius without consulting the team. New dependencies can be very helpful but also introduce new security and privacy issues, complexity, and can impact the build.

Adding a new dependency should have vital value on the product with minimum possible risk.

## Introducing New Features

We would 💖 you to contribute to Expedius, but we would also like to make sure Expedius is as great as possible and loyal to its vision and mission statement 🙏.

For us to find the right balance, please **open an issue** explaining your ideas before introducing a new pull request.

This will allow the Expedius maintainers and community to have sufficient discussion before starting work on the idea.

## Other Ways to Help

Pull requests are great, but there are many other areas where you can help Expedius. 

- Sending Feedbacks & Reporting Bugs
- Submitting New Ideas
- Improving Documentation
