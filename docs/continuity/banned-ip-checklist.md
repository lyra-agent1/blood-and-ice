# Banned IP Checklist

This project must remain a white-labeled original fantasy work.

## Banned Categories

Do not use:

- old franchise character names
- old franchise house or family names
- old franchise place names
- old franchise creature names
- old franchise religion or title terms
- direct references to the prior source franchise
- instructions to imitate named living authors

## Scan Command

Run this before opening a PR:

```bash
rg -n -i "rickon|stark|skagos|winterfell|westeros|direwolf|direwolves|game of thrones|song of ice and fire|asoiaf|greyjoy|bolton|mormont|karstark|umber|baratheon|targaryen|lannister|pierce brown|george rr martin|rothfuss|lovecraft" .
```

Expected result: no matches in the public branch surface.

If a match appears in this checklist command itself, use a script or manual review that excludes this file. The public prose and bibles must stay clean.

## Manual Review

- Check README.
- Check docs outside this file.
- Check manuscript.
- Check PR title and description.
- Check commit messages.
