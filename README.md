NEAR Sandbox: demo & visioning
==============================

Getting internal feedback to help guide development of NEAR Sandbox, near-test-runner, and related tools.

The slides, contained in `index.html`, are built using [remarkjs](https://github.com/gnab/remark), which allows you to write your slides in nice simple markdown and turns them into beautiful, browser-powered slides complete with speaker notes. Read its readme to find out more about it.

There's lots of custom styling on the slides, found at the top of the `index.html` file.


Talk Description
================

* What is NEAR Sandbox today? (https://github.com/near/nearcore/blob/624a3bc621ebb76b9a8e6d718cb92a30590ddfb0/Makefile#L67-L69)
* Who is it for?
* Why are we building it?
* What problems are we solving?
  1. local dev environment bundle (currently `near-sandbox` package; needs more than just nearcore though)
  2. contract tests (currently `near-test-runner` package; replaces simulation tests)
  3. e2e tests (could build on future versions of both former libraries; need to support full app automation "user signs into app via NEAR Wallet," etc)
* Demo of `near-test-runner` interface so far
  * Comparison to old rust-status-message tests
  * Comparison to create-near-app
  * Other comparisons?
* Naming the "contract testing" library. Possibilities:
  * `near-contract-testing`
  * `near-test-environment`
  * `near-test-env`
