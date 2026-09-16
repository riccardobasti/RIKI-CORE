# RIKI-CORE
byte dev
RIKI CORE

RIKI CORE is a minimal core for defining a canonical Space based on a small set of permanent principles:

BYTE — one unique and permanent canonical identity.

VALUE — the permanent dynamic value associated with a BYTE.

BIT — a validity state derived from the truth of the connected CHAINS.

CHAINS — permanent mathematical equalities defined on their own domains.

U — the universal mathematical operator that verifies relations inside the same canonical continuum.

The project starts from a simple goal: keep identity, values, relations, memory, computation, and behavior inside the same Space, while avoiding canonical duplication, parallel states, and hidden application logic outside the Space.

Main file

Riki 006(2).html

The file contains minimal HTML with a Space declared inside:

<script type="application/riki-space" id="riki-space">

It is not a complete application. It represents the axiomatic core from which other systems can be built.

Fundamental principles

BYTE

Every identity has one and only one permanent canonical BYTE.

A change does not create a new identity and does not require copies or discrete canonical states.

VALUE

Each BYTE is associated with one and only one permanent dynamic VALUE.

The value may change arbitrarily — including discontinuities, jumps, singularities, or breaks — without recreating the BYTE.

BIT

BIT belongs to {0,1}.

BIT = 1 only when at least one connected CHAIN has a defined, non-empty domain and all connected CHAINS are true on their respective domains.

If a required function is not defined inside the Space, it is not invented or delegated outside the Space: the relevant BIT remains 0.

CHAINS

A CHAIN is a permanent mathematical equality:

A = B

defined on its own domain D_C.

When subtraction is mathematically defined:

DELTA_C = A - B

and therefore:

DELTA_C = 0  <=>  A = B

CHAINS may be simple, composed, or cyclic, but they are valid only when their equalities are actually true on their respective domains.

Universal mathematical operator U

U is the central operational principle of RIKI CORE.

It is not a separate solver, it is not a function that creates new states, and it is not an engine external to the Space.

U operates on CHAINS that already exist inside the same canonical continuum and verifies their mathematical relation on the corresponding domain.

For a CHAIN:

C : A = B    on domain D_C

U verifies directly that:

A = B

is true on D_C.

When subtraction is mathematically defined, the same relation may be written as:

DELTA_C = A - B

therefore:

DELTA_C = 0  <=>  A = B

The fundamental point is that U does not introduce a second representation of the problem.

It does not create copies of BYTEs, does not create new canonical VALUEs, does not construct parallel intermediate canonical states, and does not replace the CHAINS with another computational system.

Conceptually:

BYTE + VALUE + CHAINS
          |
          v
          U
          |
          v
verification of the truth of the relations
          |
          v
         BIT

U behaves in the same way for simple, composed, or cyclic CHAINS. The complexity of a relation does not change the nature of the operator.

Most importantly, U does not complete what is missing.

If a required function is not defined inside the Space:

missing function
      |
      v
U does not invent it
      |
      v
condition remains unvalidated
      |
      v
relevant BIT = 0

Likewise, executable JavaScript outside the Space cannot be used as a shortcut to replace a missing function or to obtain BIT = 1 artificially.

Therefore U does not mean “automatically compute anything.”

It means:

Verify, inside the same Space, the mathematical equalities that are actually defined by the CHAINS and their domains, without introducing a parallel computational reality.

Philosophy

RIKI CORE attempts to reduce a system to a minimal set of permanent concepts:

BYTE
  |
  v
VALUE
  |
  v
CHAINS
  |
  v
BIT
  |
  v
U

The purpose is not to impose one specific kind of application, but to provide a common core that can be used for experiments involving:

mathematical computation;

CAD;

geometry and structural systems;

AI;

simulation;

memory and state;

interfaces and programmable environments.

JavaScript outside the Space

The file applies a Content Security Policy that prevents executable scripts from running outside the declared Space.

Within the declared model, JavaScript external to the Space cannot replace a missing canonical function and cannot make a branch valid when it would otherwise have BIT = 0.

Project status

RIKI CORE is an experimental core.

The file defines the principles and axioms of the Space; by itself, it does not claim to implement every possible function.

Systems built on top of this core should clearly declare which parts are defined and which parts remain at BIT = 0.

Usage

You can:

download the HTML file;

read the Space directly;

define new CHAINS and VALUEs;

build applications while preserving the principles of the core;

modify, study, and redistribute the project.

License

This project is released under the MIT License.

You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software under the terms of the MIT License.

See LICENSE.

Contributions

Forks, experiments, tests, alternative implementations, and documentation are welcome.

When extending the project, it is useful to keep explicit:

the domain of every CHAIN;

the conditions that determine BIT;

the functions actually defined inside the Space;

the parts that are not yet validated;

the absence of hidden fallback systems.

The idea in one sentence

One permanent identity, one dynamic value, explicit mathematical relations, and no second hidden reality outside the Space.
