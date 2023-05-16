# MicroFrontends
Microfrontends using SingleSpa and Module Federation

You may be wondering what the difference between micro frontend and module federation is. They actually cover a lot of the same ground. But there is a difference.

The only purpose of micro front-ends is to share UI between applications, not JavaScript logic. So, the bundled code can include duplicated code.

The purpose of module federation is to share JavaScript code between applications, not UI. So, the shared code can be used in an app.

They are actually complementary. So, with module federation in a micro-frontend app, you can avoid duplicated code and provide shared UI components across the entire app.
