# Multi-Camera 3D Scanning System — Engineering Case Study

> **OSYSTIC ENGINEERING CASE STUDY · PUBLIC SHOWCASE · SANITIZED · PORTFOLIO-SAFE**

This artifact describes a Windows multi-camera 3D-scanning delivery without publishing the confidential implementation, proprietary SDK runtime, client identity or license material.

## Problem & constraints

The system needed to coordinate multiple Intel RealSense depth cameras with a native reconstruction layer and a desktop operator interface while preserving clear separation between hardware acquisition, reconstruction-engine integration, validation and reporting.

Key constraints evidenced by the private repository include:

- Windows desktop deployment
- multiple Intel RealSense D435 cameras
- native C++ camera/reconstruction integration
- RecFusion SDK 2.2 as a licensed/proprietary dependency
- .NET 8 WPF operator UI
- hardware-dependent validation paths
- secure handling of reconstruction license material

## Architecture & decisions

The private implementation separates:

- RealSense acquisition and camera management
- native C++ core/reconstruction interfaces
- RecFusion integration
- dependency/diagnostic checks
- WPF application workflow
- calibration, capture, reconstruction, export and reporting
- isolated direct SDK activation testing

## Contribution & delivery

OSYSTIC retained a structured Visual Studio solution containing the native core, desktop application and direct SDK test project together with CI, runbooks, handover evidence and controlled legacy validation records.

## Evidence & outcomes

The private repository verifies that the multi-camera source architecture, build/handover controls and hardware-validation procedures exist.

The complete native reconstruction path depends on licensed SDK access and physical D435 hardware. This public case study therefore does not claim hardware performance numbers or a universal real-rig pass unless separately supported by approved validation evidence.

## Confidentiality

Excluded from this public artifact:

- confidential implementation source
- proprietary RecFusion binaries
- license keys/tokens
- client identity
- hardware/machine identifiers
- private logs and deployment details

The original engineering repository remains private.


## Public vs. private repository boundary

This repository contains **sanitized public proof only**. The confidential delivery/source repository remains private. Implementation source, client identity, credentials, private infrastructure, payment/contract details, private conversations, and protected raw evidence are intentionally excluded.

Public claims here are limited to the evidence-backed engineering information documented in this repository.
