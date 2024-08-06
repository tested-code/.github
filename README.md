# Tested.code

[Tested](https://github.com/tested-code) is a testing toolkit that aims to make testing less verbose, more natural to write, and safer

# Goals
## Learn once, use everywhere
as i work with a wide variety of languages, frameworks and codebases, deciding which testing library to use and understanding their design philosophy is quite tiresome. with this toolkit, you can learn once and not leave your comfort behind when you work with a different language.

## dont think about inputs
i often miss edge cases (could be skill issue, or i could be too lazy or distracted at work, my personal bais sometimes). i dont want to think about what input could break a unit when i dont need to. this toolkit auto generates and runs our tests and fills inputs with pseudo-random inputs. the inputs are controlled. for example, the same input combination will not be repeated, and each input will be vastly different from its neighbour.
