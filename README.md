# Stamplay Ionic Starter

The Stamplay Ionic Starter kit is a simple way to get a Stamplay Ionic project up off the ground.

The starter kit comes with a fully featured task list, based on user accounts. If a user does not wish to create an account, they may use the shared guest Task list to manage their tasks by adding, updating, deleting and marking them complete or incomplete.

Setup Instructions

1. Clone and cd into repo: `git clone https://github.com/Stamplay/stamplay-ionic-starter.git`
2. Run `npm install -g ionic`
4. Run `ionic platform add ios android`
5. Run `npm install && gulp install`
6. Run `stamplay init`, add Stamplay app credentials
7. In the `www/index.html`, update the `Stamplay.init("YOUR APP ID")` to include your `APP ID`
8. Inside the Stamplay Editor, add a `task` object schema with:
  - **title** - *string*
  - **body** - *string*
  - **complete** - *boolean*
9. Run `ionic serve --lab`
10. If you are new to Stamplay, or Ionic, we recommend following our tutorial of this starter kit [here](https://blog.stamplay.com/building-mobile-applications-are-a-pain).

#### Enjoy
