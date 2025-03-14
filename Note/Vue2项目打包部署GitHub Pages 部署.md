- Vue2 项目打包部署 GitHub Pages 部署

```

#!/bin/bash
npm run build
cd dist
git init
git add -A
git commit -m "Auto-deploy"
git push -f origin gh-pages

```
