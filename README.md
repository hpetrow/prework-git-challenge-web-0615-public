---
tags: prework, git
languages: ruby
---

# Prework Git Challenge

We're going to review what we just learned in the previous lesson on git.

## Directions

1. Fork this repository, clone that fork, and open up the directory in terminal.

2. Open up the file in the `spec` directory called `git_challenge_spec.rb`. This is our RSpec file where the tests for this challenge live. You'll be inputting your answers on this file.

3. Within each test, you'll see something like this:

```ruby
your_answer = __
```

Replace the __ with your answer in quotes, like this `"git clone"`. If you need to use quotes within your answer, you can nest single quotes inside of double quotes OR double quotes inside of single quotes. See below:

```ruby
# double inside of single
your_answer = 'Then she said, "Sounds like a plan!"'

# single inside of double
your_answer = "Then she said, 'Sounds like a plan!'"
```

The test will be looking at your answer and comparing it to the correct answer.

4. When you've finished answering all of the questions, run `learn` (which will be running the tests; remember this is in leiu of running `rspec`) and make sure you're seeing all green.

5. When you're finished (all of the tests pass and you're seeing green in your terminal), put your git skills to use!
* Stage the changes you made: `git add .`
* Commit those changes with a message: `git commit -m "all done"`
* Push those changed up to your fork: `git push origin master`
* Then open up a pull request on the original repository (that you cloned from).

Refer back to the previous sections, especially the first lab, if you need to.
