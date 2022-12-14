# Plurality-Election
Implements a plurality voting algorithm to determine the winner of an election, as per the below.

>$ ./plurality Alice Bob Charlie
>Number of voters: 4
>Vote: Alice
>Vote: Bob
>Vote: Charlie
>Vote: Alice
>Alice

Completed in part of Harvard's [CS50 - Introduction to Computer Science, 2020](https://cs50.harvard.edu/x/2020/)
This was pset 3: [Plurality](https://cs50.harvard.edu/x/2020/psets/3/plurality/)

### Background
Elections come in all shapes and sizes. In the UK, the [Prime Minister](https://www.parliament.uk/about/how/elections-and-voting/general/) is officially appointed by the monarch, who generally chooses the leader of the political party that wins the most seats in the House of Commons. The United States uses a multi-step [Electoral College](https://www.archives.gov/electoral-college/about) process where citizens vote on how each state should allocate Electors who then elect the President.
Perhaps the simplest way to hold an election, though, is via a method commonly known as the “plurality vote” (also known as “first-past-the-post” or “winner take all”). In the plurality vote, every voter gets to vote for one candidate. At the end of the election, whichever candidate has the greatest number of votes is declared the winner of the election.

### Usage
>$ ./plurality Alice Bob Charlie
>Number of voters: 5
>Vote: Alice
>Vote: Charlie
>Vote: Bob
>Vote: Bob
>Vote: Alice
>Alice
>Bob
