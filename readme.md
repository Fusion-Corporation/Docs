# Fusion Corporation Documentation

Official documentation source for **Fusion Corporation**.

This repository contains the source content for all Fusion Corporation documentation, written in **MDX** and **TSX**.

It serves as the canonical source for product documentation, technical guides, references, and supporting documentation content across the Fusion ecosystem.

---

## Repository Purpose

This repository contains documentation source files only.

It does **not** include:

* Documentation web server
* Frontend application
* Routing system
* Rendering infrastructure
* Deployment configuration
* Backend services

These are maintained separately to preserve a clear separation between documentation content and platform infrastructure.

---

## Documentation Stack

Documentation is built using:

* **MDX** for content authoring
* **TSX** for interactive documentation components
* Embedded React components
* Typed component-driven documentation rendering

This allows documentation to combine traditional written content with interactive examples, reusable UI blocks, and dynamic rendering.

---

## Writing Guidelines

### General Standards

* Keep documentation clear and concise
* Prioritize accuracy and maintainability
* Use consistent terminology
* Prefer practical examples where useful

### MDX Standards

Use MDX for structured documentation pages:

```mdx
# Authentication

> [!NOTE]
> API tokens expire after 24 hours.

<AuthExample />
```

### TSX Components

Reusable documentation components should remain:

* Modular
* Typed
* Reusable
* Presentation-focused

---

## File Naming

Use lowercase kebab-case where applicable:

```text
authentication-guide.mdx
api-reference.mdx
installation.tsx
callout.tsx
```

Avoid:

```text
AuthenticationGuide.mdx
apiReference.mdx
```

---

## Contribution Workflow

### 1. Create a branch

```bash
git checkout -b docs/your-change
```

### 2. Make changes

Update MDX or TSX documentation sources.

### 3. Validate

Ensure:

* MDX compiles correctly
* TSX components build without errors
* Imports resolve properly
* Links remain valid

### 4. Commit

```bash
git commit -m "docs: update authentication documentation"
```

### 5. Open a pull request

All changes should be reviewed before merge.

---

## Review Standards

Documentation updates should be reviewed for:

* Technical correctness
* Formatting consistency
* Component reusability
* Clarity
* Accuracy
* Build compatibility

---

## Versioning

Documentation evolves alongside Fusion Corporation products and services.

Breaking changes should be reflected through versioned documentation where necessary.

---

## Licensing

All documentation within this repository is the intellectual property of **Fusion Corporation** unless otherwise stated.

See the repository license for full terms.

---