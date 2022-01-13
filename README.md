# OpenFaas Node.js v16 and Puppeteer v10.0.0 Template

This template for Open FaaS uses docker-puppeteer by buildkite v10.0.0 and allows you to use puppeteer with node.js v16.

## Quickstart

### Get OpenFaaS

[Deploy OpenFaaS](https://docs.openfaas.com/deployment/) to Kubernetes, or to faasd (single-node with just containerd)

### Create a function with the template and deploy it to OpenFaaS

```bash
faas-cli template pull https://github.com/mariamorav/openfaas-puppeteer-node16-template

faas-cli new --lang puppeteer-node16 <function_name> --prefix <registry>

faas-cli up -f <function_name>.yml

```
