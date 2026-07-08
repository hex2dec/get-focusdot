# FocusDot

FocusDot is a macOS menu bar app for focused work sessions.

This public repository is for FocusDot releases, issue reports, and product
feedback.

## Releases

Download the latest version from the GitHub Releases page.

### macOS Gatekeeper Notice

FocusDot releases are currently not signed with an Apple Developer certificate.
If macOS blocks the app after installation with the message `"FocusDot" is
damaged and can't be opened. You should move it to the Trash.`, you can remove
the quarantine attribute with:

```sh
sudo xattr -rd com.apple.quarantine /Applications/FocusDot.app
```

## Feedback

Use GitHub Issues to report bugs, request improvements, or share feedback.

## License

MIT License. See [LICENSE](LICENSE).
