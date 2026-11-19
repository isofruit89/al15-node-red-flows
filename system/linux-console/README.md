# AL15 Linux Console

## Purpose

Provides a browser-based shell command interface through Node-RED HTTP endpoints.

## Endpoints

- `GET /console` - HTML console interface
- `POST /console/exec` - executes a submitted shell command

## Prerequisites

- Node-RED runtime on a compatible Linux-based AL15 environment
- Built-in Node-RED nodes: HTTP In, HTTP Response, Template, Function, Exec

## Import

Import `AL15 Linux Console.json` into Node-RED. Review the flow, HTTP paths, runtime permissions, and network exposure before deploying. No external Node-RED packages are declared in this export.

## Security warning

**Do not deploy this flow on a publicly or broadly reachable Node-RED instance.** The POST endpoint has no flow-level authentication or command restrictions and executes shell commands with the Node-RED process privileges. An exposed endpoint can permit remote command execution. Add robust authentication, authorization, network isolation, and preferably a strict command allowlist before use.

## Status

Imported from the supplied original flow without modifications. Runtime behavior and compatibility have not been tested here.
