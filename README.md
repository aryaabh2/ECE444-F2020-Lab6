# ECE444-F2020-Lab6


**Deliverable 1: Replay the example
https://github.com/mjhea0/flaskr-tdd (5 points)**

DONE - see commits and code in this repo, also deployed to heroku for fun:)

**Deliverable 2: Add atleast 1 unit test to group project (3 points)**

https://github.com/ECE444-2020Fall/project1-webapp-group15-teambits/blob/abhi_ece444lab_week67/backend/tests/app_test.py#L11-L23

**Deliverable 3: What are the pros and cons of TDD (2 points)**

TDD = Test driven development
What it is: you write tests before writing code and then you write code to pass those tests and then you write more tests and the cycle continues.

PROS:
- Architecture can be enforced easily.
- Ensures modular code since each small portion of it will be made to be unit testable
- Helps avoid defective code
- Requirements become crystal clear to the programmers
- Makes refactoring code easier since every change can be easily tested during development
- Acts as documentations for code. One can view the tests and understand what each functions/modules end to end behavior is.
- Since modules have their end to end behaviors tested well, integration errors are reduced as well.
- Makes working on group projects easier, since you can be confident your team’s and your code meets the test standards.
- Speeds up development in long term

CONS:
- Sometimes it is hard to test end to end behaviors (for example in Graphics card drivers unit tests do not capture much of the behavior well (from my experience at AMD))
- Needs to be maintained, big overhead for programmers.
- If entire team does not agree with TDD, the process will fail and fall apart.
- Refactoring existing code to start doing TDD in the future is a big task many teams choose not to do
- It may too too much time overhead for some projects, may slow down development in some cases.
- Slows down development in short run
- Hard to keep up with rapidly changing designs

Thus, we need to carefully consider if TDD is a good fit for a project and stack. 



