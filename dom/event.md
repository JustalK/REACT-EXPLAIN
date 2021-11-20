# REACT-EXPLAIN: Event

When using a windows event, a protection if is made for protecting error with window not being available in `shared/ExecutionEnvironment`.

```
export const canUseDOM: boolean = !!(
  typeof window !== 'undefined' &&
  typeof window.document !== 'undefined' &&
  typeof window.document.createElement !== 'undefined'
);
```
