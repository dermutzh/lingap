# Lingap

**Find the translations you missed.**

Lingap is a localization QA tool for Apple developers. It helps identify potentially untranslated strings that are present in localization files but still contain their original English values.

For example, a German `.strings` file might contain `"Hi there" = "Hi there";` instead of the intended German translation. Because the entry exists and is syntactically valid, this mistake can easily go unnoticed.

## Planned features

- Parse and validate Apple `.strings` files
- Detect translations identical to their source-language values
- Identify missing or empty translations
- Review and approve intentionally identical translations
- Support Xcode String Catalogs (`.xcstrings`)
- Provide a native macOS interface and eventually CLI integration

## Status

Early development. The initial focus is a Swift-based validation engine, followed by a macOS application built with SwiftUI.