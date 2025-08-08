## [1.9.7] - 2025-08-08

### 🚀 Features

- Abstract http fetcher interface
- Abstract conversion of data to separate function
- Implement test fetcher abstraction
- Add ready event and state machine
- Metrics class
- Passing tests
- Disable metrics
- Added variant payload support
- Variant metrics
- Send appName
- Send environment in url
- Ability to set multiple context fields
- Ability to set multiple context fields
- Ability to set multiple context fields
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent duplicate calls when context stays the same
- Prevent excessive fetch calls
- User controlled update toggles and send metrics
- User controlled update toggles and send metrics
- Prevent fetch on init (#56)
- Sdk uniqueness (#57)

### 🐛 Bug Fixes

- Late init
- Add test for encoding query parameters
- Typesafe url
- Count metrics for variants
- Tests
- Event emitter test
- Format
- [**breaking**] Set clientstate before emitting event
- Handling missing api data
- Custom properties encoding
- Add type for the 'properties' parameter
- Formatting
- Handle parsing errors elegantly, skipping incorrectly formatted entries
- Handle fetching from storage elegantly
- Handle fetching from storage elegantly
- Payload stringify in bootstrap
- Skip initial fetch with context (#60)
- Drop x prefix (#62)
- Add variant data to impression event (#64)
- Stop metrics timer on stop client (#65)

### 💼 Other

- Updated `http` to 1.1.0
- Changed dart sdk version and `http` version to support dart 3.0
- Update release process

### 🚜 Refactor

- Remove unused toQueryParams()

### 📚 Documentation

- Update readme: front-end API and structure
- Update readme
- Mention http fetcher and poster in README.md

### 🧪 Testing

- Check config equality
- App name reporting
- App name reporting

### ⚙️ Miscellaneous Tasks

- Version bump
- Version bump
- Version bump
- Version bump
- Version bump
- Update deps
- Update sdk connection
- Merge pull request #34 from Unleash/deps-update-semver-range
- Pr issues automation
- Merge pull request #35 from Unleash/pr-issue-automation
- Merge pull request #37 from Unleash/set-multiple-context-fields
- Version bump
- Version bump
- Version bump
- Version bump
- Merge pull request #38 from Unleash/version-bump
- Bump version
- Bump dependencies with dart fix
- Bump dependencies with dart fix
- Bump version to 1.5.1
- Update CHANGELOG.md
- Version update
- Increase uuid and shared_preferences version ranges
- Increase uuid and shared_preferences version ranges
- Increase uuid and shared_preferences version ranges
- Changelog
- Upgrade event emitter (#59)
- X-unleash-sdk version scheme (#61)
- Update repository refs
- Update repository refs and improve readme
- Change registration name to unleash-flutter-sdk (#67)
- Automate release process (#68) (#69)
