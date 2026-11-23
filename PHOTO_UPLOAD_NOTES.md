# Family photo uploads

Use this local checkout for future family photo uploads:
`/Users/jobyywilson/Documents/Projets/peralummoottil-resource`.
Remote: https://github.com/jobyywilson/peralummoottil-resource (main).

- Save profile photos in the repository root as `<nodeId>.png` (or jpg/jpeg).
- Save gallery photos in `gallery/` with unique descriptive filenames.
- Publish the requested images through the existing GitHub/Netlify workflow.
- Verify the image host serves actual images, rather than its default-image redirect.
- In Supabase project `hzqpjqvopcevhucgazlh`, create one `public.photo` row per gallery image. The three URL columns contain the filename relative to `gallery/`, without a leading slash. The same filename can be used for all sizes.
- Link each gallery photo using `public.photo_tag.user_id` = the member nodeId and `photo_id` = the photo row ID. Verify the member first and avoid duplicate tags.
- Verify the resulting tags and images before reporting completion.

## Ansa Anil Vazhuvelil

Member: `9F-2.2.2.4.4.1.2`, family tree `KPK`.
Profile: `9F-2.2.2.4.4.1.2.png`.
Gallery: `gallery/ansa-anil-vazhuvelil-wedding-1.png` and
`gallery/ansa-anil-vazhuvelil-wedding-2.png`.
All three supplied images were preserved unchanged.
