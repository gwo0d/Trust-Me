# Introduction
This project is in early development, and is still establishing its technical structure. Our main goal at present is to set out a well-founded theoretical framework, before we write any substantive code. Please see the Issues tab for a list of the current questions we'd like to answer. Contributions at the moment are *usually* limited to one of the following, unless good justification can be provided otherwise:
- Answers to one of our questions
- Proposals for new questions

Please read this file **in full** before contributing, as it contains important information on how to do so.

To make a contribution, please use the following process:
1. Fork this project
2. Make a new branch named according to the question you're answering
3. Write your contribution
4. Submit a pull request to the parent repository, ensuring you provide a good, detailed description of the work you've done


# Non-Code Contributions
All non-code contributions **must** be formatted properly, in a MarkDown (`.md`) file, and conforming with the [template](#non-code-contribution-template) below. They should use good academic English where possible, but please do not let this dissuade you from contributing if you don't feel confident doing so. As long as your contribution can be understood, one of the maintainers can help you rework the language if required.

Ensure the filename you choose is meaningful, but not too verbose. Filenames should be lowercase, and underscore-seperated. Files should be placed in the appropriate directory, as set out below in [Project Structure](#project-structure).

For example, a contribution proposing to add the word "spam" to every page in the user interface would be structured as follows:
- Filename: `add_spam_to_every_page.md`
- Directory: `/standard/user`

## Non-Code Contribution Template
```markdown
# {Title}
{Short Description}

# Abstract
{~250 words summarising everything you've done}

# Rationale
{Explain in as much detail as necessary why you've done this}

# Contribution
{Describe what you've contributed, and provide reasoning for your decisions}

# Future Work
{Optionally describe what still needs to be done, or if any further contributions are needed to support this one}
```


# Code Contributions
**At the moment, you are strongly encouraged to make non-code contributions. This project is not ready for implementation yet, so code should not be contributed unless you have strong rationale for doing so.**

This project's programming language is [Python](https://www.python.org/downloads/) (>=3.13).

Please adhere to the following principles when writing code:
- Ensure contributions are in the correct directory location, as set out below in [Project Structure](#project-structure)
- Use type hints
- Include helpful comments
- Conform to good programming practices, and practice good code hygiene
- Track your changes using git, and ensuring your commit messages are meaningful


# Project Structure
- `/standard`: all information relating to the Trust-Me's technical design
    - `/standard/user`: all standard materials relating to user-facing features
    - `/standard/network`: all standard materials relating to the *Peer-to-Peer* (P2P) decentrilised blockchain
- ~~`/reference`: a reference implementation of the Trust-Me standard~~
    - ~~`/reference/user`: code for user-facing features~~
    - ~~`/reference/network`: code for the P2P decentrilised blockchain~~
- ~~`/docs`: documentation for the Trust-Me reference implementation~~
    - ~~`/docs/user`: documentation for user-facing features~~
    - ~~`/docs/network`: documentation for the P2P decentrilised blockchain~~