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

# Integrated Continuous Integration
>One key benefit of OpenDev is that it integrates powerful continuous integration features, made possible by the donation of compute resources from our generous infrastructure partners. Test jobs are run when changes are proposed and provide code reviewers with valuable information. Test jobs also run again at merge time, in case recently approved changes introduce an incompatibility, preventing code which doesn't pass tests from merging to the repository.
>
>Advanced Zuul features like speculative execution of tests allow the testing of sequenced changes in parallel, so development velocity is rarely limited by how thorough you want your tests to be. Changes in one Git repository can depend on proposed changes in another repository, allowing integration testing of features actively developed across multiple projects, removing artificial barriers between development teams.
>
>This advanced continuous integration system was developed to sustain the complexity and scale of OpenStack development, one of the three most actively developed open source projects in the world. OpenDev makes this system available to other projects, enabling open development at scale for everyone.
