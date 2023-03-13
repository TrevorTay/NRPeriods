Created by Trevor Taylor

# NRPeriods
Calculate NR Periods

NR Period Calculator.txt contains the code to add into a blank Power Query to calculate the NR period from a date value.
Name the resulting function fxCalcPeriod.
Easiest way to call the function that creates a new column as follows:
#"Added Custom" = Table.AddColumn(#"Source", "NRPeriod", each fxCalcPeriod([Date]))
