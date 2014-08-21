oldverz
=======
tag - A tool for manipulating and querying file tags.
  usage:
    tag -a | --add <tags> <file>...     Add tags to file
    tag -r | --remove <tags> <file>...  Remove tags from file
    tag -s | --set <tags> <file>...     Set tags on file
    tag -m | --match <tags> <file>...   Display files with matching tags
    tag -l | --list <file>...           List the tags on file
    tag -f | --find <tags>              Find all files with tags
  <tags> is a comma-separated list of tag names; use * to match/find any tag.
  additional options:
        -v | --version      Display version
        -h | --help         Display this help
        -n | --name         Turn on filename display in output (default)
        -N | --no-name      Turn off filename display in output (list, find, match)
        -t | --tags         Turn on tags display in output (find, match)
        -T | --no-tags      Turn off tags display in output (list)
        -g | --garrulous    Display tags each on own line (list, find, match)
        -G | --no-garrulous Display tags comma-separated after filename (default)
        -H | --home         Find tagged files only in user home directory
        -L | --local        Find tagged files only in home + local filesystems (default)
        -R | --network      Find tagged files in home + local + network filesystems
        -0 | --nul          Terminate lines with NUL (\0) for use with xargs -0
