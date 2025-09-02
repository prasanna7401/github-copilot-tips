# Crafting Effective Prompts

## Things to Know

GitHub Copilot code suggestions are influenced by:
- Open files
- Top-level comments
- Appropriate agent (`/`), includes (`@`), and references (`#`) commands
- Meaningful function & variable names
- Providing sample input & expected output format
- Consistency & coding style of the user

---

## Commonly Used Prompts for Different Use Cases

### Create a `README.md`

**Ask Mode:**
```txt
@workspace /explain I need help creating a README file for this GitHub repository. The file should be formatted as markdown and include: Project Title, Description, Table of Contents, Installation, Usage, Features, Configuration, and License.
```

**Edit Mode:**
Replace `@workspace /explain` with `#codebase` in the previous prompt.

---

### Create Inline Code Documentation

**Ask Mode:**
```txt
@workspace /doc Create inline code documentation for all C# class files in the specified context. Document the class, its properties, required/optional attributes, and methods.
```

**Edit Mode:**
Replace `@workspace /doc` with `#codebase` in the previous prompt.


