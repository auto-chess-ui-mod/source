# Changelog
All notable changes to this project will be documented in this file.

##  2019-04-30  
### Added
- Added code for Io and Dazzle  

### Changed
- Removed Lich from pool  
- Merged optimiziation by user [boingy](https://github.com/boingy)

##  2019-04-29   
### Changed
- Temporarily disabled the probability colors untill I figure out the right way to display the relative probability  
- Re-implemented the probability calculation to be more accurate, it now simulates the actual draw algorithm

##  2019-04-26 
### Added
- Percentages in the hero list are now color coded depending on their relative availability (green to red)

### Changed
- Further optimized code to reduce FPS stutters
- Fixed problem with probabilities being off due to a bug in the source code of Dota 2 / DAC that would result in "ghost" heroes. See [Issue](https://github.com/auto-chess-ui-mod/download/issues/6)

##  2019-04-26 
### Changed
- Optimized code to only draw probabilities upon draw instead of each second for the drawn heroes

##  2019-04-26 
### Added
- Support for Chinese clients 
- Readme for Chinese players (courtesy of [zizouqi](https://github.com/zizouqi))

##  2019-04-25 
### Added
- First release