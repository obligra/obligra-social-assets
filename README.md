# Obligra social media assets

Public delivery repository for reviewed, finished Obligra branded images. Existing legacy OX files are preserved; their presence is not approval for new use.

## Release workflow

1. Prepare photography and branded overlays privately. Keep original stock packs, drafts, tests, private review records and credentials out of this repository.
2. Review the exact finished image, accompanying copy, destination and intended date. Review source rights, crop, contrast and mobile readability. Do not upload unreviewed work.
3. Add each approved output under `approved/YYYY/MM/<campaign>-<platform>-rN.<png|jpg>`. Use a new revision filename for every change; never silently replace a reviewed version.
4. Add a matching `.credits.json` with the image filename, SHA-256, dimensions, photographer, source URL, license URL and revision. Include only public-safe attribution; no local paths or private records.
5. After commit, use the direct URL `https://raw.githubusercontent.com/obligra/obligra-social-assets/<FULL_COMMIT_SHA>/approved/YYYY/MM/<filename>`. Do not use GitHub's HTML blob page or a mutable main-branch URL for an approved package.
6. Fetch without authentication and verify HTTP success, image content type, actual image decoding and SHA-256 against the reviewed file. Preserve the URL through publication.
7. Hosting is not publication or proof of publishing-service ingestion. Publish only through the authorized route after its separate checks. Record the exact version and actual result in the private operating ledger.

## Rights and safety

Use only cleared source materials and authentic brand elements. Free Unsplash photographs are subject to the [Unsplash license](https://unsplash.com/license) and [terms](https://unsplash.com/terms), including separate rights for identifiable people, brands and artwork. Keep photographer credits even when not required. Stock scenes must not imply customer endorsement or depict actual product UI.

This is a public repository. Uploads can be copied, cached, forked and retained in Git history. Do not include original photo libraries, private data, credentials, drafts or test posters. No blanket license is granted over third-party photographs or Obligra trademarks.

Use optimized final still images. Video masters and large binary source libraries belong in appropriate separately authorized storage, not ordinary Git history.
