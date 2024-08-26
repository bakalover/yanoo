# chan
Multi CAS Lock-free rust channel
***
Primary goal - create analogue of kotlin channel with `tokio::sync::broadcast` semantic and integrate it to tokio runtime as well
***
## Performance
***
## Roadmap
- [ ] Implement "infinite array"
- [ ] Omptimal array MO
- [ ] Array loom tests
- [ ] Design shared state
- [ ] Design send/recv 
- [ ] Implement send/recv
- [ ] Omptimal MO on send/recv
- [ ] send/recv loom tests