# Meili Commander

**Meili Commander** is a file management tool for macOS. Its dual-pane layout is inspired by Total Commander, and many of its keyboard shortcuts are borrowed from the Vim editor.

The Chinese word for “beautiful” is 美丽 — or *měilì* in Pinyin. **Meili Commander** is a fork of [_vCommander_](https://github.com/treblam/vCommander), originally created by [@treblam](https://github.com/treblam) from Shenzhen, China. I'm not Chinese, but I enjoy learning Mandarin, so *Meili* was chosen as a tribute to the original project and its creator.

![Meili Commander Snapshot](./vCommander_snapshot.jpg)

Meili Commander's current features include:

- [X] Dual-pane layout  
- [X] Multi-tab interface  
- [X] Keyboard-centric design
- [ ] `#TODO` Support current [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)
- [ ] `#TODO` Support current macOS styling, including Dark Theme

If you're a keyboard-focused user, you might enjoy this tool.

---

## 🛠 Development

- **Language**: Swift 5  
- **IDE**: Xcode 11.3  

---

## `#WIP` ⌨️ Keyboard Shortcuts

Meili Commander offers two modes:

- **Normal Mode**: For users unfamiliar with Vim
- **Vim Mode**: For Vim users and power keyboarders  

Note: All *Normal Mode* shortcuts also work in *Vim mode*.

You can switch modes in **Settings**.


### 🔹 Normal Mode

| Shortcut Key  | Shortcut Hint | Action |
|:--------------|:-------------:|:-------|
| | | |
| 𝕎𝕚𝕟𝕕𝕠𝕨 ℕ𝕒𝕧𝕚𝕘𝕒𝕥𝕚𝕠𝕟 | | |
| | | |
| `Tab`| | Switch focus between left and right panes |
| | | |
| 𝔽𝕚𝕝𝕖 𝕆𝕡𝕖𝕣𝕒𝕥𝕚𝕠𝕟𝕤 | | |
| | | |
| `⌘` `O` | | Open folder under cursor |
| `Enter` | | — |
| `→` | | — |
| `Backspace` | | Go back to parent folder |
| `←` | | — |
| `↑`, `↓` | | Move focus up |
| `↑`, `↓` | | Move focus down |
| `Space` | | Select file — supports multiple files selection |
| `⌘` `Enter` | | Reveal in Finder |
| `⌘` `I`| | File info |
| `F2`| | Rename |
| `F3`| | Preview | 
| `F4`| | Edit — Set Editor in Settings |  
| `F5`| | Copy to other pane |
| `F6`| | Move to other pane |
| `F7`| | New folder |
| `⇧` `F7`| | New file |  
| `F8`| | Delete |
| | | |
| 𝕋𝕒𝕓 𝕄𝕒𝕟𝕒𝕘𝕖𝕞𝕖𝕟𝕥 | | |
| | | |
| `⌘` `T`| New tab  
| `⌘` `W`| Close tab  
| `⌥` `⌘` `←` | Previous tab |
| `⌃` `⇧` `Tab`| |
| `⌥` `⌘` `→` | `⌃` `Tab`| Next tab  
| `⌥` `⌘` `→` | `⌃` `Tab`| Next tab  
| `⌘` `U`| Swap pane tabs  
| `⌘` `E`| Equalise both tabs  
| | | |
| ℂ𝕝𝕚𝕡𝕓𝕠𝕒𝕣𝕕 & 𝔼𝕕𝕚𝕥 | | |
| | | |
| `⌘` `C` | | Copy  |
| `⌘` `V` | | Paste  |
| `⌘` `A` | | Select all  |
| `⌃` `⌘` `C` | | Compare (set tool in Preferences)  |
| | | |
| 𝔽𝕠𝕝𝕕𝕖𝕣 ℕ𝕒𝕧𝕚𝕘𝕒𝕥𝕚𝕠𝕟 | | |
| | | |
| `⇧` `⌘` `G`   |               | Go to folder  |
| `⇧` `⌘` `H`   |               | Home |
| `⇧-⌘-G`       |               | Go to folder      |
| `⇧-⌘-H`       |               | Home      |
| `⇧-⌘-D`       |               | Desktop      |
| `⇧-⌘-A`       |               | Applications      |
| `⇧-⌘-O`       |               | Documents      |
| `⇧-⌘-C`       |               | Root      |
| `⇧-⌘-L`       |               | Downloads      |
| `⇧-⌘-U`       |               | Utilities      |
| | | |
| ℚ𝕦𝕚𝕔𝕜 𝕊𝕖𝕒𝕣𝕔𝕙 | | |
| | | |
| *Type filename*  | | Fuzzy match (Pinyin supported)      |
| `ESC`     | | Clear input      |
| | | |
| 𝔽𝕒𝕧𝕠𝕦𝕣𝕚𝕥𝕖𝕤 | | |
| | | |
| `⌘-D`         |               | Open favourites  |

### 🔸 Vim Mode

| Shortcut Key  | Shortcut Hint | Action |
|:--------------|:-------------:|:-------|
| | | |
| ℕ𝕒𝕧𝕚𝕘𝕒𝕥𝕚𝕠𝕟 | | |
| | | |
| `h` | Go up      |
| `l` | Open folder / file      |
| `j` | Down (`10j` = 10x down)      |
| `k` | Up      |
| `gg` | First item      |
| `G` | Last item      |
| `Ngg` / `NG` | Go to Nth item      |
| `M` | Middle of view      |
| `H` | Top of view      |
| `L` | Bottom of view      |
| | | |
| 𝔽𝕚𝕝𝕖 𝔸𝕔𝕥𝕚𝕠𝕟𝕤 | | |
| | | |
| `S`, `cc` | Rename (select all text)      |
| `i`, `a`, `A` | Rename (cursor at end)      |
| `I` | Rename (cursor at start)      |
| `dd` | Delete item (supports repetition)      |
| `d` | Delete selected items      |
| `yy` | Copy item      |
| `y` | Copy selected      |
| `p` | Paste (supports repetition)      |
| `/` | Search (supports Pinyin)      |
| `⌘ n` | Next match      |
| `⌘ p` | Previous match      |
| | | |
| ℙ𝕒𝕟𝕖𝕤 | | |
| | | |
| `gt` | Next tab      |
| `gT` | Previous tab      |


---


## 📜 License

Licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).:

