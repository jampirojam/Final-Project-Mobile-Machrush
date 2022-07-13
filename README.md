# Final-Project-Mobile-Machrush

## Test Application Using Partition or Separated Item
This test is about partition test case item or feature in application then test running on a Test Suites feature, so the successfull test based on a Test Suite not Test Case.

## Environtment Test
<ol>
    <li>Katalon Studio</li>
    <li>Bank Demo.apk</li>
    <li>Xiaomi Redmi 9 (Real Device)</li>
</ol>

## Result
When use partition testing, separated object repository in Mobile Testing its really important, cause when testing in a single object repository and run in Test Case not Test Suite, the test not execute well.

So, if wanna use separated test, should to specify tag or mark-up. This things its really helpful in execution. 
 
## Problem
Mobile.verifyElementExist in conditional statement. When, I do test to execution a statement while another statement is false, this running for along time, and while I set the timeout for checking, shown failed.