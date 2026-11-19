# AL15 Node-RED Flows

A collection of reusable Node-RED flows and examples for AL15 devices.

## Structure

- `system/` - system and engineering utilities
- `mqtt/` - MQTT integration examples
- `opcua/` - OPC UA examples
- `examples/` - simple starter flows

Each flow should include its own README with purpose, prerequisites, import steps, configuration, and security notes.

## Available flows

- [AL15 Linux Console](system/linux-console/README.md) - browser-based command execution interface. **Security-sensitive: do not deploy without access controls.**

## Importing a flow

In the Node-RED editor, select **Menu > Import**, choose the JSON file, review the nodes and settings, then deploy only in an appropriate environment.

## Security

Never commit credentials, private keys, tokens, internal addresses, or customer-specific configuration. Review every flow before publishing or deploying it. Public repository content is accessible to everyone.

## License

No license has been selected yet. Confirm publication and licensing rights before adding one.
