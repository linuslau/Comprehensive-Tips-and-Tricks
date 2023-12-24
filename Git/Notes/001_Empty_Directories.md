`.gitkeep` isn’t documented, because it’s not a feature of Git.

Git [Can I add a completely empty directory](https://git.wiki.kernel.org/index.php/Git_FAQ#Can_I_add_empty_directories.3F). People who want to track empty directories in Git have created the convention of putting files called `.gitkeep` in these directories. The file could be called anything; Git assigns no special significance to this name.

There is a competing convention of adding a `.gitignore` file to the empty directories to get them tracked, but some people see this as confusing since the goal is to keep the empty directories, not ignore them; `.gitignore` is also used to list files that should be ignored by Git when looking for untracked files.

[What are the differences between .gitignore and .gitkeep?](https://stackoverflow.com/questions/7229885/what-are-the-differences-between-gitignore-and-gitkeep)
