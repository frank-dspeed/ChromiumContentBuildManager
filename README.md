# ChromiumContentBuildManager
ChromiumContentBuildManager - Is a https://github.com/stealify compatible component collection to Manage Chromium src and builds.
It runs on every stealify-host a cross platform arch scripting host that supports Languages like Stealify Lang, ECMAScript, MESON, GN and many more ....

## Features
- [ ] Can build chromium/v8
  - [ ] extract the v8 Build parts into own v8BuildManager
- [ ] Can build chromium/ ```<thrid_party/NodeJS>```
  - [ ] extract the NodeJS Build parts into own NodeJSBuildManager
- [ ] Can build chromium/content
  - [ ] Can optional build with WPE
    - [ ] extract the WPE Build parts into own WPECogBuildManager cog is the WPE Equivalent of chromium/content
- [ ] Can static build Itself in a browser via rtc-cluster even distributed p2p using stealify/fs as exposed via vfssync
  - [ ] https://github.com/s-macke/jor1k
- [ ] Works well with the Web Platform Build of VSStudio
- [ ] Gerrit and google code editor as also repository support
 - [ ] Easy Install via just droping a executeable to your desktop that ships pre packaged stealify-host component for your operating system.
   - [ ] It will guide you with the setup 
- Supports headless execution via any stealify-host simply deploy the ChromiumContentManager to your /components folder on the stealify-host or use its api to deploy the component.
