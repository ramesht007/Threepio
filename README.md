![Threepio logo](/threepio.png)

![Coverage](https://img.shields.io/codecov/c/github/OpenMined/threepio)
![License](https://img.shields.io/github/license/OpenMined/threepio)
![OpenCollective](https://img.shields.io/opencollective/all/openmined)

# Threepio

Threepio makes it _dead simple_ to translate commands between machine learning frameworks such as **PyTorch, Tensorflow.js, and Tensorflow Python**.
It acts as a core component in [PySyft](https://github.com/OpenMined/PySyft) and [syft.js](https://github.com/OpenMined/syft.js).
Some of the life changing features this library provides are:

 - :robot: Automatic bi-directional translation between same named commands `add`, `abs`, etc.
 - :brain: Smart argument mapping between automaticaly translated commands
 - :repeat: Word level translation between libraries
 - :wrench: Custom command translation
 - :herb: One to many command translation
 - :zap: Translation of tensor methods _(in progress)_
 - :mag: Support for fuzzy match in automatic command translation _(in progress)_
 - :card_index_dividers: Support for framework versioning in automatic translation _(in progress)_
 - :mage_man: Support for automatic argument type casting (tensorflow tensor -> pytorch tensor) _(in progress)_

Threepio is made up of two main components:
- :spider: [Documentation Crawler](/docs-crawler) - This generates the majority of our automatic translations for Threepio
- :snake: [Python translation library](/pythreepio) - This is the python library for using threepio

~And has clients in both Python and Javascript!~
And has a client available in Python!

## Installation

Depending on your language, installation will differ.

### Python
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install threepio.

```bash
pip install 3p0
```

#### Usage

Please check out our [usage document](/pythreepio/README.md) for further guidelines.

### Javascript
** Threepio.js has been deprecated. For existing javascript code, please refer to commit [0a538a3f](https://github.com/OpenMined/Threepio/commit/0a538a3f1ed70b39be541766211f6b84e2136fc3) **

#### Usage

Please check out our [usage document](/js/README.md) for further guidelines.

## Support

For support in using this library, please join the **#lib_threepio** Slack channel. If you'd like to follow along with any code changes to the library, please join the **#code_threepio** Slack channel. [Click here to join our Slack community!](https://slack.openmined.org)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Contributors

Please make sure to fill this section in with **all former and current** contributors to the project. [Documentation on how to do this is located here.](https://github.com/all-contributors/all-contributors)

## License
[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)
