# Flash On Stellar - Smart Contract Documentation

## Overview
A Stellar smart contract designed for managing decentralized storage units. The contract facilitates interactions between storage providers and consumers while maintaining secure and efficient storage allocation.

## Core Structure

### Provider Management
- Providers can register on the contract
- Providers can register storage units, accessed through an endpoint
- Each unit has specified capacity and a status.
- Providers can manage unit status and maintenance/decommissioning.

### Consumer Management
- Consumers can register on the contract
- Ability to make storage reservations
- Track consumer usage and history

### Unit States
- Available
- Reserved
- InUse
- Maintenance
- Decommissioning

## Key Features

### Provider Operations
- Unit registration and management
- Maintenance scheduling
- Decommissioning process
- Usage tracking

### Consumer Operations
- Registration system
- Reservation management
- Space allocation tracking

### System Management
- Statistics tracking
- Capacity monitoring
- Usage metrics for both consumer and provider sides

## Security Features

- Owner-specific operation controls
- Strict validation checks
- Caller authentication system
- Controlled status transitions

## Technical Details

- Built on Stellar blockchain
- Storage tracking in gigabytes
- Unique ID system for units
- Persistent storage management with scaling capabilities
- Maintenance window scheduling
