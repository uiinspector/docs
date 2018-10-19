---
tap: "github"
version: "1.x"
name: "review_comments"
doc-link: ""
singer-schema: "https://github.com/singer-io/tap-github/blob/master/tap_github/schemas/review_comments.json"
description: ""
replication-method: ""
api-method:
    name: ""
    doc-link: ""
attributes:
  - name: "assignee"
    type: "string"
    description: ""
  - name: "assignees"
    type: "string"
    description: ""
  - name: "author_association"
    type: "string"
    description: ""
  - name: "base"
    type: "string"
    description: ""
  - name: "body"
    type: "string"
    description: ""
  - name: "comments_url"
    type: "string"
    description: ""
  - name: "commit_id"
    type: "string"
    description: ""
  - name: "commits_url"
    type: "string"
    description: ""
  - name: "created_at"
    type: "date-time"
    description: ""
  - name: "diff_hunk"
    type: "string"
    description: ""
  - name: "diff_url"
    type: "string"
    description: ""
  - name: "head"
    type: "string"
    description: ""
  - name: "html_url"
    type: "string"
    description: ""
  - name: "id"
    type: "integer"
    description: ""
  - name: "in_reply_to_id"
    type: "integer"
    description: ""
  - name: "issue_url"
    type: "string"
    description: ""
  - name: "labels"
    type: "string"
    description: ""
  - name: "locked"
    type: "string"
    description: ""
  - name: "merge_commit_sha"
    type: "string"
    description: ""
  - name: "milestone"
    type: "string"
    description: ""
  - name: "node_id"
    type: "string"
    description: ""
  - name: "original_commit_id"
    type: "string"
    description: ""
  - name: "original_position"
    type: "integer"
    description: ""
  - name: "patch_url"
    type: "string"
    description: ""
  - name: "path"
    type: "string"
    description: ""
  - name: "position"
    type: "integer"
    description: ""
  - name: "pull_request_review_id"
    type: "integer"
    description: ""
  - name: "pull_request_url"
    type: "string"
    description: ""
  - name: "requested_reviewers"
    type: "string"
    description: ""
  - name: "requested_teams"
    type: "string"
    description: ""
  - name: "review_comment_url"
    type: "string"
    description: ""
  - name: "review_comments_url"
    type: "string"
    description: ""
  - name: "statuses_url"
    type: "string"
    description: ""
  - name: "updated_at"
    type: "date-time"
    description: ""
  - name: "user"
    type: "object"
    description: ""
    object-properties:
      - name: "id"
        type: "integer"
        description: ""
      - name: "login"
        type: "string"
        description: ""
---