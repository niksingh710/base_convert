# Base Converter

A SImple base Converter Script written in python.

| Base        | Prefixes can be used           |
| ----------- | ------------------------------ |
| Binary      | "Binary", "b", "B", "2", "bin" |
| Hexadecimal | "Hexadecimal", "h", "H", "16"  |
| Decimal     | "Decimal", "d", "D", "2"       |
| Octal       | "Octal", "o" , "O" ,"8"        |

use : `base-convert value valueBase-toConverted Optional "-c", "--clean"`

`base-convert 123 d-h` This will give decimal to hexadecimal Conversion

`base-convert 123 d` This will give decimal to all Conversion

`base-convert 123 o` This will give octal to all Conversion

`base-convert 123` This will give decimal to all Conversion....etc

Use `--help` to get help menu.

## Requirements

Python3 must be installed.

Exec this command to get the python3 path.
`which python3`

Make sure the output is '/usr/bin/python3'.

If output does not match then try to install python from package manager.

### UBUNTU/DEBIAN or derivatives

`sudo apt install python3`

if Python installation is well and output mathes you are good to go.

```
git clone https://github.com/niksingh710/base_convert.git
cd ./base_convert
chmod +x base-convert
sudo cp base-convert /usr/local/bin/
```

#### TO Remove

```
sudo rm /usr/local/bin/base-convert
```

After this restart your Terminal app.

## Windows

windows user need to clone the repository. or can download the zip file from clone section.
and then rename the file named base-convert to base-convert.py

then run the script using python.

## TODO

- [x] Handle negative value for conversion
- [ ] Add Fraction Conversion possibility to.
