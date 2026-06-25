# JV1968GH Copilot Plugin Marketplace

Deze repository publiceert een GitHub Copilot CLI marketplace voor:

- `JV1968GH/Octoplant-Plugin`
- `JV1968GH/APG-Plugin`
- `JV1968GH/Control_Expert-Plugin`

## Toevoegen in GitHub Copilot Desktop app

Open de terminal in de Copilot Desktop app en voer uit:

```powershell
copilot plugin marketplace add JV1968GH/copilot-cli-plugin-marketplace
copilot plugin marketplace list
copilot plugin marketplace browse jv1968gh-plugins-marketplace
```

Plugin installeren vanuit de marketplace:

```powershell
copilot plugin install octoplant-plugin@jv1968gh-plugins-marketplace
copilot plugin install apg-plugin@jv1968gh-plugins-marketplace
copilot plugin install control-expert-plugin@jv1968gh-plugins-marketplace
```

## Beheer

Bij wijzigingen in `.github/plugin/marketplace.json` verhoog je `metadata.version` en commit/push je de update.