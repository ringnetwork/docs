# Contributing

Find an area you can help with and do it. Open source is about collaboration and open participation. Try to make your code look like what already exists and submit a pull request.

The [list of issues](https://github.com/ringnetwork/rng-core/issues) is a good place to start, especially the ones tagged as "help wanted" (but don't let that stop you from looking at others). If you're looking for additional ideas, the code includes `TODO` comments for minor to major improvements. Use _Search in files_ in your code editor, or `grep "TODO" -r --exclude-dir=target --exclude-dir=.git .`.

Additional tests are rewarded with an immense amount of positive karma.

More documentation or updates/fixes to existing documentation are also very welcome. 

# PR Guidelines

We generally prefer you to PR your work earlier rather than later. This ensures everyone else has a better idea of what's being worked on, and can help reduce wasted effort. If work on your PR has just begun, please feel free to create the PR with [WIP] (work in progress) in the PR title, and let us know when it's ready for review in the comments.

Since mainnet has been released, the bar for having PRs accepted has been raised. Before submitting your PR for approval, please be ensure it:
* Includes a proper description of what problems the PR addresses, as well as a detailed explanation as to what it changes
* Explains whether/how the change is consensus breaking or breaks existing client functionality
* Contains unit tests exercising new/changed functionality
* Fully considers the potential impact of the change on other parts of the system
* Describes how you've tested the change (e.g. against Floonet, etc)
* Updates any documentation that's affected by the PR

If submitting a PR consisting of documentation changes only, please try to ensure that the change is significantly more substantial than one or two lines. For example, working through an install document and making changes and updates throughout as you find issues is worth a PR. For typos and other small changes, either contact one of the developers, or if you think it's a significant enough error to cause problems for other users, please feel free to open an issue.

The development team will be happy to help and guide you with any of these points and work with you getting your PR submitted for approval. Create a PR with [WIP] in the title and ask for specific assistance within the issue, or contact the dev team on any of the channels below.

# Find Us

When you are starting to contribute to Ring Network, we really would appreciate if you come by the gitter chat channels.

In case of problems with trying out Ring Network, before starting to contribute, there's the [Support chat](https://gitter.im/rng-core/support). Write there about what you've done, what you want to do, and maybe paste logs through a text paste webservice.

* Please [join the Ring Network Lobby](https://gitter.im/rng-core/Lobby) to get a feeling for the community.
* And [see the developers chat](https://gitter.im/rng-core/dev) if you have questions about source code files.
  If you explain what you're looking at and what you want to do, we'll try to help you along the way.
* Also see `docs/*.md` and the folder structure explanations, and [the wiki](https://github.com/ringnetwork/docs/wiki).
* Further information and discussions are in news channels like the [@ringnetwork](https://twitter.com/ringnetwork).

# Pull-Request Title Prefix

**Note**: *[draft part! to be reviewed and discussed]*

Please consider putting one of the following prefixes in the title of your pull-request:
- **feat**:     A new feature
- **fix**:      A bug fix
- **docs**:     Documentation only changes
- **style**:    Formatting, missing semi-colons, white-space, etc
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**:     A code change that improves performance
- **test**:     Adding missing tests
- **chore**:    Maintain. Changes to the build process or auxiliary tools/libraries/documentation

For example: `fix: a panick on xxx when client exiting`. Please don't worry if you can't find a suitable prefix, this's just optional, not mandatory.

## Thanks for any contribution

Even one word correction are welcome! Our objective is to encourage you to get interested in Ring Network and contribute in any way possible. Thanks for any help!
