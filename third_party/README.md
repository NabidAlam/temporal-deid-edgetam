### Third-party dependencies (local clones)

This folder hosts local clones of upstream research repos:
- EdgeTAM (Apache-2.0) — `third_party/edgetam`  
  Ref: `https://github.com/facebookresearch/EdgeTAM.git`
- MaskAnyone — `third_party/maskanyone`  
  Ref: `https://github.com/MaskAnyone/MaskAnyone.git`
- RF-DETR — `third_party/rf-detr`  
  Ref: `https://github.com/roboflow/rf-detr.git`

Use the setup scripts to clone:
- PowerShell: `.\scripts\setup_third_party.ps1`
- Bash: `./scripts/setup_third_party.sh`

After cloning, you can either:
1) pip install in editable mode:
   - `pip install -e third_party/edgetam`
   - `pip install -e third_party/maskanyone`
   - `pip install -e third_party/rf-detr`
2) or add them to `PYTHONPATH` for local imports.


