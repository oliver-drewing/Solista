# Solista

Solista is an offline-first shopping list application designed for collaborative grocery planning across multiple devices.

The app allows users to manage shopping lists even without a permanent internet connection. Changes are stored locally and synchronized later.

## Problem

Most shopping list apps rely on constant connectivity and centralized cloud services.  
This creates problems when users have limited connectivity in supermarkets or want more control over their data.

Solista explores an offline-first architecture where the application remains fully functional without a network connection.

## Features

- offline-first data storage
- shared shopping lists
- category-based item organization
- store-specific sorting
- multi-user collaboration

## Architecture

Solista follows a layered architecture:

UI  
Compose Multiplatform

Domain  
Business logic and use cases

Data  
Repository pattern with local persistence

Persistence  
SQLDelight database

Synchronization  
Planned support for manual sync and peer-to-peer updates.

## Tech Stack

Kotlin  
Compose Multiplatform  
SQLDelight  
Repository Architecture

## Status

Currently in MVP development.
