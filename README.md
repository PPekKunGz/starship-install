# How to Install Beautiful CMD with Starship
Open Command Prompt(Admin)
<hr/>

```md
- winget install --id Starship.Starship
- winget install clink

!can't find starship.lua go create it.
- %LocalAppData%\clink\starship.lua
- add this in starship.lua
> load(io.popen('starship init cmd'):read("*a"))()

!can't find .config folder go create it.
- go to C:\Users\[name]\.config\starship.toml
https://starship.rs/presets/toml/pastel-powerline.toml

!replace pastel-powerline.toml to starship.toml and copy, past to .config
- restart cmd and go to setting
- select command prompt goto setting font face change to *NotoMono Nerd Font and success
```
```bash
Guide : https://starship.rs/guide/

Preset : https://starship.rs/presets/pastel-powerline

Font: https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Noto.zip

Disable Clink Msg : cmd > clink autorun install -- --quiet
```
![Sonny and Mariel high fiving.](https://i.ibb.co/Ss5JrRb/Screenshot-2024-11-03-002906.png)
