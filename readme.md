#Installation for Mac

Copy somehere useful:

```cp dsi /usr/local/bin```

If needed make the script executable:

```chmod +x /usr/local/bin/dsi```

For all login shells to initialise Docker:

Add `source dsi <docker-machine env name, default used if omitted>` to `.bash_profile`

To run manually:

```. dsi <docker-machine env name, default used if omitted>```

Don't forget the . you need to run this script in the current shell.
