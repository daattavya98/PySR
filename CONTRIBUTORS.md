# Welcome to PySR's contributing guide <!-- Forked from GitHub's awesome template contributing guide -->

Thank you for investing your time in contributing to our project! Any contribution you make will be reflected on the [contributors list](#contributors) :sparkles:.

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.

## New contributor guide

To get an overview of the project, read PySR's [README](README.md). The [PySR docs](https://astroautomata.com/PySR/) give additional information.
Here are some resources to help you get started with open source contributions in general:

- [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)
- [Collaborating with pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests)

### Issues

#### Create a new issue

If you spot a problem with PySR, [search if an issue already exists](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments). If a related issue doesn't exist, you can open a new issue using a relevant [issue form](https://github.com/MilesCranmer/PySR/issues/new/choose).

#### Solve an issue

Scan through our [existing issues](https://github.com/MilesCranmer/PySR/issues) to find one that interests you (feel free to work on any!). You can narrow down the search using `labels` as filters. See [Labels](/contributing/how-to-use-labels.md) for more information. If you find an issue to work on, you are welcome to open a PR with a fix.

### Make Changes

#### Make changes locally

1. Fork the repository.
- Using GitHub Desktop:
  - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
  - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

- Using the command line:
  - [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.

2. Create a working branch and start with your changes!

3. (Optional) If you would like to make changes to PySR itself, skip to step 4. However, if you are interested in making changes to the _symbolic regression code_ itself,
check out the [guide](https://astroautomata.com/PySR/backend/) on modifying a custom SymbolicRegression.jl library.
In this case, you might instead be interested in making suggestions to the [SymbolicRegression.jl](http://github.com/MilesCranmer/SymbolicRegression.jl) library.

4. You can install your local version of PySR with `python setup.py install`, and run tests with `python -m pysr.test main`.

### Commit your update

Once you are happy with your changes, run `black .` to apply [Black](https://black.readthedocs.io/en/stable/) formatting to your local
version. Commit the changes once you are ready.

### Pull Request

When you're finished with the changes, create a pull request, also known as a PR.
- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge.
Once you submit your PR, a PySR team member will review your proposal. We may ask questions or request additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

### Your PR is merged!

Congratulations :tada::tada: The PySR team thanks you :sparkles:.

Once your PR is merged, your contributions will be publicly visible.

Thanks for being part of the PySR community!

<div align="center">

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="12.5%"><a href="https://www.linkedin.com/in/markkittisopikul/"><img src="https://avatars.githubusercontent.com/u/8062771?v=4?s=50" width="50px;" alt="Mark Kittisopikul"/><br /><sub><b>Mark Kittisopikul</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=mkitti" title="Code">💻</a> <a href="#ideas-mkitti" title="Ideas, planning, and feedback.">💡</a> <a href="#infra-mkitti" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#platform-mkitti" title="Packaging/porting to new platform">📦</a> <a href="#promotion-mkitti" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Amkitti" title="Reviewed Pull Requests">👀</a> <a href="#tool-mkitti" title="Tools">🔧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=mkitti" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/tttc3"><img src="https://avatars.githubusercontent.com/u/97948946?v=4?s=50" width="50px;" alt="T Coxon"/><br /><sub><b>T Coxon</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Atttc3" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=tttc3" title="Code">💻</a> <a href="#plugin-tttc3" title="Plugin/utility libraries">🔌</a> <a href="#ideas-tttc3" title="Ideas, planning, and feedback.">💡</a> <a href="#infra-tttc3" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#maintenance-tttc3" title="Maintenance">🚧</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Atttc3" title="Reviewed Pull Requests">👀</a> <a href="#tool-tttc3" title="Tools">🔧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=tttc3" title="Tests">⚠️</a> <a href="#userTesting-tttc3" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/DhananjayAshok"><img src="https://avatars.githubusercontent.com/u/46792537?v=4?s=50" width="50px;" alt="Dhananjay Ashok"/><br /><sub><b>Dhananjay Ashok</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=DhananjayAshok" title="Code">💻</a> <a href="#example-DhananjayAshok" title="Examples.">🌍</a> <a href="#ideas-DhananjayAshok" title="Ideas, planning, and feedback.">💡</a> <a href="#maintenance-DhananjayAshok" title="Maintenance">🚧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=DhananjayAshok" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://gitlab.com/johanbluecreek"><img src="https://avatars.githubusercontent.com/u/852554?v=4?s=50" width="50px;" alt="Johan Blåbäck"/><br /><sub><b>Johan Blåbäck</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Ajohanbluecreek" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=johanbluecreek" title="Code">💻</a> <a href="#ideas-johanbluecreek" title="Ideas, planning, and feedback.">💡</a> <a href="#maintenance-johanbluecreek" title="Maintenance">🚧</a> <a href="#promotion-johanbluecreek" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Ajohanbluecreek" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=johanbluecreek" title="Tests">⚠️</a> <a href="#userTesting-johanbluecreek" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://mathopt.de/people/martensen/index.php"><img src="https://avatars.githubusercontent.com/u/20998300?v=4?s=50" width="50px;" alt="JuliusMartensen"/><br /><sub><b>JuliusMartensen</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3AAlCap23" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=AlCap23" title="Code">💻</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=AlCap23" title="Documentation">📖</a> <a href="#plugin-AlCap23" title="Plugin/utility libraries">🔌</a> <a href="#ideas-AlCap23" title="Ideas, planning, and feedback.">💡</a> <a href="#infra-AlCap23" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#maintenance-AlCap23" title="Maintenance">🚧</a> <a href="#platform-AlCap23" title="Packaging/porting to new platform">📦</a> <a href="#promotion-AlCap23" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3AAlCap23" title="Reviewed Pull Requests">👀</a> <a href="#tool-AlCap23" title="Tools">🔧</a> <a href="#userTesting-AlCap23" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/ngam"><img src="https://avatars.githubusercontent.com/u/67342040?v=4?s=50" width="50px;" alt="ngam"/><br /><sub><b>ngam</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=ngam" title="Code">💻</a> <a href="#infra-ngam" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#platform-ngam" title="Packaging/porting to new platform">📦</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Angam" title="Reviewed Pull Requests">👀</a> <a href="#tool-ngam" title="Tools">🔧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=ngam" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/kazewong"><img src="https://avatars.githubusercontent.com/u/8803931?v=4?s=50" width="50px;" alt="Kaze Wong"/><br /><sub><b>Kaze Wong</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Akazewong" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=kazewong" title="Code">💻</a> <a href="#ideas-kazewong" title="Ideas, planning, and feedback.">💡</a> <a href="#infra-kazewong" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#maintenance-kazewong" title="Maintenance">🚧</a> <a href="#promotion-kazewong" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Akazewong" title="Reviewed Pull Requests">👀</a> <a href="#research-kazewong" title="Research">🔬</a> <a href="#userTesting-kazewong" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/ChrisRackauckas"><img src="https://avatars.githubusercontent.com/u/1814174?v=4?s=50" width="50px;" alt="Christopher Rackauckas"/><br /><sub><b>Christopher Rackauckas</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3AChrisRackauckas" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=ChrisRackauckas" title="Code">💻</a> <a href="#plugin-ChrisRackauckas" title="Plugin/utility libraries">🔌</a> <a href="#ideas-ChrisRackauckas" title="Ideas, planning, and feedback.">💡</a> <a href="#infra-ChrisRackauckas" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#promotion-ChrisRackauckas" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3AChrisRackauckas" title="Reviewed Pull Requests">👀</a> <a href="#research-ChrisRackauckas" title="Research">🔬</a> <a href="#tool-ChrisRackauckas" title="Tools">🔧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=ChrisRackauckas" title="Tests">⚠️</a> <a href="#userTesting-ChrisRackauckas" title="User Testing">📓</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="12.5%"><a href="https://kidger.site/"><img src="https://avatars.githubusercontent.com/u/33688385?v=4?s=50" width="50px;" alt="Patrick Kidger"/><br /><sub><b>Patrick Kidger</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Apatrick-kidger" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=patrick-kidger" title="Code">💻</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=patrick-kidger" title="Documentation">📖</a> <a href="#plugin-patrick-kidger" title="Plugin/utility libraries">🔌</a> <a href="#ideas-patrick-kidger" title="Ideas, planning, and feedback.">💡</a> <a href="#maintenance-patrick-kidger" title="Maintenance">🚧</a> <a href="#promotion-patrick-kidger" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Apatrick-kidger" title="Reviewed Pull Requests">👀</a> <a href="#research-patrick-kidger" title="Research">🔬</a> <a href="#tool-patrick-kidger" title="Tools">🔧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=patrick-kidger" title="Tests">⚠️</a> <a href="#userTesting-patrick-kidger" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/w2ll2am"><img src="https://avatars.githubusercontent.com/u/16038228?v=4?s=50" width="50px;" alt="William Booth-Clibborn"/><br /><sub><b>William Booth-Clibborn</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=w2ll2am" title="Code">💻</a> <a href="#example-w2ll2am" title="Examples.">🌍</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=w2ll2am" title="Documentation">📖</a> <a href="#userTesting-w2ll2am" title="User Testing">📓</a> <a href="#maintenance-w2ll2am" title="Maintenance">🚧</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Aw2ll2am" title="Reviewed Pull Requests">👀</a> <a href="#tool-w2ll2am" title="Tools">🔧</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=w2ll2am" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://pablo-lemos.github.io/"><img src="https://avatars.githubusercontent.com/u/38078898?v=4?s=50" width="50px;" alt="Pablo Lemos"/><br /><sub><b>Pablo Lemos</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3APablo-Lemos" title="Bug reports">🐛</a> <a href="#ideas-Pablo-Lemos" title="Ideas, planning, and feedback.">💡</a> <a href="#promotion-Pablo-Lemos" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3APablo-Lemos" title="Reviewed Pull Requests">👀</a> <a href="#research-Pablo-Lemos" title="Research">🔬</a> <a href="#userTesting-Pablo-Lemos" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/Moelf"><img src="https://avatars.githubusercontent.com/u/5306213?v=4?s=50" width="50px;" alt="Jerry Ling"/><br /><sub><b>Jerry Ling</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3AMoelf" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=Moelf" title="Code">💻</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=Moelf" title="Documentation">📖</a> <a href="#example-Moelf" title="Examples.">🌍</a> <a href="#ideas-Moelf" title="Ideas, planning, and feedback.">💡</a> <a href="#promotion-Moelf" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3AMoelf" title="Reviewed Pull Requests">👀</a> <a href="#userTesting-Moelf" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/CharFox1"><img src="https://avatars.githubusercontent.com/u/35052672?v=4?s=50" width="50px;" alt="Charles Fox"/><br /><sub><b>Charles Fox</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3ACharFox1" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=CharFox1" title="Code">💻</a> <a href="#ideas-CharFox1" title="Ideas, planning, and feedback.">💡</a> <a href="#maintenance-CharFox1" title="Maintenance">🚧</a> <a href="#promotion-CharFox1" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3ACharFox1" title="Reviewed Pull Requests">👀</a> <a href="#research-CharFox1" title="Research">🔬</a> <a href="#userTesting-CharFox1" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/johannbrehmer"><img src="https://avatars.githubusercontent.com/u/17068560?v=4?s=50" width="50px;" alt="Johann Brehmer"/><br /><sub><b>Johann Brehmer</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=johannbrehmer" title="Code">💻</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=johannbrehmer" title="Documentation">📖</a> <a href="#ideas-johannbrehmer" title="Ideas, planning, and feedback.">💡</a> <a href="#promotion-johannbrehmer" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Ajohannbrehmer" title="Reviewed Pull Requests">👀</a> <a href="#research-johannbrehmer" title="Research">🔬</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=johannbrehmer" title="Tests">⚠️</a> <a href="#userTesting-johannbrehmer" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="http://www.cosmicmar.com/"><img src="https://avatars.githubusercontent.com/u/1510968?v=4?s=50" width="50px;" alt="Marius Millea"/><br /><sub><b>Marius Millea</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=marius311" title="Code">💻</a> <a href="#ideas-marius311" title="Ideas, planning, and feedback.">💡</a> <a href="#promotion-marius311" title="Promotion">📣</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Amarius311" title="Reviewed Pull Requests">👀</a> <a href="#userTesting-marius311" title="User Testing">📓</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://gitlab.com/cobac"><img src="https://avatars.githubusercontent.com/u/27872944?v=4?s=50" width="50px;" alt="Coba"/><br /><sub><b>Coba</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Acobac" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=cobac" title="Code">💻</a> <a href="#ideas-cobac" title="Ideas, planning, and feedback.">💡</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Acobac" title="Reviewed Pull Requests">👀</a> <a href="#userTesting-cobac" title="User Testing">📓</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/pitmonticone"><img src="https://avatars.githubusercontent.com/u/38562595?v=4?s=50" width="50px;" alt="Pietro Monticone"/><br /><sub><b>Pietro Monticone</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Apitmonticone" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=pitmonticone" title="Documentation">📖</a> <a href="#ideas-pitmonticone" title="Ideas, planning, and feedback.">💡</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/sheevy"><img src="https://avatars.githubusercontent.com/u/1525683?v=4?s=50" width="50px;" alt="Mateusz Kubica"/><br /><sub><b>Mateusz Kubica</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=sheevy" title="Documentation">📖</a> <a href="#ideas-sheevy" title="Ideas, planning, and feedback.">💡</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://jaywadekar.github.io/"><img src="https://avatars.githubusercontent.com/u/5493388?v=4?s=50" width="50px;" alt="Jay Wadekar"/><br /><sub><b>Jay Wadekar</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3AJayWadekar" title="Bug reports">🐛</a> <a href="#ideas-JayWadekar" title="Ideas, planning, and feedback.">💡</a> <a href="#promotion-JayWadekar" title="Promotion">📣</a> <a href="#research-JayWadekar" title="Research">🔬</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/Jgmedina95"><img src="https://avatars.githubusercontent.com/u/97254349?v=4?s=50" width="50px;" alt="Jgmedina95"/><br /><sub><b>Jgmedina95</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3AJgmedina95" title="Bug reports">🐛</a> <a href="#ideas-Jgmedina95" title="Ideas, planning, and feedback.">💡</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3AJgmedina95" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/mcabbott"><img src="https://avatars.githubusercontent.com/u/32575566?v=4?s=50" width="50px;" alt="Michael Abbott"/><br /><sub><b>Michael Abbott</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=mcabbott" title="Code">💻</a> <a href="#ideas-mcabbott" title="Ideas, planning, and feedback.">💡</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Amcabbott" title="Reviewed Pull Requests">👀</a> <a href="#tool-mcabbott" title="Tools">🔧</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/oscardssmith"><img src="https://avatars.githubusercontent.com/u/11729272?v=4?s=50" width="50px;" alt="Oscar Smith"/><br /><sub><b>Oscar Smith</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=oscardssmith" title="Code">💻</a> <a href="#ideas-oscardssmith" title="Ideas, planning, and feedback.">💡</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/henriquebecker91"><img src="https://avatars.githubusercontent.com/u/14113435?v=4?s=50" width="50px;" alt="Henrique Becker"/><br /><sub><b>Henrique Becker</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/commits?author=henriquebecker91" title="Code">💻</a> <a href="#ideas-henriquebecker91" title="Ideas, planning, and feedback.">💡</a> <a href="https://github.com/MilesCranmer/PySR/pulls?q=is%3Apr+reviewed-by%3Ahenriquebecker91" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/qwertyjl"><img src="https://avatars.githubusercontent.com/u/110912592?v=4?s=50" width="50px;" alt="qwertyjl"/><br /><sub><b>qwertyjl</b></sub></a><br /><a href="https://github.com/MilesCranmer/PySR/issues?q=author%3Aqwertyjl" title="Bug reports">🐛</a> <a href="https://github.com/MilesCranmer/PySR/commits?author=qwertyjl" title="Documentation">📖</a> <a href="#ideas-qwertyjl" title="Ideas, planning, and feedback.">💡</a> <a href="#userTesting-qwertyjl" title="User Testing">📓</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="12.5%"><a href="https://huijzer.xyz/"><img src="https://avatars.githubusercontent.com/u/20724914?v=4?s=50" width="50px;" alt="Rik Huijzer"/><br /><sub><b>Rik Huijzer</b></sub></a><br /><a href="#ideas-rikhuijzer" title="Ideas, planning, and feedback.">💡</a> <a href="#infra-rikhuijzer" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://github.com/GCaptainNemo"><img src="https://avatars.githubusercontent.com/u/43086239?v=4?s=50" width="50px;" alt="Hongyu Wang"/><br /><sub><b>Hongyu Wang</b></sub></a><br /><a href="#ideas-GCaptainNemo" title="Ideas, planning, and feedback.">💡</a> <a href="#promotion-GCaptainNemo" title="Promotion">📣</a> <a href="#research-GCaptainNemo" title="Research">🔬</a></td>
      <td align="center" valign="top" width="12.5%"><a href="https://sauravmaheshkar.github.io/"><img src="https://avatars.githubusercontent.com/u/61241031?v=4?s=50" width="50px;" alt="Saurav Maheshkar"/><br /><sub><b>Saurav Maheshkar</b></sub></a><br /><a href="#tool-SauravMaheshkar" title="Tools">🔧</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
</div>