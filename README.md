# My Github Desktop Commit Workflow

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fjdevstatic%2Fmy-github-desktop-commit-workflow&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=PAGE+VIEWS&edge_flat=false)](https://github.com/jdevstatic)

I have my personal commit workflow using GitHub Desktop.
The catch is that I'm not installing Git. 

You don't need Git to use GitHub Desktop.
But you need a technique for you to have your commits as
**verified**.

I'm actually into branches because I feel
I can group my commits into related features 
or bug fixes.

My pattern of naming is the `date` and 
the `count commit` which I call `sprint`,

this is an example of my branches in a day

`december12-sprint1`, `december12-sprint2`, 
`december12-sprint3`

I can easily remember the things that happened 
there.

I call it `sprint` because one, it's the term being used
in Agile and two, it is a continuous effort sitting
in front of the computer coding without long breaks, 
much like a real sprint, because that's the
nature of coding in itself, or else you will be
distracted by lot of things and your train of thought
would be gone from time to time.

I'm using this not only in my personal projects
but also in my company's projects.

## Steps
1. I always fetch and pull it.

2. Then start coding.

3. When it's time to commit it, I don't
commit it on the default branch.
I'll make a branch instead and bring the 
changes to it, so there will be no 
new commits left on the default branch.

4. My way of naming new branches is 
the date and the count of the commit
like `december12-sprint1`.
I already explained this above.

5. I usually will get the `commit summary` by 
using the `tab` key but if I need to make 
a very important summary I will manually do so.

6. Once it is committed, I will publish the branch.
This is an unverified commit on GitHub.
Then the branch will pop up on GitHub. I'll review 
it and make a PR then merge. This is a verified
commit now. This is clean actually. When it's not 
working at the production setup, I can always
revert it on GitHub.

7. I will switch to master leaving the changes on that
branch. Then I will fetch again and pull those recent
changes. Done. I now have the synced local project. 
I start the next task.

## GitHub Desktop Workflow Summary
fetch -> pull -> make changes -> create branch -> switch branch
-> commit changes to that branch -> publish branch on GitHub
-> make PR -> merge ( can `revert` when needed) -> switch branch
to default -> leave changes on the branch -> fetch -> pull 
