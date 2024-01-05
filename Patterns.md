# Patterns
- Context, Problem, Solution

## Module patterns

### Layered
- Each layer serves the layer just above itself.

- Simple:
![img](imgs/pattern-layered_simple.png)
![img](imgs/pattern-layered_sidecar.png)

- With sidecar(sidebar):
![img](imgs/pattern-layered_simple_sc.png)

- With open/closed jump flow
![img](imgs/pattern-layered_open.png)

- Not a layered architecture (a wolf in layer clothing):
![img](imgs/pattern-layered_not.png)

## Component & Conector patterns
### Broker Pattern
![img](imgs/pattern-broker.png)

### MVC
![img](imgs/pattern-mvc.png)

### Pipe and filter
- Usable when we know the whole workflow
- Not good for interactive systems (it's static)

### Client-Server Pattern
- Server can be
	- performance bottleneck
	- single point of failure

### Peer-to-Peer Pattern
- Each component can be client or server at any time
- Weekness
	- security
	- data consistency
	- backup and recovery

### Service-Oriented Architecture Pattern (SOA)
- Elements
	- Service consumer
	- Service provider
	- Service registry: is a repository for services.
	- ESB
	- Orchestration
- Complex to build
- Performance overhead

### Publish-Subscribe Pattern
- List-based
- Broadcast-based
- Content-based

### Shared-Data Pattern
- data does not belong solely to any one of those components
- data accessors, shared-data store, synchronizer
- use of locks: SIX (shared, intent, exclusive)

## Allocation Patterns

### Map-Reduce Pattern
- need: quickly analyze enormous volumes of data
- efficiently perform a distributed and parallel sort of a large data set and provide a simple means
- key1: map function
- key2: used for sorting

### Multi-tier Pattern