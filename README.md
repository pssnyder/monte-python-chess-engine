# Monte Python Chess Engine

A chess engine inspired by the humor and absurdity of Monty Python. Built on Python and utilizing a Monte Carlo tree search algorithm, it aims to provide a unique and entertaining chess experience.

## Features

- Monte Carlo Tree Search (MCTS) for decision making
- Support for standard chess UCI (Universal Chess Interface) for external integration
- User-friendly interface for both beginners and experienced players

## Special Features
- Unique evaluation function inspired by Monty Python's literal absurdity
- Humorous commentary and responses during gameplay
- Absurd chess variants and scenarios for added entertainment
- Wild setups and rare openings
- Easter eggs and references to Monty Python sketches (Holy Grail, Life of Brian)

## Architecture
1. Engine
   - Core logic for the chess engine
   - Implements the Monte Carlo Tree Search (MCTS) algorithm
   - Handles game state and move generation
   - Calls the evaluation function to assess positions
   - Manages custom transposition tables for openings and move orders (custom pv sequences)
2. Evaluation
   - Implements a unique evaluation function inspired by Monty Python's absurdity
   - Considers unconventional factors in position evaluation
3. UCI Interface
   - Facilitates communication with external chess interfaces
   - Implements the UCI protocol for compatibility
   - Handles time management and move time controls
4. User Interface
   - Provides a graphical interface for users to interact with the engine
   - Displays game state, move suggestions, and commentary