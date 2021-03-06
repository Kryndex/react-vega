## Development

### Run

To run in development mode

```
gulp
```

See your site at [localhost:7000](http://localhost:7000). It will automagically refresh when you change the code (via browsersync).

### Test

Run this command to test once.

```
npm test
```

Or run this command to test and retest when files are changed.

```
npm run tdd
```

Test coverage will be generated to ```coverage``` directory.

### Deployment

```bash
# Choose from one of these
npm version patch
npm version minor
npm version major
# Check package version and size.
# If everything looks good, then publish
npm publish
```