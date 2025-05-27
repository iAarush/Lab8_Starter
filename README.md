# Lab8-Starter

## How are graceful degradation and service workers related?

Service works allow us to handle activities like caching, network requests, and more. By utilizing service workers, we can make use of caches and fallback content to avoid errors and ugly "default" icons when content isn't available or times out for the user. Service works also allow multithreaded offline work to be done in the users browser, and simulate a "backend" to some extent, allowing us to create a web experience that while degraded, can still be useful for the user when the network is weak or nonexistent. 