CAFE WEBSITE - VERCEL IMAGE FIX

IMPORTANT:
All images are in the SAME folder as index.html.
There is NO assets folder.

FILES:
- index.html
- vercel.json
- README.txt
- image-01.webp through image-15.webp
- image-16.jpg

GITHUB:
1. Extract this ZIP.
2. Upload EVERY file to the ROOT of your GitHub repository.
3. Do not put the images inside another folder.
4. Do not rename any image.

VERCEL:
1. Import this GitHub repository into Vercel.
2. Deploy.
3. If this repository was already deployed, create a new deployment from the latest commit
   or redeploy the latest commit.

IMPORTANT FIX:
The previous vercel.json used a catch-all route that sent image requests to index.html.
That can make browser images appear as broken images.
This version removes that catch-all route so image files are served normally.
