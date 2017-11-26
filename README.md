# b4m36bsy-native-client

Presentation on Google Native Client for B4M36BSY class taught at FEE CTU.

Sources:
- [Native Client homepage](https://developer.chrome.com/native-client)
- [Chromium Security Architecture](http://seclab.stanford.edu/websec/chromium/chromium-security-architecture.pdf)
- [Native Client: A Sandbox for Portable, Untrusted x86 Native Code](http://ieeexplore.ieee.org/abstract/document/5207638/)

Instructions for running demo:
1. Download [SDK](https://developer.chrome.com/native-client/sdk/download) for Native Client
2. Install the stable bundle. Tutorial is [here](https://developer.chrome.com/native-client/sdk/download#installing-the-stable-bundle)
3. Update bundles. Tutorial is [here](https://developer.chrome.com/native-client/sdk/download#updating-bundles)
4. Copy the content of the demo folder to get_started folder in SDK.
5. Go to nacl_sdk/pepper_$(VERSION)/getting_started
6. Start server using the command: make serve
7. Start google chrome and go to this page: http://localhost:5103
8. If part1 or part2 does not work, you have to compile the content of the non-functional folder by using "make clean" and then "make" 