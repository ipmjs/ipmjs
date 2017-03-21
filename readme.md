<p>
  <img height="50" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR4nGNiYAAAAAkAAxkR2eQAAAAASUVORK5CYII=">
</p>
<p align="center">
  <img height="auto" width="300" src="https://raw.githubusercontent.com/ipmjs/logos/master/logo.gif">
  <p>
    <img height="50" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR4nGNiYAAAAAkAAxkR2eQAAAAASUVORK5CYII=">
  </p>
</p>

#### What's this?

This is an open initiative to make sure [this](https://medium.com/@azerbike/i-ve-just-liberated-my-modules-9045c06be67c#.8b8cid7h0) won't happen again. We think that immutability is a good way forward, but we need to reach some kind of consensus in the community. Please let us know what you think. Send PRs here, add issues, send tweets. Let's solve this.

#### Join the conversation

The easiest way to join is on Gitter:
[![Join the chat at https://gitter.im/ipmjs/ipmjs](https://badges.gitter.im/ipmjs/ipmjs.svg)](https://gitter.im/ipmjs/ipmjs)

Opening issues and PRs here is also welcome!

#### Motivation
[Azer](https://twitter.com/azerbike) rightfully rage-quited when kik decided to send their lawyers and claim ownership of his package name 'kik', which he refused. kik then contacted npm which then revoked Azers ownership. derp.

Azer replied by deleting all of his ~250 npm packages which according to npm, resulted in hundreds of broken builds every second worldwide. double-derp.

#### What is the problem?
Node.js is dependent on npm to be functional, since the majority of web developers use it to manage dependencies in their projects. npm is also a for-profit company which could be a problem since
it might make decisions (like [this](https://medium.com/@mproberts/a-discussion-about-the-breaking-of-the-internet-3d4d2a83aa4d#.3lrsd6pfw)) that might not be in its own community's best interest.

#### How could we solve this?
Create an open-sourced alternative to npm,  make it immutable, meaning that
if a package is published, it will be available for all its dependents til the end of times. This would solve the issues that npm has right now, that a package could be published one second to be unpublished the next.

#### Here is a wish list for ipm:
- A CLI (`npm install ipm-cli -g` to enable easy migration)
- Immutable packages
- Require legit licenses
- Verifiable packages
- More robust user authentication
- No more soft dependencies (>= 1.0.3 etc)
- 100% implemented on open-sourced frameworks and libraries
- Decentralized hosting?

#### I want a fix now, how could npm be fixed today?!
Ask npm to make their stuff immutable, an `npm install` today should have the same result as `npm install` next year. 
