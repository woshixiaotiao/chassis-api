# Chassis: API

Shared runtime library of the **Chassis** mod family for **Minecraft 1.21.1 (NeoForge 21.1.262)**.

This repository is a release/distribution home: the built jar is published under
[Releases](https://github.com/woshixiaotiao/chassis-api/releases). Source code is not
mirrored here yet.

## What it is

`chassis_api` (display name **Chassis 0.1.0-a**) provides the shared data model and
service contracts used by Chassis content mods:

- `dev.chassis.api` facade: `LimbPartHurtEvent` / `LimbPartSeveredEvent`, `VitalsProvider`,
  registry and service contracts (`LimbDamageService`, `LimbAware`, `ChassisServices`).
- Shared data model: `LimbData`, `LimbPart`, `BodyModel`.

It ships no content of its own. Install it together with a content mod such as
**Chassis: Limbs** (`chassis-limb`).

## Install

1. Minecraft 1.21.1 + NeoForge 21.1.262 (Java 21).
2. Put **both** jars into your `mods` folder:
   - `chassis-api-0.1.0-a.jar` (this library)
   - `chassis-limb-0.1.0-a.jar` (content, required companion)
3. Optional compatibility, detected at runtime: TaCZ (guns), Jade (body tooltips).

## Downloads

- This repository: <https://github.com/woshixiaotiao/chassis-api/releases>
- Companion mod: <https://github.com/woshixiaotiao/chassis-limb/releases>

Verify downloads with `SHA256SUMS` (attached to every release).