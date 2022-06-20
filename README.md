# Botanalytics Python SDK - Examples

## Rasa Examples

> This example is based on the official Helpdesk Assistant Rasa bot sample.

### Getting Started

* Follow the steps defined in the sample's [README](/rasa/README.md).
* Create a Botanalytics project, add Rasa channel.
* Configure custom event broker within your `endpoints.yml`.
* Set type as `botanalytics.rasa.Rasa` in `endpoints.yml` under event broker.
* Set the provided API key as `BA_API_KEY` environment variable in `.env` file or as `api_key` under `endpoints.yml` file under event broker.

``` yaml
# endpoints.yml file example
event_broker:
  type: botanalytics.rasa.Rasa
  api_token: `BA_API_KEY`
  debug: true
```
