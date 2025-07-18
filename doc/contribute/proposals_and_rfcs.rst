.. _rfcs:

Proposals and RFCs
##################

Many changes, including bug fixes and documentation improvements can be
implemented and reviewed via the normal GitHub pull request workflow.

Many changes however are "substantial" and need to go through a
design process and produce a consensus among the project stakeholders.

The "RFC" (request for comments) process is intended to provide a consistent and
controlled path for new features to enter the project.

Contributors and project stakeholders should consider using this process if
they intend to make "substantial" changes to Zephyr or its documentation. Some
examples that would benefit from an RFC are:

- A new feature that creates new API surface area, and would require a feature
  flag if introduced.
- The modification of an existing stable API.
- The removal of features that already shipped as part of Zephyr.
- The introduction of new idiomatic usage or conventions, even if they do not
  include code changes to Zephyr itself.

The RFC process is a great opportunity to get more eyeballs on proposals coming
from contributors before it becomes a part of Zephyr. Quite often, even
proposals that seem "obvious" can be significantly improved once a wider group
of interested people have a chance to weigh in.

The RFC process can also be helpful to encourage discussions about a proposed
feature as it is being designed, and incorporate important constraints into the
design while it's easier to change, before the design has been fully
implemented.

For a Major Feature, first open an issue and outline your proposal so that it
can be discussed. This will also allow us to better coordinate our efforts,
prevent duplication of work, and help you to craft the change so that it is
successfully accepted into the project. Providing the following information
will increase the chances of your issue being dealt with quickly:

  * Overview of the Proposal
  * Motivation for or Use Case
  * Design Details
  * Alternatives
  * Test Strategy

Some changes or contributions do not require an RFC, the rationale and details
of the changes should however be part of the pull-request:

- Small enhancements and modifications to existing and established subsystems.
- Rephrasing, reorganizing or refactoring
- Addition or removal of warnings
- Addition of new boards, SoCs or drivers to existing subsystems
- ...

The process in itself consists in creating a GitHub issue with the :ref:`RFC
label <gh_labels>` that documents the proposal thoroughly. You are encouraged
to use the `RFC form`_ to make sure the proposal follows a template which
project participants are already familiar with.

As with Pull Requests, RFCs might require discussion in the context of one of
the `Zephyr meetings`_ in order to move it forward in cases where there is
either disagreement or not enough voiced opinions in order to proceed. Make sure
to either label it appropriately or include it in the corresponding GitHub
project in order for it to be examined during the next meeting.

.. _`RFC form`: https://github.com/zephyrproject-rtos/zephyr/issues/new?template=003_rfc-proposal.yml
.. _`Zephyr meetings`: https://github.com/zephyrproject-rtos/zephyr/wiki/Zephyr-Committee-and-Working-Groups
