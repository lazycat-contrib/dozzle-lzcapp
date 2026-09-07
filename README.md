# Dozzle for LazyCat

LazyCat LPK packaging for [Dozzle](https://github.com/amir20/dozzle), a realtime log viewer for containers.

## Security

This package uses `compose_override` to mount the LazyCat Docker socket read-only. A read-only socket mount still grants Docker API access and should be treated as host-level privilege. Dozzle shell and container actions are not enabled by this package.
