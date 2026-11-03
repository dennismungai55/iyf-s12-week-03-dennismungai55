## Challenges Faced

### Git Merge Conflict

During the branching and merging exercise, I encountered a merge conflict in `about.html`.

The conflict happened because two feature branches were created from `main` and both modified the same paragraph in the About page.

- The first branch changed the description to focus on learning web development.
- The second branch changed the same paragraph to describe my interest in creating responsive websites.

When I merged the first branch, it was successful. However, merging the second branch caused a conflict because Git could not automatically decide which version to keep.

**How I resolved it:**

I used GitHub's Resolve conflicts editor, reviewed both versions, and combined their ideas into one paragraph. I removed the conflict markers, marked the conflict as resolved, and completed the merge into `main`.

This helped me understand why merge conflicts happen and how to resolve them manually.
