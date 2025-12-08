1. Update Next.js locally
   pnpm up next@latest
2. Update Next.js
   pnpm up next@latest
2. Regenerate the lockfile
   pnpm install
   # This updates pnpm-lock.yaml to match your new package.json.
3. Commit
	git add package.json pnpm-lock.yaml
	git commit -m "chore: update Next.js and pnpm lockfil"
	git push
	
   
Local npm
1. Enable Corepack
	corepack enable
2. Activate pnpm
	corepack prepare pnpm@latest --activate
	
3. Create/update .npmrc with
   package-manager=pnpm@10.12.4
4. Verify vercel.json
5. Commit and push


git clone https://github.com/wshang2022/MoonTV.git
cd MoonTV
dir
pnpm up next@latest
pnpm install
git add package.json pnpm-lock.yaml
git commit -m "Update Next.js and lockfile"
git commit -m "chore: update Next.js and pnpm lockfile"
git push
vi .npmrc
vim .npmrc
vim vercel.json
type vercel.json
vim vercel.json
git commit -m "chore: try installCommand with pnpm 10.12.4"
git commit -am "chore: try installCommand with pnpm 10.12.4"
git push
