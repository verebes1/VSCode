#### Debugging Cucumber steps in VSCode

To add easy debugging of Cucumber steps into your project see the Gemfile for required gems. The most important one to add is the `debug` gem. You will also need to add the `.vscode` folder to your project which includes the launch configurations for debugging the Cucumber scenarios and also the task that stops cucumber after you finished debugging.

First time setup

1. Install the gems using:

   * `bundle install`

2. Install the following extensions in VSCode:

   * Ruby LSP  <-- This one is a must for debugging to work others are optional but good for dev experience
   * Ruby Solargraph
   * Cucumber
   * Cucumber (Gherkin) Full Support
   * Gherkin Indent

That's it now you are ready to set breakpoints in the ruby code of the steps and use the debugger within VSCode.
You have 3 main options to use with Cucumber:

* Cucumber
* Cucumber current feature file
* Cucumber scenario under cursor
