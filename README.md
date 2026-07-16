# Microservices — 100xSystems

Master the architecture, trade-offs, and real-world patterns behind distributed systems that scale to millions of users.

## Tracks

| Track | Language | Difficulty |
|-------|----------|------------|
| [Spring Boot](curriculum/track-spring-boot/) | Java | Advanced |
| [NestJS](curriculum/track-nestjs/) | TypeScript | Advanced |

## Structure

```
microservices/
├── README.md
├── .gitignore
├── index.md                 # System metadata
└── curriculum/
    ├── track-spring-boot/
    │   ├── module-1-service-decomposition/
    │   ├── module-2-communication-patterns/
    │   ├── module-3-observability/
    │   └── module-4-production-patterns/
    └── track-nestjs/
```

## Contributing

Each lesson is a self-contained folder. To contribute:

1. Clone this repository
2. Navigate to the module where you want to add/edit a lesson
3. Each lesson folder contains `lesson.md` (content) and `tests/` (behavioral tests)
4. Submit a PR

## Validation

This system uses the [100xSystems CLI](https://github.com/100xsystems/cli) for validation.
