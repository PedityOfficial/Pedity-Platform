List of Addtion/Changes/Updates/Issue Fixes on Pedity Platform

Version 0.1.1 - 3rd December 2018
- Added Stellar and IPFS information on Footer
- Update of Login page with warning messages
- Goal button not working on profile pages

Version 0.1.2 - 13th December 2018
- Alignment of "Know more" and "Try Now" buttons on Pedity.com homepage - DONE
- Alpha page not responsive - FIXED
- Thumbnail coming out of frame - FIXED
- TL;DR need to move to bottom to a button - DONE
- The Geek Stats also should become a button - DONE
- Disqus same comments on each page - FIXED
- Edit profile button on all profile causes confusion - FIXED
- Menu link Hover color is bad - FIXED
- While loading an article, spinner doesn't show - FIXED
- Add reactions on pages - DONE
- Modification of profile and Goal Page message to make it more informative - FIXED
- Fix incorrect text on F.A.Q. Page
- Improvement of text on About page based on feedbacks
- Removal of meh icon on Know More and changed it to question mark
- Other small fixes related to text, spelling mistakes and grammer

Version 0.1.3 - 03rd January 2019
- Subnavbar not showing on mobile - FIXED 
- NavBar is not responsive and dropdown not working - FIXED
- Dropdown not working on alpha page - FIXED
- Hamburger cross color black on Alpha page - FIXED
- JS error - Profile reactive component not defined on alpha page - FIXED 
- Addition of tui editor for better Article Writing Experience (Testing) - DONE
- Version information doesn't specify the meaning - DONE 
- Primary info color does is odd and doesn't fit in design - FIXED 
- Rewards page doesn't specify 0.2 timelines - FIXED 
- Removal of Tags as they are not required - DONE 
- Image URL text Size for article is just 50 - Increase to 100 - FIXED 
- Title for article is just 50 - Increase to 100 - FIXED
- Remove repetative about page and replace it with docs.pedity.com - DONE 
- Image size not showing properly on articles - FIXED 
- Create Article Page improved
- Removal of duplicate warning messages from alpha and authenticate page

Version 0.1.4 - 15th January 2019
- Kelp updated to 1.3.0 - DONE 0.1.4
- Scroll issue on alpha page - ADDED 0.1.4
- Change the article page and modify the layour - DONE 0.1.4
- Modify width of articles - FIXED 0.1.4
- Removal of gradient from navigation background - DONE 0.1.4
- Addition of Pedity Keybase - https://keybase.io/pedity
- NEW - https://api.pedity.com now shows important infomation related to API release plan

Version 0.1.5 - 12th February 2019 - Major changes in API
Backend Updates - 
- Updated API endpoints in v1 
- Added node related informtion
- Updated go-stellar to latest version 
- Different backend nodes can now be synced
- pedi-api configuration is now added for easy running individual nodes
- Reduced API load by reducing no of queries from frontend to API node
- Fix an issue with create article not getting created in first run
- Migrated go-ipfs from 0.4.16 to go-ipfs 0.4.18

Frontend Updates - 
- Updated js-stellar-sdk to latest version
- Added setTimeout method on frontend for javascript sdk
- Changed transaction signing to make sendings tips
- Added new SSL certificate on frontend

Version 0.1.6 - 21th February 2019
- Create article fields are required and can't be empty - DONE 0.1.6
- Preview button currently not working on creating article
- Link to API on Pedity platform frontend - DONE 0.1.6
- Addition of Nodes on Pedity Frontend - DONE 0.1.6
- Removal of storage of private key and user needs public key - DONE 0.1.6
- Creating content now requires private key since storage of key is removed - DONE 0.1.6
- Custom amount for tipping - DONE 0.1.6
- Disable Loading button when it is loading from API - DONE 0.1.6
- XDR is now available when creating content so that user can submit XDR data on stellar labs - DONE 0.1.6
- Modify icons on Preview and Create on create page - DONE 0.1.6

Version 0.1.7 - 25th February 2019
- Documentation Release - https://docs.pedity.com

Version 0.1.8 - 3rd March 2019
- Footer updated with more information - DONE 0.1.8
- Social icons size updated to better match footer design - DONE 0.1.8
- Subscription added monthly updates from Pedity - DONE 0.1.8
- Pages that submit content now require authentication - DONE 0.1.8
- Read More button is removed from Alpha page - DONE 0.1.8
- Rewards page modified to specify 0.2 timelines - FIXED 0.1.8
- Removal of redundant links from sidebar - DONE 0.1.8
- Create now shows only to users with Valid public key - DONE 0.1.8
- Clean renamed to Logout for regular convention - DONE 0.1.8
- Store public key in browser storage on login - DONE 0.1.8
- Addition of State management - DONE - 0.1.8
- Check Authentication of page after cleaning keys - DONE 0.1.8

 Update on Pedity Docs
- Fix Concepts page having IPFS twice, where it should be IPFS and IPLD
- On concepts page, Text for General section is not properly format
- On Concepts page, Community is not updated properly

Version 0.1.9 - 6th March 2019
- Show blog even when the profile is not set - DONE 0.1.9
- Show profile balance even when profile doesn't exist - DONE 0.1.9
- Bug - Refresing removed login from the navbar even though user is logged in - FIXED 0.1.9
- Modify Profile to fix issues related to not loading data - DONE 0.1.9
- Redesigned the profile page (Example: https://pedity.com/profile/GBB2S6FOUVNJW2OHOHORJK4N2HTIQYPVY3JCZVZ54CZZKSE2FVWW2O7Q) - DONE 0.1.9
- Addition of Keybase in social profile fields - DONE 0.1.9
- Fix profile and goal submission using private key - DONE 0.1.9
- Fix redirects after modification of profile - DONE 0.1.9
- Removal of links from sidebar - DONE 0.1.9
- Update of About page - DONE 0.1.9

Update on backend
 - FIXED BLOCKING ISSUE- platform frontend unable to fetch ipfs content from different nodes 
 - Added keybase in schema data for profile
 - Fixed missing data from blog endpoint

Pedity 0.2 release
https://medium.com/@pedity/pedity-alpha-0-2-on-the-horizon-bf4a51442f5e

Pedity 0.2.1 - 22nd March 2019
- Fix incorrect image not available on Alpha, Blog, Article page
- Fixed issue with reward page not showing last payments
- Rewards server is now working properly with batch payments in 24 hours
- Login error now shows minimum balance requirements
- Fixed final transaction showing as blank on Alpha page
- Error Messages are now more meaningful on Profile and article creation
- Fixed secret key incorrect value on profile modification
- Improved loading of Alpha page on mobile devices
- Access to api.pedity.com to developers

Upcoming features and updates
- Allow users to copy XDR 
- Allow users to see XDR on Edit profile
- Modification of tips to design better
- Search of content by v3


Use Github (https://github.com/PedityOfficial/Pedity-Platform/issues) or Telegram(https://t.me/pedity) for issue reporting.
