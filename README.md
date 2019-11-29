# update-version-hook

Update a project's VERSION file to match the version in the branch name via git hook.

## Usage

Add the file `pre-push` to your project's `.git/hooks` directory.

Now when you push to a branch that begins with `release/<version.number>`, a second commit will be made that increments the VERSION file.


