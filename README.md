# All [Humainary.io](https://humainary.io) Projects

## Description

A humane, open, and extensible approach to software observability and controllability for the Java
platform.

## Modules

This project uses the git submodule feature to include all instrumentation API and reference service
provider implementation (SPI) libraries. This is the preferred way to build the libraries until
there are published as official maven packages elsewhere.

The `modules/api` directory contains the various interface-only instruments libraries.

The `modules/spi` directory contains a reference implementation of each instrument library SPI.

### Substrates

A project that defines some basic interfaces commonly used across all observability software
libraries and technologies.

- [`API`](https://github.com/humainary-io/humainary-substrates-java)
- [`SPI`](https://github.com/substrates-io/substrates-java)
- [`WWW`](https://substrates.io)

### Signals / _OpenSignals_

Inspired by concepts and techniques in signaling theory, stigmergy, systems thinking, semiotics, and
social cognition, OpenSignals offers a humane and scalable way to infer and reason about the state
of systems of services. OpenSignals provides a simplified model and superior means to reframe and
contextualize data collected that is meaningful, relevant, and effective for application monitoring
and service management.

- [`API`](https://github.com/humainary-io/humainary-signals-services-java)
- [`SPI`](https://github.com/opensignals-io/opensignals-services-java)
- [`WWW`](https://opensignals.io)

### Events / _Phaneros_

The Phaneros project aims to fundamentally rethink and reimagine how observability events are
captured, collected, and communicated within high- and low-latency computing environments. The
primary objective of this project is to offer a simplified but highly versatile instrumentation
interface that affords efficient and effective contextualization of emitted phenomenon states within
application and runtime system spaces.

- [`API`](https://github.com/humainary-io/humainary-events-java)
- [`SPI`](https://github.com/phaneros-io/phaneros-events-java)
- [`WWW`](https://phaneros.io)

### Channels / _Kanalis_

The Kanalis project offers a generic data flow interface for in-memory movement of
observability-related data between sources and outlets within an observed process or service. Much
like the Substrates project, it is a project that is utilized by other Humainary projects but at
runtime within the SPI infrastructure. It is observability for observability.

- [`API`](https://github.com/humainary-io/humainary-channels-java)
- [`SPI`](https://github.com/kanalis-io/kanalis-channels-java)
- [`WWW`](https://kanalis.io)

### Counters / _Calculis_

The Calculis project offers a highly efficient implementation of contextually bound counters that
can be used as a building block for other observability instrument libraries and technologies, such
as activity-based resource metering.

- [`API`](https://github.com/humainary-io/humainary-counters-java)
- [`SPI`](https://github.com/calculis-io/calculis-counters-java)
- [`WWW`](https://calculis.io)

### Gauges / _Modulis_

The Modulis project offers a highly efficient implementation of contextually bound gauges that can
be used as a building block for other observability instrument libraries and technologies, such as
adaptive control valves.

- [`API`](https://github.com/humainary-io/humainary-gauges-java)
- [`SPI`](https://github.com/modulis-io/modulis-gauges-java)
- [`WWW`](https://modulis.io)

### Observers / _Inspectis_

The Inspectis project offers an open and extensible observability framework for building, layering,
and composing observers and their state inspection models on top of other protocol (primarily input)
observability instruments.

- [`API`](https://github.com/humainary-io/humainary-observers-java)
- [`SPI`](https://github.com/inspectis-io/inspectis-observers-java)
- [`WWW`](https://inspectis.io)

### Stacks / _Stakks_

The Stakks project offers an open and extensible observability framework for capturing and
collecting contextual execution stacks for named call sites.

- [`API`](https://github.com/humainary-io/humainary-stacks-java)
- [`SPI`](https://github.com/stakks-io/stakks-stacks-java)
- [`WWW`](https://stakks.io)
