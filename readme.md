# Nest Http Template

A NestJS template, which used the coolest and fastest stuff.

<img width="727" alt="image" src="https://user-images.githubusercontent.com/41265413/159869110-7704ddc4-d0ac-4cc4-9f34-b7b5568481f9.png">

## Which Tech Stack In Use

- Framework: NestJS (Based on Fastify)
- Language: TypeScript (Best practices, Not AnyScript)
- Database ODM: Typegoose (Write schema once all in TypeScript)
- Bundle Toolchain: @vercel/ncc Bundle (Bundle entry, go node_modules away)
- Testing: Vitest (Test case write in TypeScript, fast and out-of-box)
- Package Manager: PNPM (which is fastest)
- DevOps: Docker
- Other: Prettier, ESLint, Husky, Bump Version, etc.

## How to start development

```bash
npm run dev
```

## File Structure

```
.
├── app.config.ts                 # Main program configuration, database, program, third party, all configurable items
├── app.controller.ts             # Main program root controller
├── app.module.ts                 # The main program root module is responsible for the aggregation of various business modules
├── common                        # Store middleware
│   ├── adapters                  # Adapter configuration
│   ├── decorator                 # Business decorator
│   ├── exceptions                # Custom exception
│   ├── filters                   # Exception handler
│   ├── guard                     # Guarding and Authentication
│   ├── interceptors              # Interceptor, data filtering and response formatting
│   ├── middlewares               # Middleware in the traditional sense
│   └── pipes                     # Pipeline
├── constants                     # Сonstant
├── main.ts                       # Introduce configuration, start the main program, and introduce various global services
├── modules                       # Business logic module
├── processors                      # Core auxiliary modules
│   ├── cache                       # Redis Cache related
│   ├── database                    # Mongo Database related
│   ├── gateway                     # Socket.IO Related
│   ├── helper                      # Auxiliary class
│   └── logger                      # Customize Logger
├── shared                          # General model
│   ├── dto                         # Data validation model
│   ├── interface                   # Interface
│   └── model                       # Basic data model
├── utils                           # Tools
├── bootstrap.ts                    # Bootloader
└── main.ts                         # Entrance

```

## Docs

Please visit [docs](./docs/) folder under this project.

## Authors

[Innei](https://github.com/innei).
