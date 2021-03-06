# 0.0.11

- Use `universal_io` package for IO.
- Fix `l10n.dart` file generating wrongly, again.
- Use `lint` package for static analysis.

# 0.0.10

- Fix `l10n.dart` file being generated lacking messages due to using wrong locale as the main one.

# 0.0.9

- Rename example/README.md to example/EXAMPLE.md

# 0.0.8

- Add example project.

# 0.0.7

- Fix message descriptions containing apostrophes to ruin `l10n.dart`.
- Fix dependencies versions conflicts.

# 0.0.6

- Fix `l10n.dart` generator for languages with only country name provided.

# 0.0.5

- Always provide `countryCode` for `Locale`s in `l10n.dart`. Fixes an exception.

# 0.0.4

- Fix error generating `description` argument instead of `desc` in `l10n.dart`.
- Add delegate field to `l10n.dart` generator.
- Add `supportedLocales` to `l10n.dart` generator.

# 0.0.3

- Fix health suggestions.
- Fix NoSuchMethodError when running without pubspec config.

# 0.0.2

- Fix `petitparser` version constraint error on some Flutter branches.

# 0.0.1

- This is the first release of arbify package! It still needs tests and testing, but _generally_ should work.

# 0.0.0

- Parking package name
