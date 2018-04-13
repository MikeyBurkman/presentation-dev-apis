@title[Cover]

## Unexpected Server Error! 
## See Admin2

<br />

APIs are User Interfaces, too!
<br>
<span class="byline">Don't forget who your users are</span>

---

@title[Intro]

#### Who is your audience?
@ul
- Might be another developer
- Might barely classify as a developer
- Might be yourself, 6 months from now
- Regardless, they want to get accomplish their task, with little pain
@ulend

---

@title[InitialReactions]

#### Think about initial reactions
@ul
- Is it documented at all? 
    - Example inputs and outputs?
- Do you require seemingly-unnecessary data?
- Do you use **consistent** naming conventions?
    - If you call it `userID` in one place, don't call it `userId` in another
    - Don't mix `camelCase` and `underscore_case`
    - Use the same date string format everywhere
@ulend

---

@title[ThingsBreak]

#### Things will go wrong
Even with perfect documentation, things will go wrong
@ul
- Do you document how errors are returned?
- Do you use the accepted standards for your platform?
    - HTTP status codes, exit codes, etc

- Are your error codes and messages *helpful*?
    - Can they help the user resolve the problem?
    - Can they help YOU resolve the problem?
@ulend

<span class="byline">Think back to your own frustrations</span>

---

@title[UsabilityTesting]

#### Usability Testing
It's not much different than for a GUI
@ul
- Ask someone else to use it, _without_ your help
- Explain your API to someone. Have them play dumb.
- Use your API yourself
    - Eat your own dog food
    - Note where YOU make mistakes
@ulend

---

@title[ThingsBreakMore]

#### Remember Failure Scenarios
Try purposely doing things wrong, and look at the error messages
@ul
- Leave out required fields
- Make fields the wrong type
- Purposely misspell words
@ulend

If you get unhelpful errors (or no errors at all), then you have work to do

<span class="byline">Remember all the times you got unhelpful errors while coding!</span>

---

@title[CompilerExamples]
#### Compilers are user interfaces too!


![Java](javaError.png)
![Typescript](typescriptError.png)

