# Function: <code>release_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155ef70)
Location: drivers/base/firmware_class.c:1245
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8155ef70-ffffffff8155efd6: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b34b0)
Location: drivers/base/firmware_class.c:1293
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815b34b0-ffffffff815b3516: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e2840)
Location: drivers/base/firmware_class.c:1328
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff815e2840-ffffffff815e28a6: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f7cd4)
Location: drivers/base/firmware_class.c:1328
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff815f7370-ffffffff815f73d9: release_firmware.part.12 (STB_LOCAL)
ffffffff815f73e0-ffffffff815f73f7: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165fc83)
Location: drivers/base/firmware_class.c:1335
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8165f4f0-ffffffff8165f559: release_firmware.part.12 (STB_LOCAL)
ffffffff8165f560-ffffffff8165f577: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169ab43)
Location: drivers/base/firmware_loader/main.c:746
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8169a470-ffffffff8169a4d0: release_firmware.part.9 (STB_LOCAL)
ffffffff8169a4d0-ffffffff8169a4e6: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb34b)
Location: drivers/base/firmware_loader/main.c:755
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff816bae50-ffffffff816baeb0: release_firmware.part.9 (STB_LOCAL)
ffffffff816baeb0-ffffffff816baec6: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5b45)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff816f5390-ffffffff816f53f6: release_firmware.part.0 (STB_LOCAL)
ffffffff816f5400-ffffffff816f5416: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719f45)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
ffffffff81719790-ffffffff817197f6: release_firmware.part.0 (STB_LOCAL)
ffffffff81719800-ffffffff81719816: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5f6d)
Location: drivers/base/firmware_loader/main.c:976
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
ffffffff817d55f0-ffffffff817d565a: release_firmware.part.0 (STB_LOCAL)
ffffffff817d5660-ffffffff817d5676: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea9de)
Location: drivers/base/firmware_loader/main.c:1049
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff817e9ec0-ffffffff817e9f2a: release_firmware.part.0 (STB_LOCAL)
ffffffff817e9f30-ffffffff817e9f46: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cf174)
Location: drivers/base/firmware_loader/main.c:1053
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff817ce5d0-ffffffff817ce63a: release_firmware.part.0 (STB_LOCAL)
ffffffff817ce640-ffffffff817ce656: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81859859)
Location: drivers/base/firmware_loader/main.c:1052
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff81858e80-ffffffff81858eea: release_firmware.part.0 (STB_LOCAL)
ffffffff81858ef0-ffffffff81858f06: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a0459)
Location: drivers/base/firmware_loader/main.c:1077
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff8199fbe0-ffffffff8199fc4c: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11fe4)
Location: drivers/base/firmware_loader/main.c:1077
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff81b116a0-ffffffff81b1170c: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b602d4)
Location: drivers/base/firmware_loader/main.c:1132
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff81b5f930-ffffffff81b5f99c: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3d14)
Location: drivers/base/firmware_loader/main.c:1133
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_flash_update_doit
```
**Symbols:**

```
ffffffff81bb3340-ffffffff81bb33ac: release_firmware (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d69c)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
ffff80001090cb40-ffff80001090cbd0: release_firmware.part.0 (STB_LOCAL)
ffff80001090cbd0-ffff80001090cc00: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f66fc)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
c09f5bc4-c09f5c40: release_firmware.part.0 (STB_LOCAL)
c09f5c40-c09f5c64: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009adc44)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
c0000000009ac660-c0000000009ac730: release_firmware.part.0 (STB_LOCAL)
c0000000009ac730-c0000000009ac74c: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000592164)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffe00059197c-ffffffe000591b18: release_firmware.part.0 (STB_LOCAL)
ffffffe000591b18-ffffffe000591b44: release_firmware (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e0275)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
ffffffff816dfac0-ffffffff816dfb26: release_firmware.part.0 (STB_LOCAL)
ffffffff816dfb30-ffffffff816dfb46: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba8b5)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816ba100-ffffffff816ba166: release_firmware.part.0 (STB_LOCAL)
ffffffff816ba170-ffffffff816ba186: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d8b8)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8170d1e0-ffffffff8170d246: release_firmware.part.0 (STB_LOCAL)
ffffffff8170d250-ffffffff8170d266: release_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void release_firmware(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817285a6)
Location: drivers/base/firmware_loader/main.c:945
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_core.c:rproc_auto_boot_callback
```
**Symbols:**

```
ffffffff81727c90-ffffffff81727cf6: release_firmware.part.0 (STB_LOCAL)
ffffffff81727d00-ffffffff81727d16: release_firmware (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
