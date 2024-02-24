# <img src="https://www.gstatic.com/lamda/images/favicon_v1_150160cddff7f294ce30.svg" width="35px" alt="Gemini Icon" /> Gemini-API



A Python wrapper, [python-gemini-api](https://pypi.org/project/python-gemini-api/), interacts with [Google Gemini](https://gemini.google.com) via reverse engineering.

<br>

## What is [Gemini](https://deepmind.google/technologies/gemini/#introduction)?
Gemini is a family of generative AI models developed by Google DeepMind that is designed for multimodal use cases. The Gemini API gives you access to the Gemini Pro and Gemini Pro Vision models. In February 2024, Google's **Bard** service was changed to **Gemini**.

## Installation
```
pip install python-gemini-api
```
```
pip install git+https://github.com/dsdanielpark/Gemini-API.git
```

## Authentication

> **Warning** *DO NOT* expose your cookies. 

- Depending on the region and Google account status, *multiple cookies may be required*, including `__Secure-1PSIDTS`, `__Secure-1PSIDCC`, `__Secure-1PSID`, `NID`, *or more*.
- You must appropriately set the `cookies_dict` parameter to `Gemini` class.
- Cookie values can be changed frequently, thus it is recommended to automatically update them through the [browser_cookie3](https://github.com/borisbabic/browser_cookie3) package.

<br>

## Usage



<br>

## [FAQ](https://github.com/dsdanielpark/Gemini-API/blob/main/documents/README_FAQ.md)
You can find most help on the [FAQ](https://github.com/dsdanielpark/Gemini-API/blob/main/documents/README_FAQ.md) and [Issue](https://github.com/dsdanielpark/Gemini-API/issues) pages. Alternatively, utilize the official Gemini API at [Google AI Studio](https://ai.google.dev/tutorials/ai-studio_quickstart).

            
## [Issues](https://github.com/dsdanielpark/Gemini-API/issues)
Sincerely grateful for any reports on new features or bugs. Your valuable feedback on the code is highly appreciated. Frequent errors may occur due to changes in Google's service API interface. Both [Issue reports](https://github.com/dsdanielpark/Gemini-API/issues) and [Pull requests](https://github.com/dsdanielpark/Gemini-API/pulls) contributing to improvements are always welcome. We strive to maintain an active and courteous open community.


## Contributors
We would like to express my sincere gratitude to all the contributors.

## Contacts
- **Core Maintainer:** [Daniel Park](https://github.com/dsdanielpark)
- **E-mail:** parkminwoo1991@gmail.com

## License
[MIT](https://opensource.org/license/mit/) license, 2024, Minwoo(Daniel) Park. We hereby strongly disclaim any explicit or implicit legal liability related to our works. Users are required to use this package responsibly and at their own risk.



## References
[1] Github [acheong08/Bard](https://github.com/acheong08/Bard) <br>
[2] Github [GoogleCloudPlatform/generative-ai](https://github.com/GoogleCloudPlatform/generative-ai) <br>
[3] Github [HanaokaYuzu/Gemini-API](https://github.com/HanaokaYuzu/Gemini-API) <br>
[4] [Google AI Studio](https://ai.google.dev/tutorials/ai-studio_quickstart) <br>



