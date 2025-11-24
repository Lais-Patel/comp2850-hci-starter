# Prototyping Constraints & Trade-offs

## Rendering splits
- Full page: [describe what `/tasks` returns and when it's used]
- Fragment: [describe what `/tasks/fragment` returns and when it's used]

## URL & History
- [Explain how `hx-push-url="true"` maintains browser history]
- [What breaks if you remove it?]

## Accessibility hooks
- [Describe the live region `#status` and its purpose]
- [Explain `aria-describedby` connection between list and result count]
- [Why is result count visually hidden?]

## State management
- [How do query parameters (`q`, `page`) maintain state?]
- [Why must pagination links include the filter query?]

## Performance notes
- Page size: [your choice - justify it]
- Fragment response size vs full page: [estimate bandwidth savings]
- Debounce delay: [300ms - why this value?]

## Future risks
- [What could go wrong with this approach?]
- [Scalability concerns (e.g., 10,000 tasks)?]
- [Template maintenance burden?]

## Accessibility verification

### Keyboard testing
- [Results from Tab navigation test]

### Screen reader testing
- [If available: what was announced when filtering?]

### No-JS parity
- [Confirmation that all features work without JavaScript]
