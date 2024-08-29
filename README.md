# Description

CPPify is a header-only C++ API for interacting with the Spotify Web API. This header serves as a starting point for your needs. I originally created it for a [different project](https://github.com/KielanT/PicoMusicController), but I believe it could be useful to others on its own.

I have included a class called SpotifyCalls, which provides examples of how to use CPPify to interact with the Spotify Web API.

I have provided a class called AuthServer for handling authentication. This project uses the Authorization Code Flow for authentication. Please refer to Spotify's Authorization Flows documentation to choose the appropriate method for your specific needs, which can be found here: Spotify Authorization.

### Dependencies

All required dependencies are included in the external folder:

- Curl
- Crow (for the AuthServer)
- nlohmann/json
If you only wish to use the CPPify header, Curl is the only dependency required.

