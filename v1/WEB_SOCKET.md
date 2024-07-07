# Web Socket <!-- omit in toc -->

# Table of Contents <!-- omit in toc -->

- [Initial Connection](#initial-connection)

# Initial Connection

When the web socket connects, the server will request a session token. A session
can be obtained via the [HTTP: Login](/v1/HTTP.md#login) endpoint. When connecting
via the official UI, the session token will be stored as a cookie after successfully
logging in.
