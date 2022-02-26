# Lab2 Report - bug fixing

## Three code changes:
1. code1

![code1](https://user-images.githubusercontent.com/97651152/151650232-53f937e6-31e6-4d10-97e1-7392eb353312.png)

*Link to test file*

[code1](https://github.com/PiaoX/markdown-parse/commit/72bd27e7d0e14c304495e2b582fd86364d0f128f)

*Failure Output:*

![code1](https://user-images.githubusercontent.com/97651152/151650371-5e8e43c7-cc85-42ac-8ff8-6744f75d83f8.png)

*Description:*

There's an error that an infinite loop occures for a test file, because there was texts after the closed parenthesis. We added a line in the code to avoid this error.

2. code2

![code2](https://user-images.githubusercontent.com/97651152/151647934-71a3b073-61b7-4d6f-8641-dcf10ab00de3.png)

*Link to test file*

[code2](https://github.com/PiaoX/markdown-parse/commit/2e21973b9c795cfe4b586ab1b0429c09d3f54693)

*Failure Output:*

![code2](https://user-images.githubusercontent.com/97651152/151647822-413ddf78-d51e-434e-a277-17aaf281124f.png)

*Description:*

The first link is not valid because of the extra parenthesis, so the output of the link is cut before the extra parenthesis. The changes I made is to delete the parenthesis, which gives a correct output.


3. code3

![code3](https://user-images.githubusercontent.com/97651152/151647702-e584cf20-ceb8-4edd-828d-53c7a88d779e.png)

*Link to test file*

[code3](https://github.com/PiaoX/markdown-parse/commit/72bd27e7d0e14c304495e2b582fd86364d0f128f)

*Failure Output:*

![code3](https://user-images.githubusercontent.com/97651152/151650833-18687817-1a41-4e0e-bed8-d759b86c1861.png)


*Description:*

There're errors in the code about the uppercase lowercase, which is easy to make it wrong. What we do is to fix the cases by the prompt.
