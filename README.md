# MIST_gb

The MIST_gb program is two HTML/Javascript programs (one for Training, the other for the Task) used to induce acute psychological stress for research studies.

![image](https://github.com/GrantBenham/MIST_gb/assets/138258565/ada8d230-49d8-4768-b405-348f36f3cdab)

## Description

The program is modeled off a protocol developed by Katarina Dedovic et al. (2005), the Montreal Imaging Stress Task (MIST), which was itself derived from the Trier Mental Challenge Test.<br>
The MIST_gb Task consists of a series of mental arithmetic questions where the answer is always a single integer between 0 and 9. <br>
Questions are randomly selected from an editable series of math questions in the script ("questions").
Participants indicate their answer to each question by clicking one of the available buttons (0 to 9).<br>
<br>
In the Task program, the difficulty of the task is manipulated to create mental stress by adjusting the time available to answer each question. <br>
The task starts with a time limit per question of 5 seconds which is displayed to participants through a timer bar.<br>
If three consecutive questions are answered correctly, the time limit is reduced by 10%. <br>
If three consecutive questions are answered incorrectly, the time limit is increased by 10%.<br>
A green-on-black performance bar is displayed to show the participant's average performance. The bar changes color to red if performance drops below 50%.<br>
The performance bar title text changes depending on performance values (below 25%, between 25-49%, between 50-79%, and 80% or above).<br>
After a specified amount of time, which can be easily adjusted in the program code, the program presents table of results showing the question, correct answer, answer given, whether the answer was correct/incorrect/timed-out, the response time (ms) and the allowed time (s) per question.<br>
These results are also automtically exported in a CSV file for easy import to Excel. File names include the participant number entered at the start of the session.<br>
<br>
In the Training program, the participant is presented with math questions but no performance or timer bar is presented and there is no time limit per question.<br>
The low-stress Training program should be presented to participants first, to familiarize them with the subsequent high-stress Task.<br>

## Getting Started

### Dependencies

The program runs in a browser window. Microsoft Edge is recommended.

### Installing

All files should be stored in the same folder. 

### Executing program

The separate programs can be run by opening the Training or Task html files.

## Help

CSV files generated when the Task session ends will automatically be downloaded to the same location as the Task program.

## Authors

Dr. Grant Benham <br>
https://orcid.org/0000-0002-5664-6025 <br>
https://scholar.google.com/citations?hl=en&user=OT4muuUAAAAJ <br>
https://stresslab.weebly.com <br>
grant.benham@utrgv.edu <br>


## Version History

* 1.0
    

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments


