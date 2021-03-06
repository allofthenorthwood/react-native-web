# Contributing to this project

The issue tracker is the preferred channel for [bug reports](#bugs),
[features requests](#features), and [submitting pull requests](#pull-requests).

<a name="bugs"></a>
## Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful - thank you! You can compare the
behaviour against that expected with React Native by using the [React Native
Playground](https://rnplay.org/)

Guidelines for bug reports:

1. **Use the GitHub issue search** &mdash; check if the issue has already been
   reported or fixed in `master`.

2. **Isolate the problem** &mdash; create a [reduced test
   case](http://css-tricks.com/reduced-test-cases/) using this
   [codepen](https://codepen.io/necolas/pen/PZzwBR?editors=001).

A good bug report contains as much detail as possible. What is your
environment? What steps will reproduce the issue? What browser(s) and OS
experience the problem? What would you expect to be the outcome? All these
details really help!

Example:

> Short and descriptive example bug report title
>
> A summary of the issue and the browser/OS environment in which it occurs. If
> suitable, include the steps required to reproduce the bug.
>
> 1. This is the first step
> 2. This is the second step
> 3. Further steps, etc.
>
> `<url>` - a link to the reduced test case
>
> Any other information you want to share that is relevant to the issue being
> reported. This might include the lines of code that you have identified as
> causing the bug, and potential solutions (and your opinions on their
> merits).


<a name="features"></a>
## Feature requests

Feature requests are welcome. But take a moment to find out whether your idea
fits with the scope and aims of the project (i.e., is this for parity with
React Native? does it make sense on the Web?). Please provide as much detail
and context as you think is necessary to make your case.


<a name="pull-requests"></a>
## Pull requests

Good pull requests - patches, improvements, new features - are a fantastic
help. Please keep them focused in scope and avoid containing unrelated commits.

**Please ask first** before embarking on any significant pull request (e.g.
implementing new features or components, refactoring code), otherwise you risk
spending a lot of time working on something that the project's developers might
not want to merge into the project.

Development commands:

* `npm run build` – build the library
* `npm run examples` – start the dev server and develop against live examples
* `npm run lint` – run the linter
* `npm run test:watch` – run and watch the unit tests
* `npm test` – run the linter and unit tests

Please follow this process for submitting a patch:

1. [Fork](http://help.github.com/fork-a-repo/) the project, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/react-native-web
   # Navigate to the newly cloned directory
   cd react-native-web
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/necolas/react-native-web
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout master
   git pull upstream master
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/interactive-rebase)
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream master
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.

**IMPORTANT**: By submitting a patch, you agree to allow the project owner to
license your work under the same license as that used by the project.
