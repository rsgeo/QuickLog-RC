# QuickLog-RC
Small tool to facilitate rapid and accurate geological logging of RC chips.

## Aim
simple python GUI application for geological logging

## GUI & Content
+ initial setup window
  + drillhole length
  + sampling interval
+ data entry window
  + header information
    + drillhole ID / date / geologist / shift
  + logging
    + lithology percentages
    + quartz & sulphide presence
  + sampling
    + sample y/n
  + QAQC
    + blank / duplicate / standard

## Considerations
+ setup window for hole length & interval --> generate correct number of input fields, plus correctly label intervals
  + requires generation of tkinter fields/buttons/labels based on a loop from user input, then generate the logging sheet
+ calculation of first and second lithologies from user input percentages
+ handling of missed intervals
+ check box selection for interval sampling
+ visualisation of the log, simple 2d block colour lithology
+ export to .csv file when completed
