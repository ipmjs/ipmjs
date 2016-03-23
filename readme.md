<p>
  <img height="50" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR4nGNiYAAAAAkAAxkR2eQAAAAASUVORK5CYII=">
</p>
<p align="center">
  <a href="http://ipmjs.org">
    <img height="125" src="https://raw.githubusercontent.com/ipmjs/logos/master/logo.gif">
  </a>
  <p>
    <img height="50" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR4nGNiYAAAAAkAAxkR2eQAAAAASUVORK5CYII=">
  </p>
</p>


__March 22, 2016__ will forever be remembered for all of us who is hooked on __npm__ and its beautiful ecosystem of modules. This was the day when [Azer](https://twitter.com/azerbike) rightfully rage-quited because kik decided to send its lawyers and claim ownership of the package name 'kik', which the author refused. kik then contacted npm which gave kik the ownership. derp.


Azer unpublished all of his ~250 npm packages which according to npm, resulted in hundreds of broken builds every second worldwide.

__What is the problem?__ node.js is dependent on npm to be functional, since the majority of web developers use it to manage dependencies in their projects. npm is also a for-profit company which could be a problem since
it might make decisions (like this) that might not be in its own community's best interest.

__How could we solve this?__ create an open-sourced alternative to npm,  make it immutable, meaning that
if a package is published, it will be available for all it's dependents till the end of times. This would solve the issues that npm has right now, that a package could be published one second to be unpublished the next.


__Here is a wish list:__

- Immutable packages

- Verifiable packages

- More robust user authentication

- No more soft dependencies (>= 1.0.3 etc)

- 100% implemented on open-sourced frameworks and libraries

- Open-source-based hosting

__Signed by__

Pierre Reimertz  | [github](https://github.com/reimertz) | [twitter](https://twitter.com/reimertz)


