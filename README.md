# AI Market Assistant

A Next.js and PostgreSQL hackathon demo helping Kubwa provision shops record stock and helping nearby buyers find estimated availability.

**Demo data is simulated.** Local stock logging, confirmation, buyer discovery, feedback and inventory alerts have been tested. Meta API adapters are implemented but authenticated model execution and English/Pidgin voice quality are still pending. Railway configuration is prepared; the application has not been deployed or submitted.

- [Application setup, verification and architecture](web/README.md)
- [Project instructions and six-task plan](AGENTS.md)
- [Release checklist, workshop findings and Muse handoff](06-demo-release-and-pilot.todo.md)

Open `AI Market Assistant.code-workspace` in VS Code. Application commands run from `web/`:

```sh
npm ci
npm test
npm run lint
npm run build
```

Follow `web/README.md` to configure a private local environment before starting the demo. Environment files, API keys and local demo databases are excluded from this repository.

The supplied Meta Agents 101 workshop demonstrates Muse Spark 1.3; this app defaults to that model for extraction. Using Muse Code to edit a repository and calling a Meta model from the application are separate steps. Neither is proof that all hackathon rules or production launch requirements have passed.
