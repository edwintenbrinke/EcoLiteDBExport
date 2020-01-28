# EcoLiteDBExport
An database export tool for the game Eco

## Usage
- configure the `config.json` file to your desire.
- edit the `"previous_run_data"` array in the `config.json` to include the LiteDB collections you want it to export
- *currently supported collections:*
    - PickupAction
    - PlayAction


### TODO
- implement other collections to the data_models
- make it loop every {config} minutes
- error handling
- send logs to api to monitor memory usage etc
- find a way to send a message on crash
