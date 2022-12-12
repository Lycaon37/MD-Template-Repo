## Conventional Commits
Using Conventional Commits is simple. Please start your commit message with one of the following prefixes:
- feat: For new features.
- fix: For bug fixes.
- perf: For performance improvements.
- docs: Changes to documentation.
- style: Changes that do not effect the purpose of the project. (Formatting, adjusting for best-practices, etc.).
- refactor: A change to the core project that neither fixes a bug nor adds a feature.
- chore: Changes to minor things. These shouldn't do anything visible to users.
- revert: Reverting commits. In the description, please list the commit IDs that are being reverted.

## Examples
This list will show some, but not all, use-cases for each of the conventional commit categories.

   ```
   feat: Project can now read GIF images
   ```

   ```
   fix: No longer crashes when name is longer than 15 characters
   ```

   ```
   docs: "prividing" to "providing"
   ```

   ```
   style: Names are now consistent with other projects
   ```

   ```
   refactor: General cleanup
   ```

   ```
   perf: Script now completes 25% faster
   ```

   ```
   chore: Updated release action
   ```