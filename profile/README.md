# AiChaos GitHub

This is the home of the RiveScript chatbot scripting language and other related chatbot projects.

See the RiveScript website at https://www.rivescript.com/

Some notable repositories in this organization include:

## RiveScript Interpreter Libraries

These will enable you to build your own custom chatbot from scratch that uses RiveScript as its A.I. engine.
There are implementations available in several programming languages:

* **Go:** [rivescript-go](https://github.com/aichaos/rivescript-go)
* **Java:** [rivescript-java](https://github.com/aichaos/rivescript-java)
* **JavaScript:** [rivescript-js](https://github.com/aichaos/rivescript-js)
* **Perl:** [rivescript-perl](https://github.com/aichaos/rivescript-perl)
* **Python:** [rivescript-python](https://github.com/aichaos/rivescript-python)

There is also a **very much work-in-progress** official port for Rust: [rivescript-rs](https://github.com/aichaos/rivescript-rs).

Outside of the AiChaos organization, there are a couple of third-party implementations of RiveScript in more languages:

* **PHP:** https://github.com/axiom-labs/rivescript-php (at least 80% feature complete)
* **C#:** https://github.com/fabioravila/rivescript-csharp (progress unknown)

## The RiveScript Language Itself

See the [RiveScript Working Draft](https://github.com/aichaos/rivescript-wd) for the language specification. This
will be a crucial resource if you want to try and develop your own RiveScript interpreter from scratch!

Also see the [RiveScript Test Suite (RSTS)](https://github.com/aichaos/rsts), a unified set of tests that the
official implementations run against. If your custom interpreter passes these tests, you know your implementation
is _at least_ as correct as the official ones!

## Other Goodies

* [Aiden](https://github.com/aichaos/aiden) is a reference RiveScript chatbot personality (collection
  of `*.rive` files you can use with a RiveScript bot).
* There is [aiml2rs](https://github.com/aichaos/aiml2rs), scripts that can translate
  [A.L.I.C.E.](https://en.wikipedia.org/wiki/Artificial_Linguistic_Internet_Computer_Entity)
  [AIML](https://en.wikipedia.org/wiki/Artificial_Intelligence_Markup_Language) code into RiveScript,
  and back again! It may be useful to port an existing Alicebot brain over to RiveScript.
* There are a few full chatbot applications: [Scarecrow](https://github.com/aichaos/scarecrow) (Go,
  supporting Slack & XMPP), [Admiral](https://github.com/aichaos/admiral) (Python, for Slack bots),
  and [Aires](https://github.com/aichaos/aires) (Python, supporting XMPP and the now-defunct AOL
  Instant Messenger OSCAR protocol)
