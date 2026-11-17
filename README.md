# gemini-local (private)

Machine- and owner-specific Gemini files kept apart from the portable `gemini` repository: the trusted folders list, the project registry and the project configs. Originals stay where Gemini reads them (`~/.gemini`); this repository is their versioned backup, refreshed by `bun scripts/local-sync.ts` of the `gemini` repository. No history, logs, caches or installation id.
