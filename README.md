# Windhager Heater 2

This is a custom component for Home Assistant to integrate Windhager heaters.

## Installation using HACS

1. Install [HACS](https://hacs.xyz/)
2. Add this repository as a custom repository in HACS by clicking on the three dots in the top right corner and selecting "Custom repository".
3. Enter the following as the repository URL and select "Integration" as the type:
```
https://github.com/jannemannX/ha-windhager2
```
4. Search for "Windhager Heater 2" and download it.
5. Restart Home Assistant.

## Installation using manual method

1. Download the repository as a zip file from [here](https://github.com/jannemannX/ha-windhager2/archive/refs/heads/main.zip).
2. Extract the zip file to the `custom_components` folder in your Home Assistant installation.
3. Restart Home Assistant.

## Configuration
1. Add the integration as usual.
2. Enter the host and password of your Windhager heater.
3. The integration will now be available in Home Assistant.

## Debugging

If you want to debug the integration, please add the following to your `configuration.yaml` file:

```yaml
logger:
  default: warning
  logs:
    custom_components.windhager2: debug
```

This will enable debug logging for the Windhager integration.

If any values are displayed as "Unknown", please check the logs for more information.

## Reporting issues

Please report any issues to the [GitHub repository](https://github.com/jannemannX/ha-windhager2/issues). Please include the logs and what device you are trying to integrate.

## Supported devices

| Device | Status | Notes |
|--------|:------:|-------|
| BioWin II | ✅ | Infowin Touch (1.0.2), API (1.0.0)  |
