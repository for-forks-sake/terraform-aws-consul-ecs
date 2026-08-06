## v0.10.0-internal-0.1.0

### Changed

* PET-4346
  * controller: extend usage of var.name_prefix to ecs service name
  * controller: allow configuration of ecs desired count.

* PET-4109
  * gateway-task: Ensure 100 min healthy percent
  * gateway-task: Ignore desired count in favour of auto-scaling.

### Fixed

* PET-3594: Fix perpetual drift in terraform when `enable_transparent_proxy` is false.
* PET-4193: Set consul sidecars as essential.
