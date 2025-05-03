# Commands

## Lily58

```bash
# Left
qmk flash -kb lily58/rev1 -km vial -e CONVERT_TO=promicro_rp2040 -bl uf2-split-left
mv .build/lily58_rev1_vial_promicro_rp2040.uf2 /mnt/f/Keyboards/Lily58/mine-left.uf2

# Right
qmk flash -kb lily58/rev1 -km vial -e CONVERT_TO=promicro_rp2040 -bl uf2-split-right
mv .build/lily58_rev1_vial_promicro_rp2040.uf2 /mnt/f/Keyboards/Lily58/mine-right.uf2
```
