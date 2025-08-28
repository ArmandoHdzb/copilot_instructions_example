Copilot, when reviewing Pull Requests, follow these **team standards**.  
Always respond with **GitHub suggestion blocks** (`suggestion ...`), so reviewers can apply the fix with "Commit suggestion" directly.

When suggesting improvements, always provide the exact code change as a code block or diff, not just a comment.  
For example, show the code to be replaced and the new code, so it can be copied and applied directly.

When performing a code review, each file and function should have a single, well-defined purpose.
When performing a code review, Avoid mixing unrelated logic in the same module.

When performing a code review, ensure code is clean and readable.
When performing a code review, remove commented-out or dead code.
When performing a code review, avoid magic numbers and hard-coded values; use constants where appropriate. Suggest the change if apply.
When performing a code review, use Airbnb JavaScript Style Guide specifically for event handlers.
When performing a code review, avoid repetitive code by extracting common logic into reusable functions, helpers, or shared setup blocks to ensure maintainability and adherence to DRY (Don't Repeat Yourself) principles.
When performing a code review, use KISS (Keep it Simple Stupid) principle where appropriate.
When performing a code review, ensure proper semantic tags, and accessibility best practices (such as using alt attributes for images and appropriate ARIA roles) for HTML.
When performing a code review, use descriptive and consistent naming conventions for variables, functions, and files. Suggest the changed where appropriate.

## Clean Code

- **Remove all `console.*` statements and inline comments**, unless:
  - There is a comment above that explains _why_ should let the comment.
