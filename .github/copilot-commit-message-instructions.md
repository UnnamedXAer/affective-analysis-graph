# Commit Message Guidelines

Generate commit messages following these rules:

## Subject Line

- Write in imperative mood (e.g., "Add feature" not "Added feature")
- Start with an uppercase letter
- Do not end with a period
- Use abbreviations (e.g. "env" instead of "environment", "config" instead of "configuration", "dev" instead of "development", ...)
- Limit to 50 characters maximum
- Summarize the change concisely

## Body

Note: Use the body only if there are multiple changes or if additional context is needed

- Separate body from subject with a blank line
- Wrap lines at 72 characters
- Format as a list of changes, each on its own line
- End each point with a semicolon
- Use abbreviations (e.g. "env" instead of "environment", "config" instead of "configuration")
- Explain *what* and *why*, not *how*

## Examples

Good (with body):
```
Refactor authentication module

Add token refresh logic for expired sessions;
Remove deprecated login methods;
```

Good (subject only):
```
Unify date format across application
```

Good (with body):
```
Refactor button styles

Add hover and disabled state for buttons;
Use consistent padding and margin;
```

Good (subject only):
```
Add hover and disabled state for buttons
```

```
Update Angular dependencies to v19

Upgrade @angular/core to version 19.0.0;
Upgrade @angular/router to version 19.0.0;
Fix breaking changes in standalone component API;
```

Good (subject only):
```
Fix null pointer exception in report service
```

Bad:
```
added new feature.
```
(lowercase start, past tense, ends with period)

```
This commit adds a really long description that goes way beyond the fifty character limit
```
(too long, not imperative)

```
Add production, staging and development environment authentication configuration
```
(too long, does not use abbreviations)