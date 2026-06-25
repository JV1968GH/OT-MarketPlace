# OT-MarketPlace

Deze repository publiceert een GitHub Copilot CLI marketplace voor:

- https://github.com/JV1968GH/Octoplant-Plugin
- https://github.com/JV1968GH/APG-Plugin
- https://github.com/JV1968GH/Control_Expert-Plugin

## Toevoegen in GitHub Copilot Desktop app

Open de terminal in de Copilot Desktop app en voer uit:

```powershell
copilot plugin marketplace add <owner>/OT-MarketPlace
copilot plugin marketplace list
copilot plugin marketplace browse ot-marketplace
```

Plugins installeren vanuit de marketplace:

```powershell
copilot plugin install octoplant-plugin@ot-marketplace
copilot plugin install apg-plugin@ot-marketplace
copilot plugin install control-expert-plugin@ot-marketplace
```

## Beheer

Bij wijzigingen in `.github/plugin/marketplace.json` verhoog je `metadata.version` en commit/push je de update.