# Homestead Cleaning Co.

A responsive static website for Homestead Cleaning Co., serving Alabama.

The site uses `sweethome@hotmail.com` for quote requests. 

## Run locally

Open `index.html` in a browser or run a local static server from this folder:

```powershell
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Production

- Website: <https://homestead-cleaning.vercel.app>
- Source: <https://github.com/joselinekiptalam-c/homestead-cleaning>

The site is deployed as a static project from the repository root. To publish
local changes, run `npx vercel --prod` from this folder. GitHub pushes do not
automatically trigger a new deployment until the GitHub account connection is
completed in Vercel.
