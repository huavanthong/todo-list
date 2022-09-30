# Reference
* Original project. Refer: [here](https://github.com/btubbs/todopy-pg)


# Python + Postgres + React TodoMVC Example

This application takes the React TodoMVC example and adds a Python and Postgres
backend.

All changes are immediately stored in Postgres (instead of browser localStorage
as in the upstream example), and then streamed out to clients via websockets.

To get it running:
