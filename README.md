# iOS Engineer Blog — article discussions

Comments for [dementievmykola.com](https://dementievmykola.com), powered by [giscus](https://giscus.app).

This repository contains discussion configuration and community comments. The website source and article drafts are maintained separately.

- **Articles**: discussions for published articles. English and Ukrainian editions share the same thread.
- **Preview**: public test discussions from localhost and deploy previews, separate from live comments.
- Read without an account. Comment using GitHub, either on the website or directly in Discussions.
- Discuss the article, share reproducible examples and keep replies respectful. Do not post credentials or private information.
- Maintainers can hide spam, lock threads and moderate through GitHub Discussions.

The categories use Announcement format: maintainers and giscus create article threads; readers can comment and reply.

## Configuration

`giscus.json` restricts widget origins and defines the comment order. Its source configuration is `params.comments` in the website’s `hugo.yaml`; the website’s `scripts/sync_comments_config.mjs` publishes changes here.

All comments are public. Allowed origins prevent accidental embedding elsewhere; they do not make discussions private.
