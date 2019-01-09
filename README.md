# coverletissuedemo
Coverlet Shoudly issue

To reproduce the issue.

First try running the test with "dotnet test", It will pass. but when you use coverlet "dotnet test /p:CollectCoverage=true ", It fails as shoudly needs full debug information which it could not find.
