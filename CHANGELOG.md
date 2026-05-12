# Changelog

## Galpd-J4 v3.3

### Added
- Screen 63 Hz target
- KSM support
- NTFS read-only support
- TCP Westwood default
- Extra TCP congestion algorithms

### Kept from stable base
- CPU OC 1651 MHz
- GPU OC 672 MHz
- CPU input boost 1651 MHz / 100 ms
- Deadline I/O scheduler
- zRAM support, not forced

### Removed / avoided
- GPU 700 MHz removed because performance was worse
- F2FS removed because it failed to build
- Default interactive governor tuning avoided because it caused reboot issues
