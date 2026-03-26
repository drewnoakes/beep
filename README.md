# beep

[![Beep NuGet version](https://img.shields.io/nuget/v/Beep)](https://www.nuget.org/packages/Beep/)
[![Beep NuGet download count](https://img.shields.io/nuget/dt/Beep)](https://www.nuget.org/packages/Beep/)

Command line tool that makes a beep/bell noise.

Useful in command/shell scripts to notify of events such as completion or failure.

## Install

```
dotnet tool install -g beep
```

## Use

```
beep
```

That's it!

## Troubleshooting

If you don't hear a beep, your terminal may have the bell muted.

- **Windows Terminal** — Settings → your profile → Advanced → Bell notification style → Audible
- **VS Code terminal** — add `"terminal.integrated.enableBell": true` to settings
- **macOS Terminal** — Preferences → Profiles → Advanced → Bell → check Audible bell
