# Angular Coding Guidelines

## Naming
### short-lived observables
```typescript
devices(id: string): Observable<Device[]> {
   return (/* http stuff */)
   .first();
}
```

### long-lived observables
```typescript
devices$(id: string): Observable<Device[]> {
    return (/* http stuff */);
}
```


## State shape
Domain models (has id)

UI state or singletons
