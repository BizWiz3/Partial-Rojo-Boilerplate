
# Partial-Rojo-Boilerplate

This is a partial Rojo project boilerplate for Roblox development, designed to help you quickly set up a managed workflow with [Rojo](https://github.com/rojo-rbx/rojo), [Wally](https://wally.run/), and [Aftman](https://github.com/LPGhatguy/aftman).

## Usage & Setup

### 1️⃣ Prerequisite: Aftman

You need [Aftman](https://github.com/LPGhatguy/aftman) installed and available in your PATH to use this project.

### 2️⃣ Install Tools and Dependencies

All required tools (like Rojo and Wally) are already configured! To install them, run:

```bash
aftman install
```

Then, install project dependencies with Wally:

```bash
wally install
```

### 3️⃣ Build and Run

To build the place file from source, use:

```bash
rojo build -o "Partial-Rojo-Boilerplate.rbxlx"
```

🛠️ Open `Partial-Rojo-Boilerplate.rbxlx` in Roblox Studio. To sync live changes, start the Rojo server:

```bash
rojo serve
```

📚 For more help, check out [the Rojo documentation](https://rojo.space/docs).
