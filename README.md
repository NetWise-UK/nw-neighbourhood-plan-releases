# nw-neighbourhood-plan-releases

This repo holds built releases (zip files) of the **NW Neighbourhood Plan**
WordPress plugin. It has no source code — that lives in the private
`nw-neighbourhood-plan` repo. Client sites check here for updates.

`nw-neighbourhood-plan.json` is the file every client site actually polls. It is
written by the release workflow in the private repo on every version tag, and
served by `raw.githubusercontent.com` rather than the GitHub API — the API
allows 60 unauthenticated requests an hour counted per IP, shared by every site
on a server, and exhausting it makes updates fail silently.

Nothing here should be edited by hand.
