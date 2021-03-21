<!-- markdownlint-disable MD025 MD041 -->

[![Build](https://github.com/bnaard/pycmdlineapp-groundwork/workflows/Build/badge.svg?event=push)](https://github.com/bnaard/pycmdlineapp-groundwork/actions?query=event%3Apush+branch%3Amaster+workflow%3ABuild)
[![Docs](https://github.com/bnaard/pycmdlineapp-groundwork/workflows/Docs/badge.svg?event=push)](https://github.com/bnaard/pycmdlineapp-groundwork/actions?query=event%3Apush+branch%3Amaster+workflow%3ADocs)
[![license](https://img.shields.io/github/license/bnaard/pycmdlineapp-groundwork.svg)](https://github.com/bnaard/pycmdlineapp-groundwork/blob/master/LICENSE.md)
[![Coverage](https://codecov.io/gh/bnaard/pycmdlineapp-groundwork/branch/master/graph/badge.svg)](https://codecov.io/gh/bnaard/pycmdlineapp-groundwork)

# Welcome to pycmdlineapp_groundworks

pycmdlineapp_groundworks is an opinionated collection of libraries to jumpstart the development for mid-levele to complex python command-line applications.

The toolset solves the following challanges:

| Challenge           | Description                          | Solution       |
| :------------------ | :----------------------------------- | :------------- |
| Commandline parsing |                                      | Uses click     |
| Settings management | Schema-validated, documented and probably pre-processed settings from different sources (config files, environment variables, .env files, secret files), coordinated with click default values and input from command-line arguments  | pydantic  |
| Logging setup       | Update resource | ssss |
| Multi-progress bar  | Thread-safe colored progressbar with options for multiple bars, counters and clutter-free printing of log-/error-messages | ssss |
| Factory methods     | Delete resource | ssss |

[Documentation](https://bnaard.github.io/pycmdlineapp-groundwork/index.html)

Inspired by:

- [https://realpython.com/factory-method-python/](https://realpython.com/factory-method-python/)
