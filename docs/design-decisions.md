# Design decisions

## Queue over spreadsheet

Each caller receives explicit owned work rather than a shared editable list.

## Touches as events

Every action is recorded separately, preserving history and enabling reporting.

## Time-zone safety

The interface checks local calling eligibility before encouraging contact.

## Manager separation

Assignment and performance controls are unavailable to ordinary callers.

