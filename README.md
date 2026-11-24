# SmartCampusRoomChecker — Power Apps source

This archive contains the source files extracted from the supplied Microsoft Power Apps `.msapp` package.

## Main source files
- `Src/App.pa.yaml` — app-level properties and Power Fx `OnStart` initialization.
- `Src/Screen1.pa.yaml` — screen layout, controls, properties, and Power Fx formulas.
- `Controls/` — control metadata and serialized definitions.
- `Properties.json` — app configuration and metadata.
- `References/` — theme, data source, resource, and template references.

## Notes
- The `.pa.yaml` files are the human-readable Canvas Apps source representation.
- The original `.msapp` file is included separately by the student if the instructor needs to import/open the app in Power Apps.
- Microsoft notes that YAML source is primarily intended for reviewing changes and minor edits; use Power Apps Studio / the maker portal for normal editing.
