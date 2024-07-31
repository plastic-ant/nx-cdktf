## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Install

```shell
# npm
npm install --save-dev @plastic-ant/nx-cdktf

# yarn
yarn add --dev @plastic-ant/nx-cdktf
```

## Usage

Add this plugin to your `nx.json` config:

```
"plugins": [
    {
      "plugin": "@plastic-ant/nx-cdktf",
      "options": { ... }
    }
]
```

```
options:
  synthTargetName      (optional) generated target synth, default cdktf-synth
  deployTargetName     (optional) generated target deploy, default cdktf-deploy
  getTargetName        (optional) generated target synth, default cdktf-synth
```

## License

This project is MIT licensed 2024 Plastic Ant Software

## Links

- [Nx](https://github.com/nrwl/nx)
- [Terraform CDK](https://developer.hashicorp.com/terraform/cdktf)
