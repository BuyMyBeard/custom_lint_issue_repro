# custom_lint_issue_repro

Reproduction of issue where running custom_lint in a pnpm workspace with firebase installed causes an exception to be thrown.

To reproduce, run these commands:

```
flutter pub get
npm install -g pnpm
pnpm init
pnpm install
dart run custom_lint
```