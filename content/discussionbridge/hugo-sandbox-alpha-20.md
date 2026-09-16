---
title: Hugo Sandbox Alpha.20
date: 2026-09-15T17:45:00-07:00
description: A human-operated Hugo publication connected to the DiscussionBridge sandbox.
discussionbridge_mode: to_discourse
discussionbridge_publish: true
authors:
  - id: hugo-sandbox-editor
    name: Hugo Sandbox Editor
discussionbridge_primary_author_id: hugo-sandbox-editor
---

This page is the human-operated DiscussionBridge Alpha.20 Hugo sandbox publication.

It verifies that Hugo can generate a deterministic content manifest, authenticate
through its own Content Connection, and resolve one durable Bridge Record and
Discourse topic without exposing the connection credential in public output.

## Stable across rebuilds

An exact rebuild or retry must resolve the same Bridge Record and topic. It must
not create a duplicate discussion or change the canonical Hugo identity.

{{< discussionbridge mode="interactive" >}}
