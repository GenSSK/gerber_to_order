# gerber_to_order

A KiCad plugin to create zip compressed gerber files to order for Elecrow, FusionPCB or PCBWay.

# Usage

## Setup

Put this project to ~/.kicad_plugins

```
mkdir ~/.kicad_plugins
cd ~/.kicad_plugins
git clone https://github.com/asukiaaa/gerber_to_order.git
```

## Run

Then start pcbnew of KiCad and select Tools -> External plugins -> Gerber to Order.

# License

MIT

# References

- [Python Plugin Development for Pcbnew](http://docs.kicad-pcb.org/doxygen/md_Documentation_development_pcbnew-plugins.html)
- [KiCad Pcbnew Python Scripting: pcbnew Namespace Reference](http://docs.kicad-pcb.org/doxygen-python/namespacepcbnew.html)
- [KiCad アクションスクリプト GerberZip](https://www.g200kg.com/archives/2019/05/kicad-gerberzip.html)
- [kicad-action-plugins/action_menu_gerber_zip.py](https://github.com/g200kg/kicad-action-plugins/blob/master/action_menu_gerber_zip.py)
