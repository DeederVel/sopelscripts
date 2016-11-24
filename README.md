#DeederVel Sopel script Collection™#

###Trivia.py###
Just a simple trivia script for your Sopel IRC Bot

Questions file must be written with this format, one question per line:  
`question**answer**points`  
`another question**yet another answer**points`  
You can omit the points for the question by simply writing:  
`this has no points?**Exactly`

Answers (both from the file and user input) are transformed
in lower case strings, where possible.  
Standings (general one and match one) are saved in CSV files at the end of every match.  
The script is fully UTF-8 compatible.
