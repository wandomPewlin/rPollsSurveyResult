# Raw Data

## How to read rPolls_cleaned.csv

Since both the order of the question and the order of the options were randomized in the survey. Each question gets 3 columns of data: `questionOrder[i], optionOrder[i], optionPicked[i]`. `questionOrder0` of `18` means the first question you see in `question_and_options.json` (i.e. the color of the upvote button) appeared as the 19th question for that particular survey participant. `optionPicked0` of `1` means the participant picked the second option (i.e. Orange) as the answer. You may have noticed, all indices started from `0`. `optionOrder0` of `0` means the `Orange` option appeared as the first option for this particular participant.

`uuid` is not consecutive because some visitors did not submit the survey result.
