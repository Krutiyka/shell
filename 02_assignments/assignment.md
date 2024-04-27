## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `11:59 PM - 27/04/2024`
* The branch name for your repo should be: `assignment`
* What to submit for this assignment:
    * This markdown file (assignment.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/shell/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

# Assignment: The Secret Password

You are stuck in a virtual room and can only leave if you figure out the password! Fortunately, somebody left behind 6 clues for you to find the secret password, but the messaging is not that clear. It is your job to discover what the secret password is!

1. The very odd and inedible ingredient in a cake recipe
2. The season number that contains only 18 episodes (Hint: How do you list them?)
3. Fifth word of Season 6, Episode 21 of Friends
4. Fifth word of the fifth fictional Space Wars series
5. Second word of this song that's exactly 4 minutes long in this "colour" album
6. The fourth word to the fourth Hunger Games movie

## Instructions
1. Fork this Shell learning module repository following these [instructions](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#setting-up)
2. Use your bash skills (such as `cd`, `cat`, etc.) to figure out what the secret password is! You will be exploring the `clues` directory in your bash terminal.
3. Write the secret password in your own version of this markdown file in your forked repo.

**What is the secret password?**
```
Your answer here...
My answers:
1. Paper Rings
My commands:

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell (main)
$ ls
01_slides/  02_assignments/  03_homework/  04_instructional_team/  LICENSE  README.md  steps_to_ask_for_help.png

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell (main)
$ cd 02_assignments

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments (main)
$ ls
assignment.md  clues/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments (main)
$ cd clues

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (main)
$ ls
albums/  food/  movies/  shows/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (main)
$ cd food

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food (main)
$ ls
cake/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food (main)
$ cd cake

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food/cake (main)
$ ls
chocolate_cake.txt  red_velvet_cake.txt  vanilla_cake.txt

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food/cake (main)
$ cat chocolate_cake.txt
Milk
Cake Flour
Eggs
Cocoa Powder
Dark Chocolate
Baking Powder
Sugar
Vanilla Extract
Butter

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food/cake (main)
$ cat red_velvet_cake.txt
Baking Powder
Milk
Vanilla Extract
Red Food Colouring
Eggs
Cocoa Powder
Sugar
Butter
Cake Flour

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food/cake (main)
$ cat vanilla_cake.txt
Milk
Sugar
Baking Powder
Cake Flour
Eggs
Butter
Vanilla Extract
Paper Rings

My answer:
2. 10
iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food/cake (main)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/food (main)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (main)
$ ls
albums/  food/  movies/  shows/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (main)
$ cd shows

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows (main)
$ ls
friends/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows (main)
$ cd friends

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends (main)
$ ls
season_1/  season_10/  season_2/  season_3/  season_4/  season_5/  season_6/  season_7/  season_8/  season_9/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends (main)
$ ls season_10
ep_1.txt   ep_11.txt  ep_13.txt  ep_15.txt  ep_17.txt  ep_2.txt  ep_4.txt  ep_6.txt  ep_8.txt
ep_10.txt  ep_12.txt  ep_14.txt  ep_16.txt  ep_18.txt  ep_3.txt  ep_5.txt  ep_7.txt  ep_9.txt

My answer:
3. Meets
iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends (main)
$ ls season_6
ep_1.txt   ep_11.txt  ep_13.txt  ep_15.txt  ep_17.txt  ep_19.txt  ep_20.txt  ep_22.txt  ep_24.txt  ep_3.txt  ep_5.txt  ep_7.txt  ep_9.txt
ep_10.txt  ep_12.txt  ep_14.txt  ep_16.txt  ep_18.txt  ep_2.txt   ep_21.txt  ep_23.txt  ep_25.txt  ep_4.txt  ep_6.txt  ep_8.txt

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends (assignment)
$ cd season_6

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends/season_6 (assignment)
$ cat ep_21.txt
The One Where Ross Meets Elizabeth's Dad

My answer:
4. and
iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends/season_6 (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends (assignment)
$ cd .

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows/friends (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/shows (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ ls clues
ls: cannot access 'clues': No such file or directory

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ cd movies

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies (assignment)
$ ls
hanger_games/  space_wars/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies (assignment)
$ cd space_wars

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies/space_wars (assignment)
$ ls
fifth_movie.txt  first_movie.txt  fourth_movie.txt  second_movie.txt  third_movie.txt

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies/space_wars (assignment)
$ cat fifth_movie.txt
Space Wars: Future Legends and Past Legacies

My answer:
5. Lucky
iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies/space_wars (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ cd albums

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums (assignment)
$ ls
fearless/  lover/  red/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums (assignment)
$ cd red

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ ls
song_1.txt  song_2.txt  song_3.txt  song_4.txt  song_5.txt

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ cat song_1.txt
Title: Red
Duration: 3:43

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ cat song_2.txt
Title: I Knew You Were Trouble
Duration: 3:39

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ cat song_3.txt
Title: Everything Has Changed
Duration: 4:05

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ cat song_4.txt
Title: Holy Ground
Duration: 3:22

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ cat song_5.txt
Title: The Lucky One
Duration: 4:00

My answer:
6. Stars

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums/red (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/albums (assignment)
$ cd ..

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues (assignment)
$ cd movies

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies (assignment)
$ ls
hanger_games/  space_wars/

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies (assignment)
$ cd hanger_games

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies/hanger_games (assignment)
$ ls
movie_1.txt  movie_2.txt  movie_3.txt  movie_4.txt

iryna@LAPTOP-OMLS5BNV MINGW64 ~/Desktop/shell/02_assignments/clues/movies/hanger_games (assignment)
$ cat movie_4.txt
Hanger Games & the Stars of Darkness```




```

|Criteria|Complete|Incomplete|
|---|---|---|
|Secret Password|The user properly used the proper bash commands to find the secret password.|The user did not properly used the proper bash commands to find the secret password.|



If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
