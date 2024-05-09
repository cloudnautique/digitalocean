# Digital Ocean GPTScript tool

## Introduction

This gptscript tool makes it easy to interact with Digital Ocean through the v2 api.

## Quick example

```bash
export GPTSCRIPT_API_DIGITALOCEAN_COM_BEARER_AUTH=<key>
```

Then you can do things like:

```bash
gptscript eval --tools "github.com/cloudnautique/digitalocean/droplets" "List all Vms in Digital Ocean"
```
