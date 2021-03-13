# RoCaptcha Changelog

All notable changes to this project will be documented in this file.

## Version 0.1.1 Alpha

- Temporarily disabled Data Caching (it was causing a heap of bugs that were annoying, will be fixed)
- Restructured the color matching captcha so it doesnt look ugly lol
- Changed the Key ID to prevent leaking (all users should have it in their dms if purchased)

In addition, to create a wider public perspective on the data caching, we only cache data such as;
- Player Usernames, User Identification Codes,
- Captcha Results, such as if the user failed or succeeded,
- Game Data such as game id, etc,
- Version Data

and only send it through a private portal. It is not visible to the public or staff, only the owner(s)
