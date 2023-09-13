# Changelog

This changelog follows the patterns described here: <https://keepachangelog.com/en/1.0.0/>.

Subheadings to categorize changes are `added, changed, deprecated, removed, fixed, security`.

## Unreleased

### added

- added `AsyncTask::with_timeout(mut self, dur)`
- added timeout support via `AsyncTask::new_with_timeout(dur, f)`
- added `AsyncTask::pending()` as an abstraction for a task that never finishes

## 1.0.1

### fixed

- broken documentation links are fixed

## 1.0.0

- Initialize release.