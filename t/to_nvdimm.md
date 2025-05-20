# Function: <code>to_nvdimm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81598720)
Location: drivers/nvdimm/dimm_devs.c:203
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/dimm_devs.c:validate_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
```
**Symbols:**

```
ffffffff81598720-ffffffff8159873c: to_nvdimm.part.3 (STB_LOCAL)
ffffffff81598740-ffffffff81598769: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff815ee31c)
Location: drivers/nvdimm/dimm_devs.c:203
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff815ee1d0-ffffffff815ee1ec: to_nvdimm.part.3 (STB_LOCAL)
ffffffff815ee1f0-ffffffff815ee21b: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8161b35c)
Location: drivers/nvdimm/dimm_devs.c:212
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
```
**Symbols:**

```
ffffffff8161b2b0-ffffffff8161b2cc: to_nvdimm.part.3 (STB_LOCAL)
ffffffff8161b2d0-ffffffff8161b2fb: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f3fc)
Location: drivers/nvdimm/dimm_devs.c:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
```
**Symbols:**

```
ffffffff8162f360-ffffffff8162f36d: to_nvdimm.part.3 (STB_LOCAL)
ffffffff8162f370-ffffffff8162f39c: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81697bdc)
Location: drivers/nvdimm/dimm_devs.c:228
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
```
**Symbols:**

```
ffffffff81697ad0-ffffffff81697add: to_nvdimm.part.3 (STB_LOCAL)
ffffffff81697ae0-ffffffff81697b0c: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3d35)
Location: drivers/nvdimm/dimm_devs.c:230
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
```
**Symbols:**

```
ffffffff816d3c30-ffffffff816d3c3d: to_nvdimm.part.5 (STB_LOCAL)
ffffffff816d3c40-ffffffff816d3c6b: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f54e5)
Location: drivers/nvdimm/dimm_devs.c:218
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816f5370-ffffffff816f537d: to_nvdimm.part.6 (STB_LOCAL)
ffffffff816f5380-ffffffff816f53ab: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8172ed65)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81730099-ffffffff817300b2: to_nvdimm.part.0 (STB_LOCAL)
ffffffff817300b2-ffffffff817300c4: to_nvdimm.cold (STB_LOCAL)
ffffffff8172ec10-ffffffff8172ec31: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817530a5)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81752ed0-ffffffff81752edd: to_nvdimm.part.0 (STB_LOCAL)
ffffffff81752ee0-ffffffff81752f0b: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81811be5)
Location: drivers/nvdimm/dimm_devs.c:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81811880-ffffffff8181189d: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81820dd5)
Location: drivers/nvdimm/dimm_devs.c:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81820740-ffffffff8182075d: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818040d5)
Location: drivers/nvdimm/dimm_devs.c:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81803a20-ffffffff81803a3d: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e7a5)
Location: drivers/nvdimm/dimm_devs.c:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff8188dc80-ffffffff8188dc9d: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7e15)
Location: drivers/nvdimm/dimm_devs.c:201
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff819d71f0-ffffffff819d7219: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52ca5)
Location: drivers/nvdimm/dimm_devs.c:201
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81b51f70-ffffffff81b51f99: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6155)
Location: drivers/nvdimm/dimm_devs.c:201
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81ba5450-ffffffff81ba5479: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa3d5)
Location: drivers/nvdimm/dimm_devs.c:203
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81bf96d0-ffffffff81bf96f9: to_nvdimm (STB_GLOBAL)
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
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010953934)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffff8000109536d0-ffff8000109536ec: to_nvdimm.part.0 (STB_LOCAL)
ffff8000109536f0-ffff800010953744: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a002d0)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_visible
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
c000000000a002d0-c000000000a00304: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c31d2)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffe0005c2f98-ffffffe0005c2fb4: to_nvdimm.part.0 (STB_LOCAL)
ffffffe0005c2fb4-ffffffe0005c3000: to_nvdimm (STB_GLOBAL)
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
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707795)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff817075c0-ffffffff817075cd: to_nvdimm.part.0 (STB_LOCAL)
ffffffff817075d0-ffffffff817075fb: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816db215)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_dimm_attr_visible
  - drivers/acpi/nfit/core.c:acpi_nfit_dimm_attr_visible
  - drivers/acpi/nfit/core.c:dirty_shutdown_show
  - drivers/acpi/nfit/core.c:id_show
  - drivers/acpi/nfit/core.c:flags_show
  - drivers/acpi/nfit/core.c:dsm_mask_show
  - drivers/acpi/nfit/core.c:family_show
  - drivers/acpi/nfit/core.c:serial_show
  - drivers/acpi/nfit/core.c:formats_show
  - drivers/acpi/nfit/core.c:format1_show
  - drivers/acpi/nfit/core.c:format1_show
  - drivers/acpi/nfit/core.c:format_show
  - drivers/acpi/nfit/core.c:subsystem_device_show
  - drivers/acpi/nfit/core.c:subsystem_rev_id_show
  - drivers/acpi/nfit/core.c:subsystem_vendor_show
  - drivers/acpi/nfit/core.c:device_show
  - drivers/acpi/nfit/core.c:rev_id_show
  - drivers/acpi/nfit/core.c:vendor_show
  - drivers/acpi/nfit/core.c:to_nfit_memdev
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff816db040-ffffffff816db04d: to_nvdimm.part.0 (STB_LOCAL)
ffffffff816db050-ffffffff816db07b: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746565)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff81746390-ffffffff8174639d: to_nvdimm.part.0 (STB_LOCAL)
ffffffff817463a0-ffffffff817463cb: to_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm *to_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817619a5)
Location: drivers/nvdimm/dimm_devs.c:215
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
**Symbols:**

```
ffffffff817617d0-ffffffff817617dd: to_nvdimm.part.0 (STB_LOCAL)
ffffffff817617e0-ffffffff8176180b: to_nvdimm (STB_GLOBAL)
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
