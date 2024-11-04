# athena

# Best Development Practices for Production

### Production Checklist

- [ ] Logging to a file has been enabled. This includes proper tagging of info, warn, error - etc.
- [ ] Observability is enabled. For Web Application this means at least a basic heart beat check to see if the services is up.
- [ ] Production Host has proper access levels. This means only opening ports required to be opened to services that require it. Rarely should our servers / services be publicly available.
