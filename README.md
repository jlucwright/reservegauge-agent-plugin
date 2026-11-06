# ReserveGauge CSV review

Review a selected [ReserveGauge](https://reservegauge.com) CSV export for missing readings, reset boundaries and observed changes. The skill accepts a user-supplied file or rows. It has no app or provider connection and does not produce ReserveGauge's forecasts.

Import this Agent Plugins v1 package into Hermes and invoke `reservegauge-agent-plugin:reservegauge-csv-review`. Export the CSV from the app's Settings. The skill asks for a reduced set of columns where possible and never needs account tokens. The package contains no executable code, network client, install script, credential store, background process or telemetry. Hermes reads the selected input, and the user's configured model service processes the supplied usage rows.

The documented export header is grounded in `Sources/ReserveGauge/Storage/SnapshotStore.swift` in the product source. MIT covers this package; product names and service access retain their separate terms.
