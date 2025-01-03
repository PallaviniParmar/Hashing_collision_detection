# Hashing Algorithm in Collision Detection

This repository contains a small Project for the **Digital Electronics** course, focusing on implementing a hashing algorithm for collision detection.

## Project Overview

The project demonstrates:
- A simple hash function: `H(x) = x % 10`.
- Detection of collisions and resolution using chaining.
- Visualization through LED indicators in case of collisions.

### Features:
1. Hash table implementation with 10 buckets.
2. Collision resolution using chaining.
3. Simulated environment to show LED glow for collisions.

## Files Included
- `DE_Assignment.docx`: Documentation of the assignment.
- `Collision.circ`: Circuit file demonstrating a collision scenario.
- `No_Collision.circ`: Circuit file demonstrating no collision.

## Usage
1. Open `.circ` files using [Logisim]or similar tools.
2. Test with various input values to observe collision behavior.

## Examples
- **Collision Scenario:** Input values like 7 and 17 result in the same bucket index, causing a collision.
- **No Collision Scenario:** Input values like 7 and 13 result in different bucket indices, avoiding collisions.


