
# FLE [(Factorio Learning Environment)](https://jackhopkins.github.io/factorio-learning-environment/) API Specification

This is a temporary project to explore and discuss the features, technologies, and overall design of a (could be) future FLE API.

### Vision

The goal of the FLE API is to serve as a unified entry point for all external Factorio integrations—for example, AI frameworks that need access to Factorio. FLE itself would be an FLE API integration.

### High-Level Overview

The planned architecture includes:

1. **API Specification** – Enables auto-generation of both server and client code.
2. **API Implementation** – Built using the above specification as the foundation.
3. **Factorio Mod** – Provides access to all necessary in-game actions and data.
4. **Containerized Deployment** – Bundles the Factorio headless server, the custom mod, and the API into a single container.

### Collaboration

I've created issues to outline the different layers of the architecture. Feedback is welcome—especially on architecture, feature set, CI/CD, etc.

Feel free to create new issues if you notice missing elements or want to focus discussion on a specific topic.
