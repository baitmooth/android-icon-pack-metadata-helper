# Android Icon Pack Metadata helper
- Should (in the end) contain all the latest metadata for open-source apps (primarly from F-Droid). This metadata consists of the PACKAGE_NAME , ACTIVITY_NAME and ICON_FILENAME . 
- For apps on F-Droid, the embedded script inside /bin will collect all the necessary information by reading the fdroiddata/metadata submodule folder and downloading the necessary data. 
- The original icons can be found in a separate repo / sub-module folder; because these icons would increase the repo size too much. Submodules do not get downloaded automatically during a git fetch. 
- This project has been abandoned for some years now. During this time fdroid has changed it's metadata format, so the first goal for this fork is to make the scripts working again.
- The next goal would be switching from shell scripts to some high level language.
