# Upgrading Install4j

## Installer File

- Download a new installer file from install4j
- Upload the new installer file to the 'assets' repository
- Update triplea-game build actions (in folder .github/) to download the updated install4j

## License Key

Install4j has a website to upgrade the install4j license key:
https://www.ej-technologies.com/support/upgradeProduct

After that is done:
 - record the license key in the secrets file.
 - update github action secrets environment variable with the updated license key
  (done via github website > settings > secrets)

## Install4j Config

- Install install4j locally.
- Launch install4j
- Locate the *.install4j file checked into the code
- Open the 'install4j' file as a project and 'save'
- Commit the file updates and push

