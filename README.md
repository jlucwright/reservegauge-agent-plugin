# ReserveGauge CSV review

Review a selected [ReserveGauge](https://reservegauge.com) CSV export for missing readings, reset boundaries and observed changes. The skill accepts a user-supplied file or rows. It has no app or provider connection and does not produce ReserveGauge's forecasts.

Import this Agent Plugins v1 package into Hermes and invoke `reservegauge-agent-plugin:reservegauge-csv-review`. Export the CSV from the app's Settings. The skill asks for a reduced set of columns where possible and never needs account tokens. It does not read other files, run shell commands, make network requests, store credentials, start background processes or report telemetry. Supplied usage rows are processed by the user's configured Hermes and model service.

The documented export header is grounded in `Sources/ReserveGauge/Storage/SnapshotStore.swift` in the product source. MIT covers this package; product names and service access retain their separate terms.
