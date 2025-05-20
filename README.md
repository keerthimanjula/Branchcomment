# Branchcomment


git branch feature_update
git checkout feature_update
echo "Feature branch content" > feature.txt
git add feature.txt
git commit -m "Add feature content"
git checkout main
git merge feature_update
git push origin main
