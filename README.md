# dp-proposal-images

Cover photos for Design Pro JobTread proposals. Public on purpose: when a proposal is made, JobTread pulls the chosen picture straight from its link here. Nothing else belongs in this repo.

- `pictures.json` lists every picture: name, project type, order (lower shows first), file and link.
- Folders: kitchens, bathrooms, basements, market-prep, exteriors, main-level, flooring.
- Pictures are resized to 2400 px max, JPG.

To add a picture: drop the JPG in its folder and add a row to `pictures.json`. To change which pictures show first for a project type, change their `order`.

The proposal skill in the private DP Claude library reads this list. If a picture is missing or fails to load, the proposal keeps the JobTread template's default cover photo.
