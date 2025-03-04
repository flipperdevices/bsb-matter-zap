### BSB ZAP configuration

To regenerate configuration, run zap-cli tool:

```bash
zap-cli generate --noUi --noServer --noLoadingFailure --appendGenerationSubdirectory --packageMatch fuzzy --zcl ../simplicity_sdk/app/zcl/zcl-zap.json --zcl ../matter_ext/src/app/zap-templates/zcl/zcl.json --generationTemplate ../simplicity_sdk/protocol/zigbee/app/framework/gen-template/gen-templates.json --generationTemplate ../matter_ext/src/app/zap-templates/app-templates.json --upgradeZapFile --in ./ -o ./
```

Specified paths are valid for invocation from the `bsb-firmware` project folder structure.
