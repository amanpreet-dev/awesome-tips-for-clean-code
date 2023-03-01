# **Awesome tips for Clean Code**

## Clean Namings:

1. Use intention-revealing namings
2. Capture business knowledge
3. Avoid encoding and technical details
4. Use pronounceable names
5. Use searchable names
6. Avoid noise and redundant words
7. Use strong words
8. Don't use abbreviations
9. Be consistent with concepts and use the same vocabulary
10. Use is/has/should/can prefix for booleans
11. Avoid negative names for booleans
12. Use naming conventions within your project
13. Boolean name should be an adjective
14. Class names should be noun or noun-phrases

## Clean Functions:

15. Function names should be verb or verb-phrase
16. Keep a function small and concise
17. Avoid too many function arguments
18. Max number of lines of a function should be 8-10
19. Avoid passing boolean as a function parameter
20. Strive for no side effects.
21. Use enums as flags
22. Use empty lines to separate logic
23. If it takes more than 3 seconds to figure out what a function does, then refactor it

## Clean Classes:

24. Should have only one main responsibility
25. Avoid large classes (~100 lines of code can be a smell)
26. Strive for one public function per class
27. Create small private functions to do single tasks
28. Order your functions based on execution

## Clean Comments:

29. Avoid comments as much as possible
30. Don't state the obvious
31. Don't use them extensively because nobody will read them
32. Replace them with good namings of your software elements
33. Use comments only for explaining the why
34. Use comments for revealing implicit behavior
35. Use comments for API doc generation

## Clean Tests:

36. Use descriptive tests names describing the test scenario
37. Use GivenWhenThen or ShouldWhen naming templates
38. Use Arrange/Act/Assert pattern to structure tests
39. Avoid logic (if, for, and while loops) in test code
40. Couple a test with one behavior
41. Use meaningful test data
42. Hide irrelevant test data
43. Use clean assertions, describing the domain behaviors
44. Create deterministic tests
45. Remove duplication with parameterized tests
46. Prefer fakes for mocking out 3rd party code

## A test should follow the **F.I.R.S.T** principle:

47. should be fast
48. should be independent of other tests
49. should be repeatable
50. should be self-validating
51. should be thorough cover covering all happy paths, edge cases, negative cases, security, and illegal issues

## Git commits:

52. Commit early & push often
53. Make your commit messages meaningful, explaining the reason for the change.
54. Use the imperative mood in the commit message
55. Use present tense in the commit message
56. Add link reference to the actual user story, task or bug

## Code smells:

57. Avoid magic numbers
58. Avoid magic strings
59. Avoid long conditions
60. Avoid global variables
61. Avoid long parameter list
62. Don't be obsessed with primitives. Model your domain with complex types.
63. Avoid deeply nested logic
64. Reduce cyclomatic complexity
65. Hard-to-test logic is a code smell to fix

## Formatting:

66. Set up team standards
67. Use automated code formatters
68. Set max width for horizontal formatting
69. Don’t use horizontal alignment.
70. Don't break indentation
71. Variables should be declared close to their usage

## Principles:

72. Don't repeat yourself (**DRY**): remove knowledge duplication
73. Keep it simple (**KISS**): simple code beats both complex and clever code
74. You ain't gonna need it (**YAGNI**): don't produce code that is not needed in your current context
75. Tell, don't ask: bundle data and functions together
76. Single Responsibility Principle (**SRP**): organize logic into modules with one reason to change
77. Liskov Substitution Principle (**LSP**): a subtype should be able to replace its base type without altering the program
78. Interface Segregation Principle (**ISP**): split large interfaces into small and more specific ones
79. Dependency Inversion Principle (**DIP**): high-level modules should not depend on low-level modules. Both should depend on abstractions.
80. Favor composition over inheritance: inheritance leads to tight coupling, composition gives more flexibility
81. Divide and Conquer: break down a problem into smaller sizes to manage complexity
82. High cohesion: group related code together. It helps you to find logic easier and makes your code easy to maintain
83. Low coupling: your modules should independent of other modules. By doing so, you can easier make changes to internals without breaking other modules

## Extra tips:

84. Use a solid IDE with refactoring functionalities
85. Master your IDE hot keys
86. Use feature based folder structure
87. Work with pair programming, it makes writing clean code easier
88. Delete non used code - code is a liability, not an asset
89. Write code humans to read, and not just for machines to execute
90. Readability > cleverness
91. Favor readability over efficiency
92. Always leave the code a better place behind
93. Test early, test often
94. Refactor early, refactor often
95. Do code reviews in real-time instead of PR reviews
96. Use the rule of three to remove duplications
97. Avoid using `NULL`, it is a code smell
98. Working code != clean code
99. You can't have clean code without tests
100.  Write code that reads like a well-written prose

### Source of Reference -

- [Source](https://twitter.com/dmokafa/status/1630615034865893376)
