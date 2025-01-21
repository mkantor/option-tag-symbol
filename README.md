# option-tag-symbol

A symbol used to indicate that an object models the standard `Option` algebraic
data type.

This package is not meant to be used directly. Instead, depend on
[my `option` package](https://www.npmjs.com/package/@matt.kantor/option). This
symbol lives in a separate package to allow versioning the `option` API while
mitigating [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell) in
consuming packages.

---

#### What's with the version number?

`9007199254740991.9007199254740991.9007199254740991` is
[the maximum version allowed by npm](https://github.com/npm/node-semver/blob/v7.6.3/README.md#coercion).
Publishing the first stable release with this version means I can't even
accidentally publish a newer version, ensuring there will always be a single
unique symbol among all of your dependencies.

Also, I think it's funny.
