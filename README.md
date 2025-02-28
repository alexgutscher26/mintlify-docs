# MonitorFlow Documentation

Welcome to the MonitorFlow documentation! This documentation will help you understand and integrate MonitorFlow's powerful event monitoring solution into your SaaS application.

## Documentation Structure

Our documentation includes:

- Getting Started Guide
- API Reference
- Integration Guides
- Discord Bot Token Setup
- Subscription Management
- Best Practices

### Development

To preview the documentation changes locally, install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

Run the following command at the root of the documentation (where docs.json is):

```bash
mintlify dev
```

### Publishing Changes

Changes are automatically deployed to production when pushed to the main branch through our GitHub integration. Install our GitHub App to enable automatic documentation updates.

### Troubleshooting

- If Mintlify dev isn't running, execute `mintlify install` to reinstall dependencies
- For 404 errors, ensure you're in a directory with `docs.json`
- Check that all referenced images and assets exist in the specified paths
