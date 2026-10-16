# Security policy

moat runs in the kernel's packet path, so a bug can drop traffic it should
not, let through traffic it should drop, or be used to exhaust memory.
Please report such problems privately.

## Reporting

Use the "Report a vulnerability" button on the repository's Security tab.
It opens a private advisory that only the maintainers can read. Include
the rules file, the case file or capture that shows the problem, the
kernel version (`uname -r`) and the output of `moat version`. If you
cannot use GitHub, write to maintainers@moatfw.dev instead.

Once a fix is released, the advisory is published with credit to the
reporter, unless you prefer otherwise.

## Supported versions

Fixes go into the latest release. There are no long-term support branches
yet.
