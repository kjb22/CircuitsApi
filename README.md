# CircuitsApi
Scenario Outline: 
Check the number of races in a season 
Given I want to know the number of Formula One races in &lt;season> 
When I retrieve the circuit list for that season 
Then there should be &lt;numberOfCircuits> circuits in the list returned 
Examples: 
| season | numberOfCircuits | 
| 2017 | 20 | 
| 2016 | 21 | 
| 1966 | 9 | 
| 1950 | 8 |
