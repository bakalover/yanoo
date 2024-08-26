# chan
Multi CAS Lock-free rust channel
***
Primary goal - create analogue of kotlin channel with `tokio::sync::broadcast` semantic and integrate it to tokio runtime as well
***
## Performance
***
## Roadmap
- [ ] Implement "infinite array"
- [ ] Optimal array MO
- [ ] Array loom tests
- [ ] Design shared state
- [ ] Design send/recv 
- [ ] Implement send/recv
- [ ] Optimal MO on send/recv
- [ ] send/recv loom tests