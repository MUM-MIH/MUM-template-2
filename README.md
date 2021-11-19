# MUM-template-2 #
This is the second version of the MUM Moodle template. Created 18/08/2021. The first version continues to serve SOS and SOB and should only be discontinued after Semester 2 2022 rollover.

# Changelog #
All notable changes to this project will be documented in this file.

## Unreleased ##
- Dark mode in beta currently only deployed in SCI1020 and AMU1017.

## 2021-11-19 ##
- Centralised _Key Contacts_ customised according to Schools. MUI _Key Contacts_ moved to MUI repo.

## 2021-08-27 ##
### Added ###
- Centralised _Key Contacts_ and _Important Policy_ via javascript (addfeatures.js)
- CSS to prevent users from add/deleting sections, changing section names, rearranging sections, and editing menubar.

### Changed ###
- Alignment no longer requires "move right" on labels. All elements align left automatically now.

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
addfeatures.js | Brings in additional javascript via the Hidden Block. Controls editor behaviour and brings in centralised information.
addcss.css    | Brings in additional css via the Hidden Block. Styles things that will not appear on the same page as the menubar (Moodle Books, Lessons etc.); styles accordion in Overview.
anchor.js     | Creates anchor links on all H2, H3 and Heading Large text. 
artsbannerbackup.css, artbannerbackup.js | Controls and styles the menubar.
gridicons.css | Brings in the icons used on the Overview page and determines their position on the grid.
hiddenoverview.js | Hides the accordion elements from displaying across Moodle site (this is the default behaviour).
icon_x | Grid icon actual images.
main.css      | Does most of the work in determining how our site looks including colours, alignment and html elements. Called into moodle site via the menubar.
BU_accordion | Backup html code that creates the accordion element in _Overview_.
BU_additional-resources | Backup html code that creates the header in _Addtional Resources_.
BU_assessment-1 | Backup html code that creates the assessment descriptions placeholders in _Assessments_.
BU_assessment-table | Backup html code that creates the assessment overview table in _Assessments_.
BU_design-resources | Backup html code that creates title and instructions box in _Design Resources_.
BU_forums-head | Backup html code that creates the headers with description text in _Forums_ and other places.
BU_hiddenblock | Backup html code that is inserted into the _Hidden Block_.
BU_important-policy | Backup html code that creates the placeholder in _Important Policy_.





