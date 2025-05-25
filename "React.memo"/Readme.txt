✅ Summary: When to Use React.memo

| Use Case                        | Memo Tool Needed              |
| ------------------------------- | ----------------------------- |
| Component always renders        | Wrap with `React.memo`        |
| Prop is a function              | Use `useCallback`             |
| Prop is an object/array         | Use `useMemo` or lift outside |
| Props only change conditionally | Use custom comparator         |
