# chessh - chess over ssh

chessh is a goofy little project to play chess over ssh. It started as a shower
thought by [Nate Choe](https://natechoe.dev/) and got actually implemented
around a year later.

chessh is always stylized in all lowercase, even at the beginning of sentences.
The rest of a document, however, is not necessarily so.

chessh uses a microservice based architecture, made up of several components:

* [chessh-backend](https://github.com/chessh-org/chessh-backend) - implements
  chess and the chessh API
* [chessh-bindings](https://github.com/chessh-org/chessh-bindings) - bindings
  for the chessh API
* [chessh-terminal](https://github.com/chessh-org/chessh-terminal) - a terminal
  interface to chessh, can be used by itself or in conjunction with an SSH
  daemon.

chessh is in a **VERY** early state, you cannot host chessh with just these
repositories.
