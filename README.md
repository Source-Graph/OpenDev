# OpenDev
https://opendev.org/

## (DarkStar✹)me: OpenDev's model is better!

>How is development different with OpenDev
>OpenDev doesn't use a pull request (or merge request) workflow, like those implemented by GitHub or Gitlab. Instead it follows Gerrit's iterative change proposal workflow, which results in a slightly different experience.
>
>...
>
>By contrast, contribution with Gerrit starts by cloning the original repository locally. You iterate on development of one or more local commits, and then use git push (or the git-review tool) to propose your commits as a series of changes to the Gerrit code review service. Each change in the series is reviewed, and if it's accepted (and passing tests) then it gets merged into the original repository. If more work is needed, you amend the same commits and push new versions of them for re-review.

>The difference is subtle, but significant. In the pull request model, you create a fork of the original repository, push changes to it, and ultimately propose to merge changes back. In the change proposal model, you prepare a change, and propose it. You do not create a complete fork and everyone contributes into the same original repository **with what are basically lightweight, ephemeral topic branches. It results in less fragmentation overall, and avoids confusion between the original repository and its numerous forks.**
