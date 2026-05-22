# Phone Required Before Conversion

## Purpose
Ensures leads cannot be converted without a phone number.

## Formula

AND(
IsConverted = TRUE,
ISBLANK(Phone)
)

## Business Value
Improves lead data quality and prevents incomplete conversions.
