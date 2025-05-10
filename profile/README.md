<div align="center">

![AILERON Projects Logo](../logos/logo-light-aileron-projects.svg)

# :tada: Welcome to the AILERON Projects Community :tada:

</div>

> [!NOTE]
> **AILERON Projects — Go web framework for cloud-native enterprise systems.**

AILERON Projects leverages [Go](https://go.dev/).

![aileron-loves-go.svg](./aileron-loves-go.svg)

## Documentations

- [Website](https://aileron-projects.github.io/)

## Repositories

| Repository | Content |
| - | - |
| [aileron-projects.github.io](https://github.com/aileron-projects/aileron-projects.github.io) | Website resources. |
| [community](https://github.com/aileron-projects/community) | Governance and guidelines. |
| [.github](https://github.com/aileron-projects/.github) | Organization profiles. |
| [go](https://github.com/aileron-projects/go) | Go standard package extensions. |
| [aileron](https://github.com/aileron-projects/aileron) | Core library of the framework. |

**Repository overview.**

```mermaid
block-beta
  columns 4

  Documentation
  block:docs:3
    github["Org profile</br><a href="https://github.com/aileron-projects/.github">.github</a>"]
    githubio["Website</br><a href="https://github.com/aileron-projects/aileron-projects.github.io">aileron-projects.github.io</a>"]
    community["Governance/Guides</br><a href="https://github.com/aileron-projects/community">community</a>"]
  end

  Cores["Core Projects"]
  block:core:3
    go["Go std extension</br><a href="https://github.com/aileron-projects/go">go</a>"]
    aileron["Framework core</br><a href="https://github.com/aileron-projects/aileron">aileron</a>"]
    space
  end

  Libraries["Upper Libraries"]
  block:lib:3
    space:3
  end

  Examples
  block:example:3
    space:3
  end

style Documentation fill:transparent,stroke:none
style Cores fill:transparent,stroke:none
style Libraries fill:transparent,stroke:none
style Examples fill:transparent,stroke:none
```
