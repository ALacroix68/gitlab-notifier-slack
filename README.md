(In coming)

# gitlab-notifier-slack
Middleware tool which create notifications in Slack when specific events are triggered on Gitlab.

# How does it works

Gitlab webhooks is a feature that send JSON data to a configured URI.

# Events example that trigger the webhook

- Pushing code to a repository.
- Posting a comment on an issue.
- Creating a merge request.

# Events listened by this tool

- note => New thread on your MR, new comment on a thread you have already responded or new ping on a comment
- pipeline => Pipeline fails.
- merge_request_approuvee => New approve on a merge request.
- merge_request_desapprouvee => New unapprove on a merge request.
- merge_request_mergee => Merge request are merged.


# Configuration

todo
