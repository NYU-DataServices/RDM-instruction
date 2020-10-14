## Contribute!

If you'd like to contribute, that would be amazing! I will try my best to be on top of merge requests and issues. If you aren't comfortable with coding or Git, you can email me ([vicky dot steeves at nyu dot edu](mailto:vicky.steeves@nyu.edu)) changes you'd like to see and I will open an issue for you or, if it's quick enough, make the change and give you attribution on this README.

Here are some general instructions to help -- the following was adapted from [ProjectPorcupine's](https://github.com/TeamPorcupine/ProjectPorcupine)'s [CONTRIBUTING.md](https://github.com/TeamPorcupine/ProjectPorcupine/blob/main/CONTRIBUTING.md).

Pease follow the [Code of Conduct](CODE_OF_CONDUCT.md) in all your interactions with the project. If you would like to contribute to this project by modifying/adding to the code or data, please feel free to follow the standard GitHub workflow:

1. Fork the project (the second button to the left under the title of the repo)
2. Clone your fork to your computer.

 * From the command line: `git clone https://gitHub.com/<USERNAME>/RDM.git`

3. Change into your new project folder.

 * From the command line: `cd RDM`

4. [optional]  Add the upstream repository to your list of remotes.

 * From the command line: `git remote add upstream https://@gitHub.com:NYU-DataServices/RDM.git`

5. Create a branch for your new feature.

 * From the command line: `git checkout -b my-feature-branch-name`

6. Make your changes.

 * Avoid making changes to more files than necessary for your feature (i.e. refrain from combining your "real" pull request with incidental bug fixes). This will simplify the merging process and make your changes clearer.

7. Commit your changes. From the command line:

 * `git add <FILE-NAMES>`
 * `git commit -m "A descriptive commit message"`

8. While you were working some other changes might have gone in and break your stuff or vice versa. This can be a *merge conflict* but also conflicting behavior or code. Before you test, merge with main.

 * `git fetch upstream`
 * `git merge upstream/main`

9. Test. Run the program and do something related to your feature/fix.
10. Push the branch, uploading it to GitHub.

  * `git push origin my-feature-branch-name`

11. Make a "Pull Request" from your branch here on GitHub

### Best Practices for Contributing

* Before you start coding, open an issue so that the community can discuss your change to ensure it is in line with the goals of the project and not being worked on by someone else. This allows for discussion and fine tuning of your feature and results in a more succent and focused additions.

    * If you are fixing a small glitch or bug, you may make a MR without opening an issue.
    * If you are adding a large feature, create an issue so that we may give you feedback and agree on what makes the most sense for the project before making your change and submitting a MR (this will make sure you don't have to do major changes down the line).

* Merge Requests are eventually merged into the codebase. Please ensure they are:

    * Well tested by the author. It is the author's job to ensure their code works as expected.

* If your code is untested, log heavy, or incomplete, you can use GitHub's [Work In Progress (WIP) feature](https://docs.GitHub.com/ce/user/project/merge_requests/work_in_progress_merge_requests.html) on your merge request so others know it is still being tested and shouldn't be considered for merging yet. This way we can still give you feedback or help finalize the feature even if it's not ready for prime time.

That's it! Thanks for your contribution!

## Contact info

You are welcome to email me at [vicky dot steeves at nyu dot edu](mailto:vicky.steeves@nyu.edu) if you have questions or concerns, or raise an issue on this repository and I will do my best to respond quickly!
