# Public Data

Generated SQLite databases for AntoineChalons public web applications.

| File | Application | Source repository |
|---|---|---|
| `pet_services.db` | Jeju Pet Care Finder | Private `jeju-petcare-data` |
| `beaches.db` | Jeju Beach Finder | Private `jeju-beach-data` |

These files are generated artifacts. Do not edit them directly. Each private
source-data repository validates its CSV files, builds its database, checks
SQLite integrity, and publishes only the database through GitHub Actions.

GitHub Pages serves the files from:

```text
https://antoinechalons.github.io/public-data/<filename>
```

