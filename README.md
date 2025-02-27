# accessibility-testing
This repository houses a sample website that can be utilized for WAVE and AXE accessibility testing.

# List of Intentional Accessibility Errors

1. **Missing Language Attribute**:
   - The `<html>` element does not include a `lang` attribute, which is essential for screen readers.

2. **Missing Alt Text for Images**:
   - The `<img>` element is missing an `alt` attribute to describe the image content.

3. **Link Without Href**:
   - One of the navigation links is missing an `href` attribute, which can confuse users and assistive technologies.

4. **Deprecated Element**:
   - The use of the `<marquee>` tag is outdated and not supported in modern accessibility standards.

5. **Low Color Contrast**:
   - The body text color (`#666`) on a white background and the text in the marquee (where the text and background colors are nearly identical) may not meet contrast guidelines.

6. **Missing Form Labels**:
   - Input fields and the textarea in the contact form do not have associated `<label>` elements, making them inaccessible for screen reader users.

7. **Improper Heading Structure**:
   - The headings are out-of-order (e.g., using `<h4>` followed by `<h2>`), which can confuse assistive technologies about the document structure.

8. **Non-Descriptive Link Text**:
   - The link text “here” does not provide sufficient context about its destination.

9. **Potential Table Accessibility Issues**:
   - The table, while simple, lacks `scope` attributes or summaries that can assist screen readers in interpreting its data.

10. **Missing Skip Navigation Link**:
    - There is no “skip to main content” link, which is a best practice for keyboard navigation.
