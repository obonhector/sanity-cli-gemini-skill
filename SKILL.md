---
name: sanity-cli
description: "Integration with Sanity.io CMS via CLI. Use when Gemini CLI needs to manage content, schemas, or projects in Sanity. Supports creating blog posts, querying datasets, and managing Sanity Studio projects."
---

# Sanity CLI Skill

This skill allows Gemini CLI to interact with Sanity.io using the official CLI.

## Key Workflows

### 1. Authentication
To use Sanity CLI, you must be logged in. If you are not logged in, ask the user to run:
`sanity login`

### 2. Content Management
- **List documents**: `sanity documents query "*[_type == 'post']"`
- **Get document**: `sanity documents get <ID>`
- **Create document**: `sanity documents create --replace <path/to/doc.json>`
- **Delete document**: `sanity documents delete <ID>`

### 3. Project Information
- **List projects**: `sanity projects list`
- **Show current project info**: `sanity debug`

### 4. Schema and Studio
- **Start Studio**: `sanity start` (local development)
- **Deploy Studio**: `sanity deploy`
- **Manage datasets**: `sanity dataset list`

## Writing a Blog Post
When asked to write a blog post:
1. Generate the content in JSON format matching the schema (usually `post`).
2. Save it to a temporary file.
3. Use `sanity documents create <file.json>` to publish it.

## Reference
For a complete list of commands, use `sanity help`.
