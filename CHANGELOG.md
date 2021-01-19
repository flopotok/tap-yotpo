# Changelog

## 1.1.2
  * Retry requests that receive 502 and 400 response.
  * Reauthenticate when connection is closed.

## 1.1.1
  * Add explicit dependency for pendulum

## 1.1.0
  * Update stream selection to use metadata rather than deprecated annotated-schema [#4](https://github.com/singer-io/tap-yotpo/pull/4)

## 1.0.1
  * Update version of `requests` to `2.20.0` in response to CVE 2018-18074

## 1.0.0
  * Version bump for initial release

## 0.2.0
  * Include deleted reviews and sync backwards 30 days to pick up updated / deleted records [#1](https://github.com/singer-io/tap-yotpo/pull/1)
