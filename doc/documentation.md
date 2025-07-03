
# ![LOGO](../resources/icon/icon.svg) [SOARE](https://github.com/AntoineLandrieux/SOARE/) Language Support documentation

## Table of Contents

- [Setup for Nano](#setup-for-nano)
- [Setup for Notepad++](#setup-for-notepad)

## Setup for Nano

Clone this repository:

```sh
git clone https://github.com/AntoineLandrieux/SoareLanguageSupport
cd SoareLanguageSupport/
```

Copy `soare.nanorc` into `/usr/share/nano/` (**Administrator privileges required**)

```sh
cp Nano/soare.nanorc /usr/share/nano/soare.nanorc
```

Test it with:

```sh
nano MyProgram.soare
```

## Setup for Notepad++

Clone this repository:

**CMD.exe**:

```sh
git clone https://github.com/AntoineLandrieux/SoareLanguageSupport
explorer SoareLanguageSupport/Notepad++
```

**You have two versions**: Dark and Light, choose according to your theme.

- `SoareSupportDarkNotepad++.xml` for dark theme
- `SoareSupportLightNotepad++.xml` for light theme

1. **Open User Defined Language Window**: `Go to Language > User Defined Language > Define your language....`
2. **Import XML File**: Click on the Import... button at the top of the window. Browse to your XML file and select it.
3. **Confirmation**: A popup will appear saying "Import successful". Click **OK**.
4. **Restart Notepad++**: Restart Notepad++ to see your new language in the list.

### Important Considerations

1. **Customization**: You can further customize your language by editing the SoareSupportNotepad++.xml file located in %AppData%\Notepad++.
2. **Backup**: Always backup your SoareSupportNotepad.xml file before making any changes.
3. **Flexibility**: The UDL feature is flexible but may not support all advanced syntax highlighting features
