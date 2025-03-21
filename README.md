# github-dir
A shared template of the `.github/` dir

This dir contains shared github workflows script and can be shared by each
github repo.


# Install

1. Add `./bin` to your `$PATH`, so that command `gh-dir-co` can be used
   everywhere.


# Usage

1. Update this repo with `git pull` etc.

2. Go to the `.github` dir of another repo, such as
   `cd my/repo/.github/workflows`.

   Running this script outside a `.github` dir results in an error.

3. Run `gh-dir-co <fn>` to copy `workflows/<fn>` in this repo to
   `my/repo/.github/workflows`.


