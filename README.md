# cde2025.4-warnet
Assignment 4 of the Cryptocurrency Design and Engineering course will involve a variation of the [Bitcoin Dev Project’s](https://bitcoindevs.xyz) [Warnet](https://github.com/bitcoin-dev-project/warnet) project. This project simulates a Bitcoin network that allows users to test and study the network’s functionality. In this assignment, you will utilize this simulated network and the Python-based Bitcoin test framework to develop attacks against the network. The culmination of this assignment will be a 48-hour live competition against your fellow students.

# Warnet
The specific scenario that you will be competing in is called [The Battle of Galen Erso](https://github.com/bitcoin-dev-project/battle-of-galen-erso)
 
### Team Component
This event is designed to be a team-based activity, and participants must form teams of three to six individuals. If you have not formed a team by November 10th and intend to participate in the live event, please contact your course facilitators. They will assign a team to you. Upon accepting the assignment in Git Classroom, you will be prompted to form or join a team. If you inadvertently join or create the incorrect team, the administrators of your Git Classroom can modify the assignment after the fact.

### Expected submissions
Students are encouraged to submit the attacks they develop through Git Classroom. However, grading for the assignment will be based on each team’s progress during the live event. Each team is expected to eliminate at least six nodes to receive full credit, with partial credit awarded proportionally to the number of nodes eliminated. The assessed grade will be based on the team’s performance.

---

# Part 1: Local Planning Phase
The comprehensive instructions for the installation and utilization of the program are available at [The Battle of Galen Erso](https://github.com/bitcoin-dev-project/battle-of-galen-erso).

During this phase, students are required to download the warnet software and execute it locally to develop the software that will be deployed during the live event for credit. The provided instructions include a pre-developed attack scenario titled `my_first_attack_5kinv.py`, which can be utilized to disable one of the nodes employing a simulated vulnerabilitiy

To test this attack locally, students can execute the `regtest_small` battlefield. Given that this battlefield will only deploy two nodes, and students must disable six to obtain full credit, it is advisable to modify `regtest_small`’s files to deploy various types of nodes and compile a catalog of attacks. A fictitious development website that compiles all the genuine and simulated vulnerabilities has been established, known as [BitCornCore](https://bitcorncore.org/en/about/). This website will be instrumental in the development of your attacks.

All attacks on nodes can be developed during this stage, and it is strongly recommended that every team develop and test all their attacks prior to the live event. 



# Part 2: Online Event Phase

The online event will take place from November 13th to 14th. Where teams will be assigned a color, such as red, blue, etc. Upon assignment, teams will gain access to a set of resource nodes (armada) and will be tasked with deploying the scenarios developed during the planning phase to eliminate the nodes (tanks) associated with their team’s color. Each team’s progress will be monitored through the Warnet leaderboard, which can be accessed by executing the command `warnet dashboard`.

