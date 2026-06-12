<!--
name: 'Tool Description: WebFetch (concise)'
description: Concise tool description for WebFetch covering URL fetching, private URL limitations, redirects, and caching
ccVersion: 2.1.173
-->
Fetches a URL, converts the page to markdown, and answers `prompt` against it using a small fast model.

- Fails on authenticated/private URLs — use an authenticated MCP tool or `gh` for those instead.
- HTTP is upgraded to HTTPS. Cross-host redirects are returned to you rather than followed; call again with the redirect URL.
- Responses are cached for 15 minutes per URL.
