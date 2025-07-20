# fetch-weather-mcp

> **🌦️ MCP Project for Weather Data**

This project creates an **MCP** (_Model Context Protocol_) service that consumes a weather API and delivers relevant data. The MCP processes the received information and presents useful insights such as **temperature**, **humidity**, current conditions, and forecasts.

---

## 🏆 _Main Features_

- 🔗 **Connects** to a weather API to fetch real-time data.
- 🧮 **Processes** and filters meteorological information.
- 📊 **Presents** relevant and easy-to-understand weather data.

---

## 🚀 _Getting Started_

### ⚙️ _Requirements_

- **Node.js** (version 18 or higher recommended)

### ▶️ _Running Locally_

To run the project locally, use the following commands:

```sh
npx -y @modelcontextprotocol/inspector
npx -y tsx main.ts
```

---

## 🤖 _Running in Claude Desktop_

To run this project in **Claude Desktop**, add the following configuration to your `claude_desktop_config.json` file:

```json
{
  "mcpServers": {
    "weather": {
      "command": "npx",
      "args": [
        "-y",
        "tsx",
        "PATH/TO/YOUR/PROJECT/main.ts"
      ]
    }
  }
}
```
```
🔴 **Important!**
Where it says `PATH/TO/YOUR/PROJECT/main.ts`, you must put the actual path where you downloaded this project on your PC. For example: `c:/users/your_user/downloads/fetch-weather-mcp/main.ts`
```

---

✨ _Contributions and suggestions are welcome!_