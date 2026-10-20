# Technical overview

The private implementation separates:

- RealSense acquisition and camera management
- native C++ core/reconstruction interfaces
- RecFusion integration
- dependency/diagnostic checks
- WPF application workflow
- calibration, capture, reconstruction, export and reporting
- isolated direct SDK activation testing

## Public engineering boundary

This overview describes the sanitized architecture and engineering decisions only. Confidential implementation source and protected delivery material remain private.
