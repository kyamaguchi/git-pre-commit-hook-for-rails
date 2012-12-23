## git pre-commit hook for rails development

Ensures that changes to the project may only be committed if there is no logging or debugging methods included.
It checks only + lines.

Current keywords:

    debugger
    logger
    puts
    save_and_open_page
    console.log

## Getting Started

    $ cd rails_project
    $ wget https://github.com/kyamaguchi/git-pre-commit-hook-for-rails
    $ mv pre-commit .git/hooks/
    $ chmod +x .git/hooks/pre-commit
