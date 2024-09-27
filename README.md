# AtomicRedTeam_ThreatTests

These tests were designed to test a low level of threat, then a medium or arbitrary level of threat, then leverage some higher level attacks to test different EDR solutions.

These can be run via:

## Invoke threat level 1 testing
`Invoke-AtomicRunner -listOfAtomics .\Threat1.csv -PauseBetweenAtomics 5`

## Invoke threat level 2 testing
`Invoke-AtomicRunner -listOfAtomics .\Threat2.csv -PauseBetweenAtomics 5`

## Invoke threat level 3 testing
`Invoke-AtomicRunner -listOfAtomics .\Threat3.csv -PauseBetweenAtomics 5`


Todo: Create Threat levels 1-5 for more granular levels of testing.
