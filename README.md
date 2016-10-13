# Automatic Help-Seeking Faciliator of Computer Science students

This repo served for the Comprehensive Examination Project of Neo Hao: http://home.tobeneo.com/Comprehensive-Intro/

## Prototype of the tools facilitating online help seeking

The prototype aims at visualizing the top-down thinking process of experts in solving practical problems. Novices students can see how a big program is broken down to approachable pieces, and follow the provided links to queries targeting decontextualized small problems.

Three samples are used to illustrate the idea of the tool. Complete problem description and answers to the three sample problems can be found at https://github.com/Neo-Hao/Comprehensive-Exam

### Functional Interfaces for students

The core of the interfaces for students is the presentation of problem breakdown. The interface composes of two sections: problem breakdown and code structure.

Problem breakdown includes a list of tasks and their subtasks as the solution to the problem. There can be as many levels of subtasks for each task. Every task/subtask can have its own links to a search query and a code snippet

Code structure corresponds to the tasks/subtasks of different levels. As different level of subtasks are requested to show up or hide, the code structure change accordingly.

This tool can be embedded in a learning managment system, or be used to facilitate instruction in large-scale classes.

Three samples are developed to illustrate the ideas:

* http://home.tobeneo.com/Comprehensive-Sample1/
* http://home.tobeneo.com/Comprehensive-Sample2/
* http://home.tobeneo.com/Comprehensive-Sample3/

### Functional Interfaces for Teachers

The interfaces for teachers allow teachers to input all the information that will be presented to students, as are shown in the three samples.

The core interface is Input for Sub Tasks. This tool allows teachers to input tasks and related links to queries and code snippets, and give structure to tasks. This tool always mainstains accessibility to the database.

A whole set of developed interfaces can be accessed:

* Problem Statement: http://home.tobeneo.com/Comprehensive-Problem-Statement/
* Sub tasks: http://home.tobeneo.com/Comprehensive-List-Tasks/
* Code structure input: http://home.tobeneo.com/Comprehensive-Input-Code/
