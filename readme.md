# GeniusScanDemo
This repo was created to demonstrate the issue encountered when archiving iOS on a RN project after installing Genius scan module.


## Can't archive iOS after installing Genius Scan
The issue happens right after installing Genius scan following the docs here: https://www.npmjs.com/package/@thegrizzlylabs/react-native-genius-scan

The goal is to help repdroduce the issue by the Genius Scan team in order to eventually fix it.
The steps followed to create this project:
- Creted the project using the command `npx react-native init GeniusScanDemo --version 0.60.5`
- Followed the mentioned docs to install Genius Scan (yarn add, pod install)
- Updated iOS deployment target to match the version selected on PodFile framework from Genius Scan installation docs.