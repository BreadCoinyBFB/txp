Security Policy

The X Project (TXP)

Security is an important part of The X Project (TXP). TXP includes system-level software and development components, so security issues may affect the operating system, boot process, kernel, toolchain, or other parts of the ecosystem.

We appreciate responsible security research and reports that help improve TXP.

Supported Versions

TXP is under active development. Security support may vary depending on the component and development build.

As a general rule, the latest development version or build of a component should be used when investigating whether an issue has already been fixed.

For example:

Component| Version / Build
mX| Latest available development build
cX| Latest available development version
XLoader| Latest available development version
Kernel24| Latest available development version

Older development builds may no longer receive fixes.

Reporting a Vulnerability

If you discover a potential security vulnerability in TXP, please report it privately rather than publicly posting the vulnerability details in a GitHub issue, pull request, or public discussion.

A security report should include as much of the following information as possible:

- Affected component
- Affected version or build
- Description of the vulnerability
- Steps required to reproduce it
- Expected behavior
- Actual behavior
- Potential security impact
- Proof of concept, if available
- Relevant logs, crash information, or error messages
- Possible mitigation or suggested fix, if known

Please avoid including passwords, private keys, access tokens, personal information, or other sensitive information in a report.

What Qualifies as a Security Issue?

Examples of potentially security-relevant issues include:

- Privilege escalation
- Arbitrary code execution
- Unauthorized access
- Bootloader security vulnerabilities
- Kernel vulnerabilities
- Memory-safety issues
- Authentication or authorization bypasses
- Sandbox or isolation bypasses
- Cryptographic implementation weaknesses
- Unsafe handling of untrusted input
- Vulnerabilities that allow modification of protected system components
- Build-system or toolchain vulnerabilities
- Supply-chain vulnerabilities
- Security-sensitive information disclosure

Not every bug is necessarily a security vulnerability. If you are unsure, it is better to report the issue privately so it can be evaluated.

Responsible Disclosure

Please allow the TXP maintainers reasonable time to investigate and address a reported vulnerability before publicly disclosing technical details.

Once a vulnerability has been investigated and, where appropriate, fixed, TXP may document the issue and its resolution.

Public disclosure should avoid unnecessarily exposing users or developers to an unfixed vulnerability.

Security Updates

When a confirmed security vulnerability is fixed, relevant information may be added to the TXP changelog, release notes, or other project documentation.

Security fixes may be included in a future TXP development build or source-code release.

Users and developers are encouraged to keep their TXP components up to date.

Development and Experimental Software

TXP is actively developed, and some components may be experimental.

Development builds may contain:

- Unfinished functionality
- Experimental code
- Known limitations
- Temporary implementations
- Security weaknesses that have not yet been discovered or resolved

Do not assume that an experimental TXP build is suitable for security-critical or production environments.

Security Research

Security research and responsible testing are welcome when performed in a safe and authorized environment.

Do not:

- Access systems or accounts without authorization
- Attempt to obtain private information belonging to others
- Disrupt services or infrastructure
- Destroy or intentionally corrupt data
- Exploit vulnerabilities against systems that you do not own or have permission to test

Testing should be performed against your own systems, local development environments, emulators, virtual machines, or other explicitly authorized environments.

Dependency and Supply-Chain Security

TXP aims to maintain control and transparency over its development components and dependencies.

Significant external dependencies should be documented where appropriate.

Contributors should not introduce malicious code, compromised dependencies, hidden functionality, or unnecessary security-sensitive dependencies into the project.

Changes affecting the bootloader, kernel, compiler, build system, or other security-critical components should receive additional scrutiny.

Security Contact

For private vulnerability reporting, use the security reporting mechanism provided by this GitHub repository.

If GitHub's private security reporting features are enabled for the repository, please use the repository's Security tab to submit a private vulnerability report.

If private reporting is not available, contact the TXP maintainers through an appropriate private channel rather than publicly posting sensitive vulnerability information.

Thank You

Thank you to everyone who responsibly reports security issues and helps make The X Project (TXP) safer.

Security research, testing, and responsible disclosure are valuable contributions to the project.
