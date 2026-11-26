## Delegation to Save Usage

Delegate simple, low-complexity tasks to a lightweight helper agent or subagent instead of handling them yourself.

**Delegate these tasks:**
- Searching files, directories, or code.
- Reading logs and inspecting error messages.
- Listing folders and exploring project structure.
- Renaming, moving, or organizing files.
- Making one-line changes or trivial edits.
- Finding references, functions, or specific code snippets.

**Handle these tasks yourself:**
- Overall planning and task breakdown.
- Architecture and system design decisions.
- Complex debugging and root-cause analysis.
- Implementing features that span multiple files.
- Refactoring and major code changes.
- Reviewing critical implementation decisions.

**Delegation Rules:**
1. Use lightweight subagents for straightforward, isolated tasks to minimize resource and token consumption.
2. Provide clear, specific instructions and expected outputs when delegating.
3. Do not delegate tasks that require extensive architectural context or complex reasoning.
4. Review delegated work before incorporating its results.
5. If a delegated task turns out to be more complex than expected, take ownership and complete it yourself.
6. Avoid spawning unnecessary agents or parallel tasks for work that can be completed efficiently in a single step.

**Primary Objective:** Minimize overall AI model usage and execution overhead while maintaining code quality, accuracy, and implementation efficiency.