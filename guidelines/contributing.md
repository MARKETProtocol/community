# Contributing

By participating in MARKET Protocol development, you
agree to abide by the [code of conduct].

[code of conduct]: https://github.com/MARKETProtocol/Meta/blob/master/CODE_OF_CONDUCT.md

Fork, then clone the repo:

    git clone git@github.com:your-username/MARKETProtocol/(sub_project).git

Set up your machine:

    make install_truffle
    make install_deps
    
Make sure the tests pass:

    make start_console
    make start_bridge
    %truffle test

Make your change. Add tests for your change. Verify that the tests pass.

Push to your fork and [submit a pull request][pr].

[pr]: https://github.com/MARKETProtocol/MARKETProtocol/compare/

At this point you're waiting on us. We like to at least comment on pull requests
within three business days (and, typically, one business day). We may suggest
some changes or improvements or alternatives.

Some things that will increase the chance that your pull request is accepted:

* Write tests.
* Follow our [coding conventions][coding].
* Write a [good commit message][commit].

[coding]: https://github.com/MARKETProtocol/Meta/blob/master/coding_conventions.md
[commit]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

These guidelines were originally adapted from [Thoughtbot][fbr]
[fbr]: https://github.com/thoughtbot/factory_bot_rails/blob/master/CONTRIBUTING.md
