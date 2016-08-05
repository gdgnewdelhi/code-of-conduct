#Contributing to GDG New Delhi

We'd love for you to contribute to our source code and to make GDG New Delhi even better than it is
today! Here are the guidelines we'd like you to follow:

 - [Code of Conduct](#coc)
 - [Teams and Inactivity](#members)
 - [Question or Problem?](#question)
 - [Issues and Bugs](#issue)
 - [Feature Requests](#feature)
 - [Submission Guidelines](#submit)

## <a name="coc"></a> Code of Conduct
Help us keep GDG New Delhi open and inclusive. Please read and follow our [Code of Conduct][coc].

## <a name="question"></a> Got a Question or Problem?

If you have questions about GDG New Delhi, please direct these to the [Google+ Page][pluspage].

## <a name="issue"></a> Found an Issue?
If you find a bug in the source code or a mistake in the documentation, you can help us by
submitting an issue to our [GitHub Repository][github]. Even better you can submit a Pull Request
with a fix.

## <a name="feature"></a> Want a Feature?
You can request a new feature by submitting an issue to our [GitHub Repository][github].  If you
would like to implement a new feature then consider what kind of change it is:

* **Major Changes** that you wish to contribute to the project should be discussed first so that we can better coordinate our efforts, prevent
duplication of work, and help you to craft the change so that it is successfully accepted into the
project.
* **Small Changes** can be crafted and submitted to [GitHub Repository][github] as a Pull Request.

## <a name="projects"></a> Projects

Projects are either active, unmaintained or deprecated.

* "active" means that the project is under development and that releases are produced at least once a year. All projects that are not unmaintained or deprecated are active.
* "unmaintained" means that the project is no longer under development and that the last release can be used as stable version. The project's description on github has the prefix `[UNMAINTAINED]`.
* "deprecated" means that the project is no longer under development and that the last release should not be used any more. the project's description on github has the prefix `[DEPRECATED]`.

It is the responsibility of the maintainer to change the status of the project.

## <a name="submit"></a> Submission Guidelines

### Submitting an Issue
Before you submit your issue search the archive, maybe your question was already answered.

If your issue appears to be a bug, and hasn't been reported, open a new issue.
Help us to maximize the effort we can spend fixing issues and adding new
features, by not reporting duplicate issues.  Providing the following information will increase the
chances of your issue being dealt with quickly:

* **Overview of the issue** - if an error is being thrown a non-minified stack trace helps
* **Motivation for or Use Case** - explain why this is a bug for you
* **Browsers and Operating System** - is this a problem with all browsers or only IE8?
* **Reproduce the error** - provide a live example.
* **Related issues** - has a similar issue been reported before?
* **Suggest a Fix** - if you can't fix the bug yourself, perhaps you can point to what might be
  causing the problem (line of code or commit)

**If you get help, help others. Good karma rulez!**

### Submitting a Pull Request
Before you submit your pull request consider the following guidelines:

* Search GitHub for an open or closed Pull Request that relates to your submission. You don't want to duplicate effort.
* Make your changes in a new git branch

     ```shell
     git checkout -b my-fix-branch master
     ```

* Create your patch, **including appropriate test cases**.
* Commit your changes using a descriptive commit message.

     ```shell
     git commit -a
     ```
  Note: the optional commit `-a` command line option will automatically "add" and "rm" edited files.

* Push your branch to GitHub:

    ```shell
    git push origin my-fix-branch
    ```

* In GitHub, send a pull request.
* If we suggest changes then 
  * Make the required updates.
  * Rebase your branch and force push to your GitHub repository (this will update your Pull Request):

    ```shell
    git rebase master -i
    git push -f
    ```

That's it! Thank you for your contribution!

#### After your pull request is merged

After your pull request is merged, you can safely delete your branch and pull the changes
from the main (upstream) repository:

* Delete the remote branch on GitHub either through the GitHub web UI or your local shell as follows:

    ```shell
    git push origin --delete my-fix-branch
    ```

* Check out the master branch:

    ```shell
    git checkout master -f
    ```

* Delete the local branch:

    ```shell
    git branch -D my-fix-branch
    ```

* Update your master with the latest upstream version:

    ```shell
    git pull --ff upstream master
    ```

## <a name="members"></a> GDG New Delhi contributors
Everybody is invited to dive into the code, explore, learn, open issues, and send pull requests.

### Teams
Each project has a *team of contributors* that can merge pull requests. These team members should have a good understanding of the project to answer questions and review pull requests. Contributors are members of the corresponding GitHub project team.

One or two members are the *maintainers* of the project and publish releases. Maintainers are responsible for the _roadmap_, _milestones_, and the _state of the project_ in general. They _tag_ and _publish_ releases.

Maintainers are listed by name and GitHub handle in the readme of the project.

### Inactive contributors
Contributors who are inactive for more than a year will be contacted by the project maintainers and asked if they can become active again or retire. 
If the inactive contributor can't be reached the contributor is moved to the alumni team by one of the GDG New Delhi admin organizers

### Inactive maintainers
Maintainers who are inactive for more than six months will be contacted by one of the GDG New Delhi admin organizers and asked whether they can become active again or retire (see inactive contributors). If they retire and no other maintainers can be found the project is marked [DEPRECATED].


[coc]: https://github.com/gdgnewdelhi/code-of-conduct/blob/master/CONTRIBUTING.md
[github]: https://github.com/gdgnewdelhi
[pluspage]: https://plus.google.com/114576537688641864561
[js-style-guide]: http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml
