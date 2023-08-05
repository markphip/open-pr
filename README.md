# open-pr

This is a simple Javascipt redirector deployed in GitHub Pages for opening a GitHub Pull Request
in Microsoft's CodeFlow review tool. The URL format would look like this:

https://markphip.github.io/open-pr/?codeflow=https://github.com/org/repos/pull/12345

This loads a simple HTML page with 2-lines of Javascript that will change to a URI that will
open the CodeFlow application, if installed. Chose this approach over a generic URI redirector.
If other tools like VS Code add URI support for opening a PR we can update the Javascript to
support more query params.

------
Credit to this repository: https://github.com/intradeus/http-protocol-redirector
