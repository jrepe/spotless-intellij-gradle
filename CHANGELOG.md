<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# spotless Changelog

## [Unreleased]

## [1.0.10]
Remove upper bound for `untilBuild` to prevent plugin being outdated for new IntelliJ clients.

No logical changes made to the plugin.

## [1.0.9]
- Bump latest version of IntelliJ supported

## [1.0.8]

## [1.0.7]

## [1.0.6]

## [1.0.5]

## [1.0.4]
- Add Gradle version parsing to determine if we should append `--no-configuration-cache` option to the `spotlessApply` command.

## [1.0.3]

## [1.0.2]
- Updated version range lower bound to 211

## [1.0.1]
- Update README for a more helpful plugin description

## [1.0.0]
- Initial scaffold created from IntelliJ Platform Plugin Template
- Implemented initial version of spotlessApply action which executes the gradle task in the background asynchronously
- Users can now execute spotlessApply for their current file by selecting Code > Reformat Code with Spotless