Reporting Issues
================

Thank you for helping improve **ComboBullet**. Your bug reports and feedback make the project better for everyone.

Before you report
-----------------

Please take a moment to:

- Check the documentation – The main ``README`` covers installation, usage, and common troubleshooting steps.
- Search existing issues – Your problem may already be reported or solved. Look for similar issues in the `GitHub Issues <https://github.com/AK-ALiEN/ComboBullet/issues>`_ (once enabled).
- Test the latest version – Download the newest release from the releases page. Your issue might already be fixed.

What to include in your report
-------------------------------

A great bug report helps me understand and fix the problem quickly. Please include:

1. Clear description – What happened? What did you expect to happen?
2. Steps to reproduce – List exact actions that trigger the issue.
3. Your environment:

   - Windows version (Windows 10, 11, Server, etc.)
   - System architecture (x64, x86, or ARM64)
   - ComboBullet version (e.g., v1.0.4)

4. Input file sample – A small anonymized excerpt of the log file that causes the issue (if possible).
5. Extraction mode used – Which mode were you using (username:password, email:password, cookie extraction, etc.)?
6. Screenshots (optional) – If the issue is visual or GUI-related.
7. Error logs – If the tool generates debug logs or error messages, include them.

Example report template:

::

   Description:
   ComboBullet crashes when processing a 500MB log file in email:password mode.

   Steps to reproduce:
   1. Launch ComboBullet v1.0.4 on Windows 11 x64
   2. Load a 500MB .txt log file
   3. Select "Email:Password" extraction mode
   4. Click "Process"
   5. Application closes without error message

   Environment:
   - Windows 11 Pro (24H2)
   - x64 architecture
   - ComboBullet v1.0.4 (win-x64 self-contained)

   Extraction mode: Email:Password

   Log excerpt (anonymized):
   [user123:pass456]
   [john@example.com:qwerty]

Where to report
----------------

- GitHub Issues – Preferred location: `https://github.com/AK-ALiEN/ComboBullet/issues <https://github.com/AK-ALiEN/ComboBullet/issues>`_
- Telegram – For quick questions or minor clarifications: `https://t.me/aliendevlab <https://t.me/aliendevlab>`_

Known limitations (not bugs)
-----------------------------

The following are not considered bugs. Please do not report them:

- **Windows-only** – The tool is designed exclusively for Windows systems.
- **Large file performance** – Extremely large logs (over 1GB) may process slowly depending on hardware.
- **Input quality** – Malformed or corrupted input files produce poor output (garbage in, garbage out).
- **Real-time processing** – The tool is not designed for streaming or live log processing.

Feature requests
-----------------

Suggestions are welcome! Open a GitHub Issue with the label ``enhancement`` and describe:

- What you want to achieve
- Why it would be useful
- Any ideas on implementation (if you have them)

Keep requests focused on ComboBullet's core mission: **processing logs and extracting credential data efficiently**.

Security issues
----------------

If you discover a security vulnerability (e.g., arbitrary code execution, file tampering), **do not open a public issue**.

Please report privately via Telegram to `https://t.me/ak_xlien <https://t.me/ak_xlien>`_.

Etiquette
----------

- Be respectful and patient – this is a solo project.
- Provide as much detail as you can.
- Follow up if I ask for more information.
- Close the issue when it's resolved for you.

Thank you for helping make ComboBullet reliable and efficient.
