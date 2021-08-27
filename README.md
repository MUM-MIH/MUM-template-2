# MUM-template-2 #
This is the second version of the MUM Moodle template. Created 18/08/2021. The first version continues to serve SOS and SOB and should only be discontinued after Semester 2 2022 rollover.

# Changelog #
All notable changes to this project will be documented in this file.

## Unreleased ##
- Custom Key Contacts information based on School/Faculty/Campus


## 2021-08-27 ##
### Added ###
- Centralised _Key Contacts_ and _Important Policy_ via javascript (addfeatures.js)
- CSS to prevent users from add/deleting sections, changing section names, rearranging sections, and editing menubar.

### Removed ###
- Embed live gdoc


## 2021-08-19 ##

### Added ###
- Embed live gdoc in _Important Policies_ for consistency
- Placeholder in _Important Policies_ to indicate possibility of adding more relevant policies.
- Alert box in _Assessments_ about academic integrity
- New section (Recycle Bin) for staff eyes only (based on request)

### Changed ###
- _Unit Calendar_ to _Unit Schedule_
- _Zoom Links and Schedule_ to _Class Timetable_
- Moved _Class Timetable_ to Section 2

### Removed ###
- Old label in _Important Policies_

# Contents: #

File name     | Description
------------- | -------------
gridicons.css | Brings in the icons used on the Overview page and determines their position on the grid.
main.css      | Does most of the work in determining how our site looks including colours, alignment and html elements. Called into moodle site via the menubar.
addcss.css    | Brings in additional css via the Hidden Block. Styles things that will not appear on the same page as the menubar (Moodle Books, Lessons etc.)
addfeatures.js | Brings in additional javascript via the Hidden Block. Controls editor behaviour and brings in centralised information.







