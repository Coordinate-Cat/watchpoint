# Watchpoint

> [!WARNING]
> Currently, this project is alpha.
> This is a work in progress project. It is not yet ready for production use.

This is a [Plasmo extension](https://docs.plasmo.com/) project bootstrapped with [`plasmo init`](https://www.npmjs.com/package/plasmo).

## Development

First, run the development server:

```bash
pnpm dev
```

### Making production build

Run the following:

```bash
pnpm build
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.

- [x] Card component (for all data)
- [ ] Card component (for each data)
- [ ] Table component (for all data)
- [ ] Table component (for each data)
- [ ] Datalization component
- [ ] Plus button component
- [ ] Settings component
- [ ] Admin info component
- [ ] QA component
- [ ] About component
- [ ] Request & Bug Report Form component
- [ ] User Guide component
- [ ] Privacy Policy component
- [ ] Terms of Service component
- [ ] License component
- [ ] Resources component

### Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!

## Resources

- https://github.com/jivoi/awesome-osint/blob/master/README.md
  - for categorization
