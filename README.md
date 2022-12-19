# A11y Docs

A11y Docs is a repository of shared knowledge for designers, developers, and accessibility professionals.

## Why?

Digital accessibility can be difficult.

Interpreting the [accessibility guidelines](https://www.w3.org/WAI/WCAG21/quickref/) is one piece of the puzzle. Even learning to maneuver the [w3.org](https://www.w3.org/WAI/standards-guidelines/) site has a steep learning curve. And that’s to say nothing about learning how to use assistive technologies, what policies and regulations are at play, how to conduct audits and tests, or actually design or develop something using accessible patterns and ARIA.

Designers and developers should have a single, easy-to-reference document for accessibility requirements.

## How?

This project is an attempt to:

- Aggregate a list of general component types
- Define the essential elements that constitute those components
- Provide the functional requirements for designers and developers
- Show example technical techniques, not production ready code
- Suggest usability best practices through usage guidelines
- Detail the expected behavior across assistive technologies and input modalities

Documents are grouped into one of five categories:

- **Containers:** Frames of information (e.g., dialogs)
- **Information:** Bits of information (e.g., lists)
- **Inputs and Controls:** Sort've self-explanatory
- **Navigation:** Mechanisms of maneuverability (e.g., links or responsive navigation menus)
- **Patterns:** Guidance where a specific component doesn't quite make sense (e.g., data loading, attestation, or focus management)

They're somewhat arbitrary categories. The information architecture and labels will change over time.

There are only so many UI components and patterns. A document is created and fitted under a category. Each document follows a template, at least to the degree that it makes sense to do so. That template has the following structure:

- **Component or Variant Name:** The name of the component or pattern (e.g., Tabs)
- **Essential Elements:** The pieces that comprise the element (e.g., Tab Panels, Tab Controls)
- **Example:** Code blocks, snippets, or REPLs showcasing the component and its essential elements
- **Usage:** Guidance on how to use -- and not use -- the component or pattern effectively
- **Behavior:** Notes on expected behavior for assistive technologies, like screen readers, keyboards, switches, etc.
- **Research and Resources:** A list of links to useful sites

## Contribute

### Peruse the Issues

You may find requests for content updates or new documents.

If there's a component missing from the repository or you'd like to see content updated, feel free to start an issue. Barring that, you can always:

### Open a Pull Request

Issues are nice for tracking what might be in the works. But if there's a change you'd like implemented, the quickest way to bring it to life is to do the work and open a pull request.
