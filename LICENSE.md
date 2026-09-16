{
    "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json",

    "logo": {
        "padding": {
            "top": 2,
            "left": 2
        },
        "color": {
            "1": "cyan",
            "2": "blue"
        }
    },

    "modules": [
        "break",

        {
            "type": "custom",
            "format": "\u001b[90m╭─────────────── ✦ SYSTEM CORE ✦ ───────────────╮"
        },
        {
            "type": "host",
            "key": "    Machine",
            "keyColor": "green"
        },
        {
            "type": "cpu",
            "key": "  ├─   CPU",
            "keyColor": "green",
            "showPeCoreCount": true,
            "temp": true
        },
        {
            "type": "gpu",
            "key": "  ├─ 󰢮  Graphics",
            "keyColor": "green"
        },
        {
            "type": "memory",
            "key": "  ├─   Memory",
            "keyColor": "green"
        },
        {
            "type": "swap",
            "key": "  ├─ 󰓡  Swap",
            "keyColor": "green"
        },
        {
            "type": "disk",
            "key": "  ├─ 󰋊  Storage",
            "keyColor": "green"
        },
        {
            "type": "display",
            "key": "  ├─ 󰹑  Display",
            "keyColor": "green"
        },
        {
            "type": "sound",
            "key": "  ╰─ 󰕾  Audio",
            "keyColor": "green"
        },
        {
            "type": "custom",
            "format": "\u001b[90m╰────────────────────────────────────────────────╯"
        },

        "break",

        {
            "type": "custom",
            "format": "\u001b[90m╭─────────────── ✦ SOFTWARE ✦ ─────────────────╮"
        },
        {
            "type": "os",
            "key": "    Operating System",
            "keyColor": "yellow"
        },
        {
            "type": "kernel",
            "key": "  ├─   Kernel",
            "keyColor": "yellow"
        },
        {
            "type": "bios",
            "key": "  ├─ 󰒓  Firmware",
            "keyColor": "yellow"
        },
        {
            "type": "packages",
            "key": "  ├─ 󰏖  Packages",
            "keyColor": "yellow"
        },
        {
            "type": "shell",
            "key": "  ╰─   Shell",
            "keyColor": "yellow"
        },
        {
            "type": "custom",
            "format": "\u001b[90m╰────────────────────────────────────────────────╯"
        },

        "break",

        {
            "type": "custom",
            "format": "\u001b[90m╭────────────── ✦ DESKTOP ✦ ───────────────────╮"
        },
        {
            "type": "de",
            "key": "    Desktop",
            "keyColor": "blue"
        },
        {
            "type": "wallpaper",
            "key": "  ├─ 󰸉  Wallpaper",
            "keyColor": "blue"
        },
        {
            "type": "lm",
            "key": "  ├─ 󰍂  Login Manager",
            "keyColor": "blue"
        },
        {
            "type": "wm",
            "key": "  ├─ 󰖲  Window Manager",
            "keyColor": "blue"
        },
        {
            "type": "wmtheme",
            "key": "  ├─ 󰉼  Theme",
            "keyColor": "blue"
        },
        {
            "type": "terminal",
            "key": "  ╰─   Terminal",
            "keyColor": "blue"
        },
        {
            "type": "custom",
            "format": "\u001b[90m╰────────────────────────────────────────────────╯"
        },

        "break",

        {
            "type": "custom",
            "format": "\u001b[90m╭────────────── ✦ TIME CAPSULE ✦ ──────────────╮"
        },
        {
            "type": "command",
            "key": "  󰔟  OS Age",
            "keyColor": "magenta",
            "text": "birth_install=$(stat -c %W / 2>/dev/null); current=$(date +%s); if [ \"$birth_install\" -gt 0 ]; then echo \"$(( (current - birth_install) / 86400 )) days\"; else echo \"unknown\"; fi"
        },
        {
            "type": "uptime",
            "key": "  󰅐  Uptime",
            "keyColor": "magenta"
        },
        {
            "type": "datetime",
            "key": "  󰃰  DateTime",
            "keyColor": "magenta"
        },
        {
            "type": "custom",
            "format": "\u001b[90m╰────────────────────────────────────────────────╯"
        },

        {
            "type": "colors",
            "paddingLeft": 3,
            "symbol": "circle"
        }
    ]
}
