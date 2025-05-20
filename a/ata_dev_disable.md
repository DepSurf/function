# Function: <code>ata_dev_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d5e50)
Location: drivers/ata/libata-eh.c:1347
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815d5e50-ffffffff815d5ec7: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162f8b0)
Location: drivers/ata/libata-eh.c:1347
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff8162f8b0-ffffffff8162f927: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81660a00)
Location: drivers/ata/libata-eh.c:1347
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff81660a00-ffffffff81660a77: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816759f0)
Location: drivers/ata/libata-eh.c:1348
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff816759f0-ffffffff81675a64: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816df060)
Location: drivers/ata/libata-eh.c:1346
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff816df060-ffffffff816df0d4: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171b860)
Location: drivers/ata/libata-eh.c:1297
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff8171b860-ffffffff8171b8d3: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173e130)
Location: drivers/ata/libata-eh.c:1293
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff8173e130-ffffffff8173e1a3: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81779ca0)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff81779ca0-ffffffff81779d13: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179db00)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff8179db00-ffffffff8179db73: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861b70)
Location: drivers/ata/libata-eh.c:1207
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_unload
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81861a50-ffffffff81861add: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff81861ae0-ffffffff81861b07: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870980)
Location: drivers/ata/libata-eh.c:1207
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_unload
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81870860-ffffffff818708ed: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff818708f0-ffffffff81870917: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81856f94)
Location: drivers/ata/libata-eh.c:1207
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81853080-ffffffff8185310d: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff81853110-ffffffff8185313a: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e5834)
Location: drivers/ata/libata-eh.c:1215
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff818e10c0-ffffffff818e114d: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff818e1150-ffffffff818e117a: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a36b64)
Location: drivers/ata/libata-eh.c:1212
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81ed86c4-ffffffff81ed872b: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff81ed872b-ffffffff81ed8740: ata_dev_disable.cold (STB_LOCAL)
ffffffff81a32a10-ffffffff81a32a45: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bbb83d)
Location: drivers/ata/libata-eh.c:1211
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81bb68a0-ffffffff81bb6932: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff81bb6950-ffffffff81bb698b: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c1309d)
Location: drivers/ata/libata-eh.c:1214
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c0da50-ffffffff81c0db16: ata_dev_disable.part.0 (STB_LOCAL)
ffffffff81c0db30-ffffffff81c0db6b: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c681be)
Location: drivers/ata/libata-eh.c:1220
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c62cb0-ffffffff81c62da1: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a8ff8)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffff8000109a8ff8-ffff8000109a908c: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a78cac)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
c0a78cac-c0a78d38: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6f8e0)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
c000000000a6f8e0-c000000000a6f9c4: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe0006070c0)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffe0006070c0-ffffffe000607148: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81762bf0)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff81762bf0-ffffffff81762c63: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81742a50)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff81742a50-ffffffff81742ac3: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81792980)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff81792980-ffffffff817929f3: ata_dev_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ata_dev_disable(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817ac7c0)
Location: drivers/ata/libata-eh.c:1276
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
```
**Symbols:**

```
ffffffff817ac7c0-ffffffff817ac833: ata_dev_disable (STB_GLOBAL)
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
