some helper scripts i use

put them in a bin/ folder that's somewhere on your system path. 

e.g., `git clone ... helper-bin; echo "export PATH=\"$(pwd)/helper-bin:$$PATH\"" >> ~/.zshrc`

- `npr`: runs developer commands in the [NPD](https://github.com/DSACMS/npd) project without having to cd around between root, `backend/`, and `frontend/`
- `git pr`: open browser to the appropriate PR for the given project branch
- `git watch`: watch PR checks for the given project branch
- `git select`: use fuzzy search to switch git branches
- `passphrase-gen`: generate a bunch of password ideas
- `port`: show what process is listening on a given port
- `t`: run an executable script from `tmp/bin` or `scratch/bin` relative to the current directory