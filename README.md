# Terminal-OpenTTD-TOTTD-
> A CLI linux tool for managing OpenTTD instances, and other useful OpenTTD-related tools, like downloading BaNaNaS content without opening the game.
## Features:
> Implemented -> ✅
> Planned -> ❌
### Instance management
- ❌ tottd
> Base command, launches the selected version if used without any flags or positional arguments
- ❌ tottd -S
> Setups the game automatically by downloading the latest version and launching it after it was downloaded
- ❌ tottd dedicated | tottd -D
> Launches a dedicated server using the selected version
- ❌ tottd version [version_number]
> Changes the currently selected OpenTTD version, e.g. tottd version 15.3, tottd version latest
- ❌ tottd download [path]
> Downloads the selected version into the specified path, unzips it into a new folder
- ❌ tottd version list
> Fetches all available OpentTTD versions to download
>> Flags: -L: lists versions that are installed locally 
### BaNaNaS
- ❌ tottd bananas [package_ID]
> Downloads a package from BaNaNaS by ID into the correct folder
- ❌ tottd bananas search [query]
> Search by name for BaNaNaS packages, prints any matching BaNaNaS packages' name, ID, author, upload date, version, and description
>> Flags: -Ld: only prints the name, ID, and author

