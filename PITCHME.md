@title[Introduction]

# Unexpected Server Error! See Admin2

#### APIs are UIs, too!
<br>
<br>
<span class="byline">Or, never forget who your users are</span>

---

@title[Intro2]

#### APIs are User Interfaces
- Sometimes that user is another developer
- Sometimes that user is yourself, 6 months from now
- That user likely has a different skill level than you do now

---

@title[FirstSteps]

#### Think about how someone will use it for the first time
- Is it documented at all?
- Do you require seemingly-unnecessary data?
- Do you use **consistent** naming conventions?

#### What about things going wrong?
- Do you document how errors are returned?
- Do you use the accepted standards for your platform? (HTTP status codes, exit codes, etc)
- Are your error messages **helpful**?

---

@title[WhatNext]

## How?
#### Just like when writing a GUI, the best way is by testing with trusted users
- Try to explain your API to someone
- Ask someone to try and use it, WITHOUT your help

#### Try to create errors!
- Do some fuzz testing -- basically the equivalent of mashing the keyboard
- Try purposely doing things wrong, and see what the error messages are like
- Leave out required fields, make fields the wrong type, purposely misspell words

If you get unhelpful errors (or no errors at all), then you have work to do

#### Remember all the times you got unhelpful errors while coding!

---

@title[CompilerExamples]
#### Compilers are user interfaces too!
- You enter some text, they spit back any errors they encounter
- A good compiler will give you errors that are informative

![Typescript](typescriptError.png)
![Hava](javaError.png)
