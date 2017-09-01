# vulkano-win-backport

This is a backport of tomakas `vulkano-win` to use the `winit-0.5.11` API.
The reason for this is that the newer `winit` API is unusable for application development.
So this is a fork, will be kept updated. The only difference to the original is that
it doesn't use the `EventsLoop`-based API.
