# Electoral System of the Executive Power in Latin America and Its Reforms

Welcome to the GitHub repository of the database "Electoral System of the Executive Power in Latin America and Its Reforms," created by Dr. Flavia Freidenberg and maintained by members of the Observatorio de Reformas Políticas en América Latina.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

This database contains information on electoral reforms to the regulations governing the electoral system of the national executive powers of 18 Latin American countries. The database includes information on modifications to the electoral formula, the existence of runoff elections, the required majorities in the first and second rounds, the duration of the term in years, and the possibility of reelection.

The review of regulations was conducted from the year of each country's transition to democracy, based on the criteria proposed by Alcántara; Paramo; Freidenberg, and Déniz (2006). For countries with gradual political change processes, the base year is the start of the third wave of democracy in Latin America (Huntington, 1991).

Members of the Observatorio de Reformas Políticas en América Latina collected and codified the information. The individuals responsible for data collection are Karolina Monika Gilas (Faculty of Political and Social Sciences, UNAM) and Luciana Modica (Universidad Nacional de Río Cuarto, Argentina), while the individual responsible for data coding is Luciana Modica (Universidad Nacional de Río Cuarto, Argentina).

## Description

The directory `./Data/` contains the file `./Data/DD_SEEjecutivo` which contains all relevant information regarding the electoral system of the Executive Power database. Specifically, the database consists of the following variables:

- `country`: name of the country where the reform to the executive electoral regime took place in Latin America.
- `concode`: country code according to the "Correlates of War" coding available at: https://correlatesofwar.org/data-sets/cow-country-codes.
- `country_abbreviations`: country abbreviations according to the three-letter ISO code (for example: ARG, MEX, SAL) available at: http://utils.mucattu.com/iso_3166-1.html.
- `consecutive_reform_country`: records the consecutive number of reforms to the executive electoral regime in each Latin American country. Example: Peru_1, Peru_2, Peru_3, Peru_4.
- `year`: calendar year to which the reform to the executive electoral regime in each Latin American country corresponds between 1978-2021.
- 'electoral_system': indicates how the national executive power election is defined. Its values are [1]: Electoral college; [2]: Relative majority; [3]: Absolute majority; [4]: Two-round system; [5]: Lema law.
- `existence_2nd_round`: indicates the existence or non-existence of the second round in elections for the national executive power. Its values are No [0]: the regulation does not consider the existence of a runoff election and Yes [1]: the regulation considers the existence of a runoff election.
- `majority_1st_round`: indicates the necessary majority to win the election for the national executive power in the first or only round. Its values are Relative majority [1]: relative majority in a single round; >50% [2]: greater than 50% of the votes; >50% or 25 pts. [3]: greater than 50% of the votes or a difference of 25 points with the second place; >50% or 40% + 10 pts. [4]: greater than 50% of the votes or 40% plus a difference of 10 points with the second place; >45% [5]: greater than 45% of the votes; >45% or 40% + 10pts. [6]: greater than 45% of the votes or 40% plus a difference of 10 points with the second place; >40% [7]: greater than 40% of the votes; >40% or 35% and 5 pts. [8]: greater than 40% of the votes or 30% plus a difference of 5 points with the second place.
- `majority_2nd_round`: indicates the necessary majority to win the election for the national executive power in the second round. Its values are Absolute majority [1]: the executive power is elected with an absolute majority in the second round; Majority in Congress [2]: the executive power is elected with a majority in Congress.
- `term_years`: indicates the duration of the term of the national executive power in years.
- `reelection`: indicates the existence or non-existence of reelection of the national executive power. Its values are No [0]: the regulation does not consider reelection and Yes [1]: the regulation considers reelection.

## Citation

```r
Freidenberg, Flavia. Dir., 2022, "Electoral System of the Executive Power in Latin America and Its Reforms", Observatorio de Reformas Políticas en América Latina (1978-2021). Mexico City: Institute of Legal Research (IIJ-UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SFD/OAS), V2. DOI: https://doi.org/10.6084/m9.figshare.16869293.v2 
```