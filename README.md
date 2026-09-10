# High-Power Rocket: Design, Simulation, and Flight Demonstration

> Student team project - SEDS Rocketry at Arizona State University

[Watch the flight demonstration on YouTube](https://www.youtube.com/watch?v=sOgIDCdu4OA)

![Rocket prepared on the launch rail](docs/images/01-rocket-on-launch-rail.jpg)

## Overview

This repository is a portfolio record of a high-power student rocket project developed through SEDS Rocketry at Arizona State University. The supplied project material describes a vehicle designed toward Level 1 certification, with work centered on structural stability, aerodynamic performance, flight simulation, and recovery-oriented flight design.

The evidence here includes the completed vehicle at the launch site, CAD and exploded views, ANSYS flow-visualization results for the body and fin, an OpenRocket simulation snapshot, a commercial motor reference, and a public flight video. The repository does not assign individual team roles or present the project as a solo build.

## Reported flight result

The supplied project summary reports a flight to **1,900 ft** and a peak near **Mach 0.6**. The linked YouTube video is titled *High Power Rocket Design with Apogee of 1800ft*. Because an altimeter export and flight-data log were not supplied, this repository records the demonstrated result as a **reported 1.8-1.9 kft apogee**, rather than a verified instrumented altitude.

The summary also reports a controlled descent. Recovery, trajectory, and speed claims are retained as project-reported outcomes; their underlying telemetry is not included here.

## Design and analysis evidence

| Evidence | What it documents |
|---|---|
| [CAD assembly](docs/images/03-cad-assembly.png) | Overall vehicle configuration with nose cone, body, fin set, and external feature layout |
| [Exploded view](docs/images/04-exploded-view.png) | Major assembly elements and their relationship |
| [Body CFD view](docs/images/05-body-cfd.png) | Aerodynamic flow-visualization result around the body geometry |
| [Fin CFD view](docs/images/06-fin-cfd.png) | Aerodynamic flow-visualization result around the fin geometry |
| [OpenRocket model](docs/images/07-openrocket-model.png) | Simulated flight configuration, mass properties, stability display, and predicted performance |
| [Motor reference](docs/images/08-motor-reference.png) | Supplied commercial motor specification reference |
| [Project summary](docs/images/09-project-summary.png) | Original SEDS Rocketry ASU project overview and reported results |

![CAD model](docs/images/03-cad-assembly.png)

## Engineering record

- Used CAD to define the vehicle configuration and check the overall assembly.
- Used ANSYS aerodynamic visualization to examine body and fin flow behavior.
- Used OpenRocket to assess stability, thrust-driven trajectory, and predicted flight performance.
- Built and launched the physical vehicle at a desert launch site, as shown in the supplied photographs and video.

See the [analysis record](docs/analysis.md), [flight record](docs/flight-record.md), [media record](docs/media.md), and [team and third-party notes](THIRD_PARTY.md).

## Public documentation scope

This is an engineering portfolio record, not a construction or launch manual. It intentionally excludes propellant formulation, motor manufacture or modification, detailed recovery deployment settings, detailed launch procedures, and original CAD/CFD/OpenRocket source files. The commercial-motor image is included only as provenance for component selection.
