# Sovrack CLI (`@sovrack/cli`)

The official command-line interface for **Sovrack** — The Open-Core Deployment & Orchestration Platform.

Deploy and operate your Docker applications directly on your own Ubuntu servers from the command line.

## 🚀 Installation

```bash
npm install -g @sovrack/cli
```

Or run directly with npx:

```bash
npx @sovrack/cli --help
```

## 🛠️ Usage

### 1. Authenticate with your Sovrack Master instance
```bash
sovrack login --url https://app.sovrack.com
```

### 2. Deploy your current project
```bash
sovrack deploy --target vps-production
```

### 3. Inspect deployment status and metrics
```bash
sovrack status
```

### 4. Stream real-time container logs
```bash
sovrack logs --follow
```

## 📄 License

Licensed under the Apache-2.0 License.
