# Swiggy Memory — Health-Aware Ordering Agent

A memory-driven AI system that learns user food habits and optimizes future orders based on health goals (calories, protein, budget).

## Core Idea
Track → Optimize → Execute → Share

- Track user order behavior (time, budget, preferences)
- Convert into structured nutrition insights
- Generate optimized order baskets
- Execute via Swiggy APIs
- Optionally share insights with health platforms

## Example

### Input (user context)
- Time: Tuesday 9PM
- Budget: ₹200
- Goal: Light, high-protein

### Output (generated basket)
- Grilled chicken bowl
- Low-oil wrap
- Water

## Architecture (Simplified)

1. Memory Layer (user behavior)
2. Context Builder (time, intent)
3. Constraint Engine (budget, nutrition)
4. Ranking Engine (behavioral signals)
5. Basket Constructor
6. Confidence Scoring
7. Execution Layer

## Status

Prototype in progress:
- [x] Idea + system design
- [ ] Mock data pipeline
- [ ] Basket generation logic
- [ ] API integration

## Why this matters

Reduces decision friction and increases repeat orders by making ordering predictive instead of reactive.
