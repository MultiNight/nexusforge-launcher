# NexusForge Launcher

Custom Windows launcher for the Minecraft modpack **NexusForge Ultimate**
(Minecraft 1.21.1 / NeoForge 21.1.x).

- Microsoft OAuth sign-in (authorization code + PKCE and device code flows)
  so only players who own Minecraft: Java Edition can play online
- Installs Minecraft, NeoForge and mod files from official sources only
- Modpack updates via channel manifest, file verification and repair
- Tokens stored via Windows Credential Manager / DPAPI — never in plaintext
- Free, non-commercial hobby project — no user data collected

Tech: C# / .NET 10 + Avalonia UI.
