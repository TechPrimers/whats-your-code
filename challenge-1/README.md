# Challenge 1 - CricAnalytics

# Table of Contents
- [Problem Statement](#problem-statement)
    - [Assumptions](#assumptions)
    - [Things to consider](#things-to-consider)
- [Solutions from Community](#solutions-from-community)

# Problem Statement
You are the developer of `CricAnalytics`, an online cricket portal which provides cricket enthusiasts with cricket score, analytics, etc,.
New features need to be implemented to provide statistics as much efficiently as possible to find - 
- How many sixes were hit in total in each innings?
- How many fours were hit in total in each innings?
- How many players scored 0 in each innings?
- How many players were bowled out in each innings?
- Who scored the maximum number of 4's and 6's in each innings?

`Sample ScoreBoard Dataset looks like: `
```
ScoreBoard {
    Innings1 {
       player1 {
         score: 101,
         out: true, 
         sixes: 4,
         fours: 12,
         bowled: true
        },
        player2 {
         score: 0,
         out: true, 
         sixes: 0,
         fours: 0
        },
        player3 {
         score: 32,
         out: true, 
         sixes: 0,
         fours: 4,
         bowled: true
        }
        ...
    }
    Innings2 {
       player1 {
         score: 1,
         out: true, 
         sixes: 0,
         fours: 0
        },
        player2 {
         score: 8,
         out: true, 
         sixes: 0,
         fours: 1,
         bowled: true
        },
        player3 {
         score: 90,
         out: true, 
         sixes: 1,
         fours: 8
        }
        ...
    }
}
```

## Assumptions
- Create your own dataset using the above sample dataset.
- You are going to use Design Patterns and Clean coding standards to create a production like code.

## Things to consider
- You can use any Java 8+ version or Python 3+.

# Solutions from Community
Name      |   Solution      | Comments 
----      | ----            | ----
