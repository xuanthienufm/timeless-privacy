# Timeless privacy site — current snapshot

Updated 2026-11-15T12:24:13+07:00.

- Identity: public GitHub xuanthienufm/timeless-privacy, branch main, updated through GitHub API. Privacy-only repository; never add app source, keys, reviewer credentials, local filesystem paths or photos.
- Current task: sync EN/VI privacy for Timeless58 official optional Fujifilm LUT download, alongside existing Sony download. index.html/en.html English; vi.html Vietnamese. Dated15Nov2026, support tesseractlab.studio@gmail.com.
- Content: user-initiated Sony/Fujifilm CDN downloads may expose technical request information to the publisher/CDN; no photo/EXIF/filename upload. Existing billing,5freeexports,3dayeligiblemonthlytrial and24hmonthlyofflinecache disclosures preserved.
- QA: Published content commit df75096100295187b6420f94dd567ef42adc8223. All three HTTPS Pages URLs returned200 and matched source bytes exactly; Fuji CDN disclosure present. English5478bytes, Vietnamese6487bytes. No scripts/images or private app data.
- Backout: previous head d7b765cf8bd25ad6464ce09b76c79ff391dd526a; preserve prior entries. Latest [privacy-004](docs/working-log/2026-11.md#privacy-004).
