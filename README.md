# GSoC-2020-Report

## Introduction

GSoC was my first programming experience outside personal projects and I thoroughly enjoyed the experience. I had an awesome opportunity to work for the ns-3 organization. My mentors [abhijithanilkumar](https://github.com/abhijithanilkumar/), [mishalshah](https://github.com/mishal23) and [adeepkit01](https://github.com/adeepkit01) were extremely responsive, helpful, and understanding. I would also like to thank [tomh](http://www.tomh.org/) sir - the ns-3 Organization Admin for help and suggestions.

## Project outline

**Project Goals** : To develop a Jenkins server and add necessary updates to ns-3 AppStore to check on-demand if available, uploaded or updated apps/modules/forks to AppStore build and pass tests successfully for the given ns-3 versions and display that information on AppStore.

The project was completed in following phases :

1. **Community Bonding** - Solving some of the existing issues and getting familiar with codebase.
2. **Phase 1** - Added build model to AppStore, experimented with Jenkins locally, and wrote bash scripts used by pipelines.  
3. **Phase 2** - Added functionalities to AppStore for Jenkins communication, REST APIs and their tests in AppStore for Jenkins, and Build history page for app release.
4. **Phase 3** - Added pipelines to deployed Jenkins servers, configured the environment for AppStore - Jenkins communication, and added contributing, installation and Jenkins documentations.
  
## Commits and merge request

[#69](https://gitlab.com/nsnam/ns-3-AppStore/-/merge_requests/69) : ALl my work lies on branch mentioned in this merge request.

