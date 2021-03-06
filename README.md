# Hecmocer

| Portfolio webpage made with love and built with Polymer 1.x | ![Polymer](https://polymer.gallerycdn.vsassets.io/extensions/polymer/polymer-ide/0.4.3/1490052563126/Microsoft.VisualStudio.Services.Icons.Default) |
|---|---|

## :memo: Changelog
### 1.0.1
 - First fixes after testing
   - Removed service worker
   - Ordered jobs & experience in reverse chronological order
   - Justified profile text
   - Fixed bower dependencies
   - Fixed some other typos

### 1.0.0
 - Initial release!
   - Welcome
   - Profile
   - Experience
   - Places
   - Contact
   - Footer

## :rocket: Features
- [x] Hosted on Firebase
- [x] Welcoming video
- [x] i18n (ES/EN)
- [x] Responsive
- [x] Feedback forms
- [x] Optimize pictures for web
- [ ] Custom 404 page
- [ ] Resize images in places
- [ ] Migrate to Polymer2.0-rc
- [ ] Optimize first paint (lazy load)
- [ ] "About me" video
- [ ] Web analytics

## :package: Custom components
- `Pro-section-header` - Component for the header of each section
- `Pro-i18n-behaviour` - Behaviour for adding and translating locales
- `Pro-language-switcher` - Dropdown for selecting any of the available translations
- `Pro-experience-submenu` - Paper-submenu wrapper which rotates an icon on open/close
- `Pro-hoverable-item` - Component made up of a link and an icon which mirrors on hover
- `Pro-place` - Component used for a place. Contains the image, the information and a paper-dialog

## :computer: Run on localhost

### Prerequisites

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

    npm install -g polymer-cli

Download this GitHub project:

    git clone https://github.com/hecmocer-pro/hecmocer-pro.git
    cd hecmocer-pro

### Start the development server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve