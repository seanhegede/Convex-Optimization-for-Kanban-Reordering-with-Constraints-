## Overview

This project demonstrates how to apply **constrained convex optimization** to solve a real-world inventory management problem. Specifically, it optimizes the reorder quantities for consumable items (soap, trash bags, paper towels, toilet paper) in a short-term rental property using the **Lagrange multiplier method** (KKT conditions).

The optimization balances three competing costs:
- **Ordering costs** (fixed cost per order)
- **Holding costs** (storage and capital costs)
- **Constraint penalties** (limited storage space and budget)

## Problem Statement

### Business Context

A short-term rental property manager needs to decide:
- **How many units** of each item to order at a time?
- **When to reorder** (reorder point)?
- **How to minimize total costs** while respecting physical constraints?

### Challenges

1. **Storage is limited** (only 10 shelf units available)
2. **Budget is constrained** (max $500 tied up in inventory)
3. **Multiple items** with different demand rates and costs
4. **Trade-offs** between ordering frequently (high ordering costs) vs. holding large inventory (high storage costs)

## Features

### Core Functionality
- Complete mathematical derivation with all steps shown
- Unconstrained optimization (EOQ formula)
- Constrained optimization (Lagrange multipliers)
- Newton-Raphson solver for finding λ*
- Constraint verification and sensitivity analysis

### Visualizations
- **3D cost surface** with optimal points
- **Bird's-eye contour plots** showing oval level sets
- **Feasible/infeasible region separation**
- **Cross-sectional analysis**
- **Multiple viewing angles**
- **Constraint heatmaps**
