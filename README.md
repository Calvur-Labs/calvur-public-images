# calvur-public-images

Public image host for **The Calvur Briefs** newsletters, served by GitHub Pages at:

`https://calvur-labs.github.io/calvur-public-images/<path>`

The code, templates, brand sources and issues live in the **private** repo `Calvur-Labs/calvur-briefs`. Only final, reader-facing images are copied here.

## Rules

1. **Public by design.** Only images that newsletter readers are meant to see: mastheads, edition logos and stamps, regional badges, and Envelope issue images (maps, illustrations).
2. **Nothing personal.** No Calvur's Desk content beyond its logo mark and static masthead. No photos of people, homes or documents. No names, addresses or account details in images or file names.
3. **Never overwrite.** Files are versioned (`masthead-bcn-v1.jpg`, then `-v2`). A sent email keeps pointing at the version it was sent with.
4. **Email-sized.** About 1200 px wide (shown at 600 px), under ~100 KB each. Every `<img>` in an email has alt text, so the email still reads when images are blocked.
5. **Per-issue images** go under `envelope/regions/<region>/issues/<issue-id>/`.

## Layout

```
desk/                          Calvur's Desk: logo mark + static masthead (the week strip is HTML in the email)
envelope/core/                 Calvur Envelope: shared brand (stamp logo)
envelope/regions/bcn/          BCN Envelope: masthead
envelope/regions/bcn/issues/   per-issue images (escape map, further-afield maps)
```

New regions (e.g. `envelope/regions/cr/`) follow the same pattern.
