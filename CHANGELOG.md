# BetterWeather Change Log

## Version 3.0.4 (43):
  - Fixed a bug where location name could be null and cause a crash
  - Fixed regex for getting lat/long from settings

## Version 3.0.3 (42):
  - Added localization support for western users
  - Fixed Feels like usage and labels
  - Added translations

## Version 3.0.2 (41):
  - Removed Forecast API

## Version 3.0.1 (40)
  - Fixed FC when getting Lat/Long info from settings

## Version 3.0 (39):
  - Added WeatherAPI Interface
    - Added Forecast API
    - Added OpenWeatherMap API
  - Added Settings to switch between APIs
  - Added Icon Themes Interface
  - Fixed GPS Lock
  - Refactored lots of code
  - Separated Yahoo Places API from Weather API

## Version 2.3.3 (38):
  - Updated Pebble libraries
  - Fixed translations

## Version 2.3.2 (37):
  - Updated translations for multiple languages
  - Fixed NPE on Pebble.sendWeather

## Version 2.3.1 (36):
  - Updated target version to 19
  - Added Catalan translations
  - Updated Slovak translations
  - Fixed Russian wind direction string
  - Updated Italian translations
  - Added precision for Show Feedback setting

## Version 2.3 (35):
  - Pebble integration

## Version 2.2.2 (34):
  - Fix display bug due to worldReadable

## Version 2.2.1 (33):
  - Added SK translations
  - Fixed wind speed display, removed decimals

## Version 2.2 (31/32):
  - Fix moon icon in Climacons Pack
  - SK translation
  - Wind in M/s
      - Speed conversion functions depends on weather unit (from Mph or Km/h)
      - Setting for Mph, Km/h and m/s
      - Set sSpeedUnit accordingly
  - Fix Whitespace when only location is shown
  - Invert Low/High temps
      - Add setting and strings

## Version 2.1.4 (27):
  - Added translations
      - ZH, DE, IT, PL, RU, ES, EL, NL, SK, etc.
  - Fixed white line issue
  - Removed Internet error

## Version 2.1 (26):
  - Add option to choose from GPS+Network or only Network
  - Google Now icon pack
  - Fix null weather data
  - Fix WOEID in the settings
  - Add error reporting on widget
  - Fixed interaction between Shortcut and Touch to refresh

## Version 2.0.1 (25):
  - Fixed location search
  - Fixed default intent data

## Version 2.0 (24):
  - Fixed weather refresh issues (for real this time)
  - Added Hungarian translations

## Version 1.9 (23):
  - Added new Weather Location Preference
  - Removed Alert dialog for Network location
  - Lots of code cleanup and refactoring
  - Add translations for Wind/Humidity and speed units
      > IT, ZH
  - Added Hebrew translations

## Version 1.8.4 (22):
  - Added donation support ;)
  - Added Licenses

## Version 1.8.3 (21):
  - Added alert when network location is not enabled
  - Fixed crash when wind data isn't available

## Version 1.8.2 (20):
  - Fix translations (add from email)
  - Show Humidity, Wind and Wind Chill
  - Fixed weather refreshing issues

## Version 1.8.1 (19):
  - Add precision in settings for Shortcut
  - Add translations
  - Add leftover translations from 1.8
      - Italian

## Version 1.8 (18):
  - Add option to hide location name in expanded view
  - Add option to turn off automatic refresh
  - Add translation for new options

## Version 1.7.4 (17):
  - Added Dutch translations

## Version 1.7.3 (16):
  - Added Greek translations
  - Fixed Slovak translations

## Version 1.7.2 (15):
  - Fixed Russian translation
  - Added Slovak translations

## Version 1.7.1 (14):
  - Added Polish translations
  - Forecast text is now translated

## Version 1.7 (13):
  - Added condition status text in multiple languages
      - English
      - French
      - Russian
      - Italian
      - Spanish
      - German
      - Polish

## Version 1.6.2 (12):
  - Added Russian translations

## Version 1.6.1 (11):
  - Added Italian translations
  - Added Spanish translations

## Version 1.6 (10):
  - Added icon themes
  - Changed the way High/Low temperatures are displayed

## Version 1.5 (9):
  - Added High/Low in status text
  - When refresh on touch is enabled shortcut preference is disabled
  - Added German translations

## Version 1.4 (8):
  - Fix RuntimeException BetterWeatherExtension.java
  - Add option to show/hide Refreshing... toast
  - Added Chinese translations
  - Add About dialog

## Version 1.3.3 (7) :
  - Added feedback when clicking extension for refresh

## Version 1.3.2 (6) :
  - Added refresh options

## Version 1.3.1 (5) :
  - Corrected typos in French translation

## Version 1.3 (4):
  - Added refresh on touch
  - Added settings for refresh interval

## Version 1.2 (3):
  - Added Shortcut setting

## Version 1.1 (2):
  - Added forecasts display
  - Added setting to show/hide forecasts

## Version 1.0 (1):
  - Integrated basic extension from DashClock source
  - Added Location setting
  - Changed/Added icons