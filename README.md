# Omoikane Embed - inoue2002

- 個人Scrapbox youkan-brainに対してGitHubAcrions経由でAIが生成したレポートを書き込んでくれる

This is a tool to embed contents in a Scrapbox project into vector space.
It was made for [Omoikane](https://scrapbox.io/omoikane/) scrapbox project.
Using Github Actions run following actions automatically in daily basis.

- 1: Fetch all pages from Scrapbox
- 2: Embed all pages using OpenAI API
- 3: Push the embedded vectors to Qdrant
- 4: Generate a report and push it to the Scrapbox project

