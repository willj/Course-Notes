# Egghead JS Library Course Notes

https://egghead.io/courses/how-to-write-an-open-source-javascript-library

- Create an NPM account
- Add user account to your local NPM settings using `npm adduser`
- Once your package is ready to go, publish with `npm publish`
- When published to NPM, tag it in git so each version has a corresponding git version `git tag 1.0.0` then `git push --tags`
- On Github.com you can add more info to the tag/release
- repeat the same steps, to publish a new version, use semver for versioning
- For a beta release, set the version number as you would, but add `-beta.0` to the end, so `1.2.0-beta.0`
- Increment the `-beta.0` as required when you update the beta
- publish to github in the same way
- to publish to NPM, use `npm publish --tag beta`, so it doesn't become the latest version, but one people can opt in to use by running `npm install willj-sw-names@beta` (for the latest tagged with beta) or `npm install willj-sw-names@1.2.0-beta.0` (for a specific version)

## Mocha and Chai for testing

- Install `mocha` and `chai` and `--save-dev`
- Create your test file, and write your tests
- in package.json, set the test script to `mocha [your-test-file.js] -w` the -w watches it for changes
- run `npm test` and your tests will run

**Read up on mocha and chai**


