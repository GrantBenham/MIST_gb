# MIST_gb

The MIST_gb program is two HTML/Javascript programs (one for Training, the other for the Task) used to induce acute psychological stress for research studies.

## Description

The program is modeled off a protocol developed by Katarina Dedovic et al. (2005), the Montreal Imaging Stress Task (MIST), which was itself derived from the Trier Mental Challenge Test.
The MIST_gb Task consists of a series of mental arithmetic questions 

In the Task program, the difficulty of the task is manipulated to create mental stress by adjusting the time available to answer each question. 
The task starts with a time limit per question of 5 seconds which is displayed to participants through a timer bar.
If three consecutive questions are answered correctly, the time limit is reduced by 10%. 
If three consecutive questions are answered incorrectly, the time limit is increased by 10%.
A green-on-black performance bar is displayed to show the participant's average performance. The bar changes color to red if performance drops below 50% and a message is displayed prompting the participant to "Try Harder".
After a specified amount of time, which can be easily adjusted in the program code, the program presents table of results showing the question, correct answer, answer given, whether the answer was correct/incorrect/timed-out, the response time (ms) and the allowed time (s) per question.
These results are also automtically exported in a CSV file for easy import to Excel. File names include the participant number entered at the start of the session.

In the Training program, the participant is presented with math questions but no performance or timer bar is presented and there is no time limit per question.

a series of mental arithmetic tasks are displayed on the computer screen, and subjects submit their answers by means of a response interface. 



## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
