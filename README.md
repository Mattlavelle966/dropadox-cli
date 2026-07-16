# dropadox-cli

`export DROPADOX_API_KEY=""`

Dropadox CLI

Usage:
  dropadox storage
  dropadox folders
  dropadox files [--folder ID]
  dropadox mkdir NAME [--parent ID]
  dropadox upload FILE [--folder ID]
  dropadox download FILE_ID [OUTPUT_FILE]
  dropadox delete FILE_ID
  dropadox find SEARCH_TEXT
  dropadox help

Examples:
  dropadox storage
  dropadox folders
  dropadox mkdir "Terminal Uploads"
  dropadox mkdir "Backups" --parent 101
  dropadox upload backup.zip
  dropadox upload backup.zip --folder 101
  dropadox files
  dropadox files --folder 101
  dropadox find backup
  dropadox download 234 backup.zip
  dropadox delete 234

Environment:
  DROPADOX_API_KEY    Required API key
  DROPADOX_BASE_URL   Optional API base URL
