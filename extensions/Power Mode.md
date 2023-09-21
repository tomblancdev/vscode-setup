# Power Mode

## [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode)


## Description
This extension adds a power mode to your VS Code.

## Base Settings
```json
{
    // ___ Power Mode ___
    "powermode.enabled": true,
    "powermode.shake.enabled": false,
    "powermode.combo.counterEnabled": "hide",
    "powermode.combo.timerEnabled": "hide", 
}
```

## Custom Modes Settings
### Shark Mode
```json
{
    "powermode.explosions.customCss": {
        "background-color": "transparent",
        "background-size": "contain",
        "background-repeat": "no-repeat",
        "background-position": "center",
    },
    "powermode.explosions.customExplosions": [
        "https://media3.giphy.com/media/l41YdkkvBMkQMNj32/giphy.gif",
        "https://media4.giphy.com/media/l41YuF7W6vxr35dqo/giphy.gif",
        "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExOTRmY2NkMGQ3NDc5MDFiZTcyZmJmNWZhMTVjNjYwM2E0ZDY3ODBjNSZjdD1z/xT8qBkgGpnJ8Af0U92/giphy.gif",
        "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmIxNDE1Y2E2OGI4YTA0NTBlN2EyYWRiNTBjNmYzYWUwODU1YTRjOCZjdD1z/l41YuleZAqmxPrgFq/giphy.gif",
        "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmI2NjQ4MjMxMjM3YjkyNGE2MGMxMjBmNjQ0ZTgzYjQ1ZDQ0MjU1MyZjdD1z/3oEjHVR86eMeXB2eL6/giphy.gif",
    ],
    "powermode.explosions.size": 5,
    "powermode.presets": "flames",
}
```

### Mario Mode
```json
{
    "powermode.explosions.customCss": {
        "background-color": "transparent",
        "background-size": "contain",
        "background-repeat": "no-repeat",
        "background-position": "center",
    },
    "powermode.explosions.customExplosions": [
        "https://media0.giphy.com/media/YqzszOjOBBvMeqYIn9/giphy.gif",
    ],
    "powermode.explosions.size": 5,
    "powermode.presets": "flames",
}
```




