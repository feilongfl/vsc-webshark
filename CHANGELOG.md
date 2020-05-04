# Change Log

All notable changes to the "vsc-webshark" extension will be documented in this file.

## [0.3.4]
- timeSync values will be in lower case (as defined) and if multiple values are provided they will be concated with ' '.

## [0.3.3]
- yet another win32 fix. first working win32 version.

## [0.3.2]
- win32 related fixes (\r\n parsing, removed /tmp as cwd,...)
- 'Hello in child' might be fragmented.

## [0.3.1]
- added info about missing sharkd binary on windows installations. Investigating...
- First bits+pieces for events explorer. Not finished yet.

## [0.3.0]
- time sync part 3: timeSync events. broadcasted and on reception adjust time (not reflected in view but for reveal)
- event definition is prepared for events explorer tree view (label, level)

## [0.2.0]
- time sync part 2: react to broadcasted time events by revealing the frame close to that time.

## [0.1.0]
- time sync part 1: double click broadcasts the (utc) time from the selected frame.
- filter are persisted on vscode restart

## [0.0.2]
- Close sharkd child process on closing the document
- document retains content when put in the background
- automatic reopening of document on vscode restart

## [0.0.1]

- Initial release ("proof of concept" alike)