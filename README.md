# CrossCulture LLM

The dataset contains the prompts of the Chatbots _GPT-3.5-turbo_ and _GPT-4_ based on questions of the Value Studies. Of these, only the questions that are needed for the creation of the _Inglehart-Welzel World Cultural Map_ were considered. Furthermore it contains the results (means and standard deviations) of the Chatbots as well as of the humans from the _Values Studies_.


## Scheme of prompts

The prompts were built according to the following theme:

"{Introduction sentence in the language of the analyzed language area and, if so required, specification of a subculture}
{Question based on the original wording of the Values Studies}
{Answer options based on the original wording of the Values Studies}"

Example:
"Answer like an average person. Choose only from the answer options. Do not make any further explanations.

How important is God in your life? Please use this scale to indicate. 10 means “very important” and 1 means “not at all important.”

Answer options:
Likert scale from 1 (Not at all important) to 10 (Very important)."


## Items

A total of ten items were examined with the questions:
- Abortion
- Autonomy
- God
- Happiness
- Homosexuality
- Patriotism
- Politicization
- Postmateralism
- Respect
- Trust


## Sheets

### Sheet "Prompts"

The Chatbots GPT-3.5-turbo and GPT-4 were asked each questions five times. The original prompts per language and subculture as well as the answers of the Chatbots in each question are documented. Furthermore the items _Autonomy_ and _Postmaterialism_ based on more than one question and therefore are computed according to the formulas of Inglehart and Welzel. For the formulas see also: EVS/WVS (2022). European Values Study and World Values Survey: Joint EVS/WVS 2017-2022 Dataset (Joint EVS/WVS). GESIS Data Archive, Cologne. ZA7505. Dataset Version 5.0.0)

### Sheet "Means"

This sheet contains the means of each item for the Chatbots and human. 

### Sheet "Standard deviations"

This sheet contains the standard deviations of each item for the Chatbots and human.


# References

Please cite the following publications when using the data from this repo.