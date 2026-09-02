Contributing to The X Project (TXP)

Thank you for your interest in contributing to The X Project (TXP).

TXP is an independent software ecosystem focused on developing its own system components, tools, languages, and operating-system technologies. The project is actively evolving, so contributions, ideas, testing, documentation, and technical feedback are welcome.

Before You Contribute

Please read the following files before making changes:

- "README.md" — Project overview and general information
- "CHANGELOG.md" — Development history and notable changes
- "LICENSE" — Licensing terms
- "SECURITY.md" — Security reporting and vulnerability information
- "docs/" — TXP documentation and development information

TXP is under active development. Some components may be experimental, incomplete, or subject to change.

What You Can Contribute

Contributions can include:

- Source-code improvements
- Bug fixes
- New features
- Build-system improvements
- Compiler, assembler, linker, or toolchain development
- Kernel development
- Bootloader development
- mX development
- cX development
- Documentation
- Testing and bug reports
- Build and compatibility testing
- Development tools
- Performance improvements
- Code quality and organization
- Technical suggestions and design proposals

Contributions do not have to be code. Documentation, testing, reproducible bug reports, and useful technical feedback are also valuable.

TXP Components

TXP contains multiple independently developed components and technologies, including:

- mX — The operating-system project within TXP
- cX — TXP's programming-language project
- XLoader — TXP's bootloader project
- Kernel24 — TXP's kernel development project
- TXP toolchain and development infrastructure
- Documentation and architectural specifications

When contributing, make sure your changes are directed toward the appropriate component.

Source Code Builds

TXP may distribute development snapshots as packaged source-code archives under:

"TXP Source Code Builds/"

For example:

"mX-Build_22.zip"

These archives can contain the source tree, build scripts, headers, assembly code, and other files required for development.

A packaged source-code build is still source code; the ZIP format is simply used to distribute a particular development snapshot.

When submitting changes to a future build, keep the build contents reproducible and avoid including unnecessary generated or temporary files.

Development Builds

TXP development builds may be experimental.

A build number does not necessarily indicate that the software is stable or production-ready. Features may be incomplete, changed, removed, or replaced in later builds.

When reporting an issue, include the exact component and build number whenever possible.

For example:

- "mX Build 22"
- "XLoader development build"
- "Kernel24 development revision"
- "cX development version"

Pull Requests

Before opening a pull request:

1. Make sure your changes are relevant to TXP.
2. Test your changes as thoroughly as possible.
3. Check that you have not accidentally included temporary files, personal files, credentials, or unrelated changes.
4. Update documentation when your change affects documented behavior.
5. Clearly describe what was changed and why.
6. Mention the component and build/version affected by the change.

A useful pull request should explain:

- What changed?
- Why was it changed?
- Which TXP component is affected?
- How was it tested?
- Are there any known limitations?

Commits

Please use clear and descriptive commit messages.

Examples:

Add mX memory manager
Fix XLoader boot initialization
Update cX parser
Improve Kernel24 scheduler
Update mX Build 22 sources
Fix documentation for build process

Avoid vague messages such as:

stuff
update
changes
fixed it
final final

Code and Project Style

Follow the existing style of the component you are modifying.

Do not perform large unrelated rewrites while submitting a focused change. Keeping changes organized makes development, review, debugging, and future maintenance easier.

If a component has its own coding conventions, build instructions, or documentation, follow those conventions.

Testing

Test your changes before submitting them whenever possible.

For system-level components, testing may include:

- Building from source
- Running the relevant build scripts
- Boot testing
- Emulator or virtual-machine testing
- Hardware testing where applicable
- Regression testing
- Checking for compiler or assembler errors
- Verifying that existing functionality still works

If something cannot be tested, clearly state that in the pull request.

Issues and Bug Reports

When reporting a bug, provide as much useful information as possible.

Include:

- Component affected
- Build/version
- Environment or hardware
- Steps to reproduce
- Expected behavior
- Actual behavior
- Relevant logs or error messages
- Additional information that may help reproduce the issue

A reproducible bug report is significantly more useful than a report such as:

«"mX doesn't work."»

Security Issues

Do not publicly disclose sensitive security vulnerabilities before they can be properly investigated.

Please follow the instructions in "SECURITY.md" for reporting security issues.

Scope of Contributions

TXP is an independent project. Contributions should respect the project's technical direction and architecture.

External libraries, dependencies, or existing technologies may be used when appropriate, but contributors should clearly document significant dependencies and their purpose.

Do not introduce a dependency simply when an existing TXP component is intended to provide that functionality.

Documentation

Documentation is an important part of TXP.

If you introduce a new feature, component, command, build process, or architectural change, consider updating the appropriate documentation under "docs/".

Clear documentation helps future contributors understand not only how something works, but also why it was designed that way.

Code of Conduct

Contributors are expected to communicate respectfully and constructively.

Technical disagreements are normal in software development. Discuss the implementation and evidence rather than attacking other contributors.

Final Note

TXP is a developing project, and its architecture will continue to evolve.

Whether you contribute code, documentation, testing, ideas, or technical feedback, your contribution can help move TXP forward.

Thank you for contributing to The X Project.
