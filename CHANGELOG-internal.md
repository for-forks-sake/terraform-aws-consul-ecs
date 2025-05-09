## v0.8.0-internal-0.2.0

### Changed

* [PET-4346]
  * controller - extend usage of var.name_prefix to ecs service name
  * controller - allow configuration of ecs desired count.

## v0.8.0-internal-0.1.0

### Changed

* [PET-4109]
  * Allow gateway task to use internal consul ECR
  * Ensure 100 min healthy percent
  * Ignore desired count
* [PET-4139] Use consul-ecs v0.9.1 to fix health check bug.

### Fixed

* [PET-3594] Fix perpetual drift in terraform when `enable_transparent_proxy` is false.
* [PET-4193] Set consul sidecars as essential.
