# Structure

```
necro-template/
├── apps/
│   ├── compression-playground/
│   └── hop-visualizer/
├── packages/
│   ├── ui/              # Shared components
│   ├── agent-core/      # Shared types and runner
│   └── config/          # Shared configs
└── .kiro/
```

Apps must import from packages. Do not duplicate shared logic.
