# Replace with your GitHub username
USERNAME=your-github-username

# Create directory and initialize git
mkdir apna-paryawaran
cd apna-paryawaran
git init
echo "# ApnaParyawaran

Eco-themed social media community platform" > README.md
git add README.md
git commit -m "Initial commit"
gh repo create $USERNAME/apna-paryawaran --public --source=. --remote=origin --push
