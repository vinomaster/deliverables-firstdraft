# ![toip-logo](https://avatars0.githubusercontent.com/u/61128026?s=200&v=4) Contributing Deliverables

As a member contributor, here are the guidelines that you should follow.

Use this repository to contribute to this project as easy and transparent as possible, whether it's:

* Reporting a bug
* Discussing the current state of the ToIP Deliverable
* Submitting a fix
* Proposing process recommendations
* other

Our [GitHub Repo](https://github.com/trustoverip/deliverables) is used to host all the deliverables of the ToIP Foundation. We standard GitHub activities to track issues and feature requests, as well as accept all Pull Requests (`PR's`) related to the deliverables we manage.

## GitHub Workflow

* [Issue Submission / Tracking](./github-issues.md)
* [Pull requests](./github-pullrequests.md)
* Organization Resources
    * [Code of Conduct](../CODE_OF_CONDUCT.md)
    * [ToIP GitHub Organization Management Policy](https://github.com/trustoverip/admin/blob/master/GITHUB_ORG_MANAGEMENT_POLICY.md)
* General GitHub Resources
    * [Issue Creation](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)
    * [PR Creation](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
    * [Creating a PR from a Fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)

## Preparation

Before proposing a new deliverable, consider the following preparatory actions:

1. Exploring the idea in the appropriate WG Slack Channel.
2. Socialize the idea during a WG meeting.
3. Make use of the mailing lists to socialize the idea and to make an assessment that your proposal is novel and you will not be overlapping work already proposed. Encouraging feedback from maintainers is a good sign that you're on the right track.
4. Make use of the [Deliverables Index](../index.md]) for a current listing of all work product efforts and their statuses so that you can appropriately position your proposal as unique.
5. Make a decision as to the [type of deliverable](./work_products.md) you will be proposing.

## Submit a Proposal

1. Fork [Deliverables Repo](https://github.com/trustoverip/deliverables).
2. Decide which parent folder is appropriate for your new deliverable. See [ToIP Deliverables - Table 1](./work_products.md).
    * In a terminal window, change directories to the `<parent folder name>`
3. Pick a descriptive folder name for your new deliverable. Don't pick a number yet.
    * Decide on a clear and simple name that is descriptive, yet not verbose or vague.
    * Create a new folder under the appropriate deliverable type folder: `<your folder name>`
    * Navigate into your new folder.
4. Copy the appropriate **template file** for your type of deliverable to your new folder.
5. Fill in the **template file**. [Use MUST and SHOULD per standard conventions](https://tools.ietf.org/html/rfc2119). Put care into the details: Deliverable submissions that do not present suffifient information as requested by the **template file** tend  to be poorly received. You can add supporting artifacts and organize your folder as desired. You MAY want to :
    * Create an `images` folder
6. Consider how your new proposal should be [tagged](../tags.md).
7. Assign a number to your deliverable submissiomn. Get the number by loading <a target="rfcnum"
    href="https://trustoverip.github.io/next-deliverable-num/">this web page</a> (or,
    if you want to do it the hard way, by inspecting open and closed PRs against
    this repo to figure out what the next PR number will be). Rename your folder from
    `<your folder name>` to `<your 4-digit number>-<your folder name>`. At the
    top of your README.md, modify the title so it is in the form: `<your 4-digit
    number>: Friendly Version of Your Title`. Commit your changes.
8. In the root of the repo, run `python code/generate_index.py` to update the index
    with your new Deliverable proposal.
9. In the root of your repo, run `pytest code` to see whether your Deliverable passes all automated tests. The  tests are simple. They just check for things like naming conventions and hyperlink correctness.
10. Commit the updated version of `/index.md` and push your changes.
11. Submit a pull request.
    * Make sure that all of your commits satisfy the [DCO requirements](https://github.com/probot/dco#how-it-works) of the repo and conform to the license restrictions noted [below](#intellectual-property).
    * The ToIP Deliverable Maintainers will check to see if the process has been followed, and request any process changes before merging the PR.
    * When the PR is merged, your RFC is now formally in the **Proposed** state.

### Changing the Status of a Deliverable

The lifecycle of a deliverable is driven by the author or current champion of the deliverable.

![lifecycle](../_images/lifecycle.png)

To modify the state of a deliverable, submit a PR with the following characteristics:

* The PR should __ONLY__ change the deliverable status. Note that this requires refreshing the index (`python code/generate_index.py && pytest code`).
* The title of the PR should include a deadline date for merging the PR and the referenced deliverable.
    * Example: `Status to Accepted, deadline 2019.08.15, PLAN 999-cool-stuff`
* The PR comment should document why the status is being changed.
* The deadline date should be 2 weeks after announcing the proposed status change on an ToIP SC call. The PR should also be announced on the appropriate WG Slack channel.
* Barring negative feedback from the community, the repo's maintainers should merge the PR after the deadline.
* The deadline should be moved by two weeks after addressing each substantive change to the deliverable made during the status change review period.

### How to get a deliverable approved
Work through the incubation process defined by the WG that is sponsoring your deliverable.

### How to get a deliverable accepted
An accepted deliverable is a standards-track document. It becomes an acknowledged standard and/or Foundation-level work product.

### Intellectual Property

This repository is licensed under an [Apache 2 License](LICENSE). It is protected by a [Developer Certificate of Origin](https://developercertificate.org/) on every commit. This means that any contributions you make must be licensed in an Apache-2-compatible way, and must be free from patent encumbrances or additional terms and conditions. By raising a PR, you certify that this is the case for your contribution.

### Signing off commits (DCO)

If you are here because you forgot to sign off your commits, fear not. Check out [how to sign off previous commits](#how-to-sign-off-previous-commits)

We use developer certificate of origin (DCO) in all Hyperledger repositories, so to get your pull requests accepted, you must certify your commits by signing off on each commit.

#### Signing off your current commit
  - `$ git commit -s -m "your commit message"`
  - To see if your commits have been signed off, run `$ git log`. Any commits including a line with `Signed-off-by: Example Author <author.email@example.com>` are signed off.
  - If you need to re-sign the most current commit, use `$ git commit --amend --no-edit -s`.

The `-s` flag signs off the commit message with your name and email.

#### How to Sign Off Previous Commits

1. Use `$ git log` to see which commits need to be signed off. Any commits missing a line with `Signed-off-by: Example Author <author.email@example.com>` need to be re-signed.
2. Go into interactive rebase mode using `$ git rebase -i HEAD~X` where X is the number of commits up to the most current commit you would like to see.
3. You will see a list of the commits in a text file. **On the line after each commit you need to sign off**, add `exec git commit --amend --no-edit -s` with the lowercase `-s` adding a text signature in the commit body. Example that signs both commits:

   ```
   pick 12345 commit message
   exec git commit --amend --no-edit -s
   pick 67890 commit message
   exec git commit --amend --no-edit -s
   ```

4. If you need to re-sign a bunch of previous commits at once, find the earliest commit missing the sign off line using `$ git log` and use that the HASH of the commit before it in this command:
   ```
	$ git rebase --exec 'git commit --amend --no-edit -n -s' -i HASH.
   ```
   This will sign off every commit from most recent to right before the HASH.

5. You will probably need to do a force push (`$ git push -f`) if you had previously pushed unsigned commits to remote.
