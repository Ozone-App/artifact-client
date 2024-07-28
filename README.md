# Ozone Artifact API library

The Ozone Python library provides convenient access to the Artifact REST API from any Python 3.8+ application.

## Documentation

The REST API documentation can be found on [somewhere](https://ozone.pro).

## Installation

> [!IMPORTANT]
> The SDK was rewritten in v1, which was released November 6th 2023. See the [v1 migration guide](https://github.com/openai/openai-python/discussions/742), which includes scripts to automatically update your code.

```sh
# install from PyPI
pip install openai
```

## Usage

The full API of this library can be found in [api.md](api.md).

```python
import os
from artifact import Artifact

client = Artifact(api_key=os.environ.get("ARTIFACT_API_KEY"))

some_one = client.get_something()
```

