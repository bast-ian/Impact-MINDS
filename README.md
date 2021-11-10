# Impact-MINDS

This analysis was conducted for MINDS Yishun Training and Development Center for the intellectually-challenged with the primary motive to identify the impact of YTDC's activities on beneficiaries' wellbeing and capabilities.

The data used was originally internal but has been randomized for this presentation. Hence, no significant insights can be derived but the methodology is retained.

The report primarily uses linear regressions to identify the effect of MINDS's activities on beneficiaries wellbeing score (0 to 5) or MISO scores, either via individual indicators (-1 to 1) or via aggregation (-9 to 9).

Here's a description of the variables used in the dataset:
| Variable   | Description                                                                                            |
|------------|--------------------------------------------------------------------------------------------------------|
| Activity   | {Daily Walks, Community Mobility or Arts & Craft}                                                      |
| Contact ID | A beneficiary identifier                                                                               |
| Stage      | The stage of the assessment {Pre-Service, Post-Service}                                                |
| Question   | Question posed to the beneficiary, One-to-one associated with the indicator used                       |
| Rating     | The rating ascribed by the respondent. {-1,0,1} for MISO indicators and {0 to 5} for General Wellbeing |
| Text       | Long Text Responses, usually describing the respondent's score                                         |
| Indicator  | MISO or wellbeing indicator being measured, One-to-one associated with the question posed              |
