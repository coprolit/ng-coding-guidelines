# Angular Coding Guidelines

## Naming
### short-lived observables
```typescript
    getLessons(id: string): Observable<Lesson[]> {
	   return (/* http stuff */)
        .first();
    }
```

### long-lived observables
    lessons$(id: string): Observable<Lesson[]> {
	    return (/* http stuff */);
    }


## State shape
Domain models (has id)

UI state or singletons
