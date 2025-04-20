#learning management systmes 
git clone https://github.com/ninja345-long/learning-management.git
cd learning-management
echo "New update at $(date)">> README.md
git add README.md
git -m update "Updated RAEDME with timestamp"
git push origin main
