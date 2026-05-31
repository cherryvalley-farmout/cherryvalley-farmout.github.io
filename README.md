cat > README.md << 'EOF'
# cherryvalley-farmout.github.io

Source for the **Cherry Valley Farmout** website.

- **Live site:** https://cherryvalley-farmout.github.io/
- **Repo:** https://github.com/cherryvalley-farmout/cherryvalley-farmout.github.io

## Publishing

Edit `index.html` (and friends), then:

    git add -A && git commit -m "describe change" && git push

GitHub Pages redeploys from `main` automatically.
EOF
git add README.md && git commit -m "Add README with live site link" && git push