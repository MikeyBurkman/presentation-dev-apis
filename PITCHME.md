@title[Introduction]

## Unexpected Server Error! 
## See Admin2

<br />

#### APIs are User Interfaces, too!
<br>
<span class="byline">Don't forget who your users are</span>

---

@title[Intro2]

#### Who is your audience
- Sometimes that user is another developer
- Sometimes that user barely classifies as a developer
- Sometimes that user is yourself, 6 months from now
- Regardless, they want to get their task done, with little pain

---

@title[FirstSteps]

#### Think about initial reactions by users
- Is it documented at all? 
    - Example inputs and outputs?
- Do you require seemingly-unnecessary data?
- Do you use **consistent** naming conventions?
    - If you call it `userID` in one place, don't call it `userId` in another
    - Don't mix `camelCase` and `underscore_case`
    - Don't use both ISO8061 strings and Unix timestamps -- pick one

---

#### Things will go wrong
Even with perfect documentation, things will go wrong

- Do you document how errors are returned?
- Do you use the accepted standards for your platform?
    - HTTP status codes, exit codes, etc
- Are your error codes and messages **helpful**?
    - Can they help the user resolve the problem?
    - Can they help YOU resolve the problem?

<span class="byline">Think back to your own frustrations</span>

---

@title[WhatNext]

#### Usability Testing
It's not much different than for a GUI
- If possible, ask someone to try and use it, WITHOUT your help
- Try to explain your API to someone. Have them play dumb
- Try to use your API yourself
    - Eat your own dog food
    - Note where YOU make mistakes

---

#### Remember Failure Scenarios
- Do some fuzz testing
    - Basically the equivalent of mashing the keyboard
- Try purposely doing things wrong, and see what the error messages are like
    - Leave out required fields
    - Make fields the wrong type
    - Purposely misspell words

If you get unhelpful errors (or no errors at all), then you have work to do

<span class="byline">Remember all the times you got unhelpful errors while coding!</span>

---

@title[CompilerExamples]
#### Compilers are user interfaces too!
- Give them code -> error messages

![Typescript](typescriptError.png)
![Hava](javaError.png)
