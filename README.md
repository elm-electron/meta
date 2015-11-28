# elm-electron

This organization is responsible for providing and maintaining Elm-friendly bindings to [electron's native APIs](https://github.com/atom/electron/tree/master/docs#api-references). In my opinion Elm and electron are a perfect match for building awesome cross-platform applications, but there is no need for everyone to hand code their own interop for electron's built-in stuff. This project is currently ongoing, and none of the packages are in a released state. If you have the time, please help by contributing or downloading and testing the packages in your own projects.

## Remaining work
- [ ] Implement source for all modules available in the renderer process
- [ ] Get native module approval for renderer packages (if this is still required when we get there)
- [ ] Publish v1.0.0 of renderer modules
- [ ] Resolve gaps in APIs that require inter-module dependencies (i.e. `nativeImage` and `clipboard.writeImage()`)
- [ ] Implement testing
- [ ] Implement source for all modules available in the main process
- [ ] Get native module approval for main packages (again, if necessary)
- [ ] Create a website or something maybe?
- [ ] ...
- [ ] Profit! (Actually, don't profit - this is free software)

## Contributing

As you can see there is a lot to do, so any help is greatly appreciated! *All people of any skill level are invited and encouraged to participate* through code contributions, documentation, and open discussion. Let's all learn by doing, encourage varietiy of perspective, and bring even more positive momentum to the Elm community. I myself am brand-new to Elm! Additionally, I would like to encourage mentorship through contribution, so I ask any iterested person with existing Elm experience to create an issue if they are interested in reviewing code as well as writing it.

## Code of Conduct

See CODE_OF_CONDUCT.md
