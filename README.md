# Notarized QGIS builds for macOS

This repository creates notarized builds of QGIS for macOS.
It is based on the pull request https://github.com/qgis/QGIS/pull/60039 and creates notarized builds of preview packages built there.
As such, they are currently experimental and meant for testing only.

Packages are signed with OPENGIS.ch certificats.

To download packages for local testing, head over to https://github.com/opengisch/qgis-notarize/actions click on a recent run and you will find a download link in the Artifacts section at the bottom.

This is a public preview and will be moved to the https://github.org/qgis organization and run with OSGEO certificates before being published as stable release with QGIS 4.0 in October 2026.
