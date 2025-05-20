# Function: <code>pci_user_write_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142ead0)
Location: drivers/pci/access.c:275
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_pci22_write
  - drivers/pci/access.c:pci_vpd_pci22_read
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff8142ead0-ffffffff8142eb72: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8147a090)
Location: drivers/pci/access.c:243
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff8147a090-ffffffff8147a12e: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149b510)
Location: drivers/pci/access.c:255
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff8149b510-ffffffff8149b5ae: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a51f0)
Location: drivers/pci/access.c:263
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff814a51f0-ffffffff814a5290: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e4000)
Location: drivers/pci/access.c:263
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff814e4000-ffffffff814e40a6: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513ab0)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff81513ab0-ffffffff81513b5f: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81529160)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff81529160-ffffffff8152920f: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81558370)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff81558370-ffffffff81558428: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579980)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81579980-ffffffff81579a38: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161ea80)
Location: drivers/pci/access.c:258
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_bar_restore
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
```
**Symbols:**

```
ffffffff8161ea80-ffffffff8161eb38: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816452b0)
Location: drivers/pci/access.c:258
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_bar_restore
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
```
**Symbols:**

```
ffffffff816452b0-ffffffff81645368: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627f50)
Location: drivers/pci/access.c:258
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
```
**Symbols:**

```
ffffffff81627f50-ffffffff81628004: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697850)
Location: drivers/pci/access.c:258
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
```
**Symbols:**

```
ffffffff81697850-ffffffff81697904: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8500)
Location: drivers/pci/access.c:263
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
```
**Symbols:**

```
ffffffff817b8500-ffffffff817b85c6: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2e90)
Location: drivers/pci/access.c:263
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff818d2e90-ffffffff818d2f56: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915e90)
Location: drivers/pci/access.c:263
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff81915e90-ffffffff81915f56: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195de00)
Location: drivers/pci/access.c:263
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff8195de00-ffffffff8195dec6: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dae58)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
```
**Symbols:**

```
ffff8000106dae58-ffff8000106daf64: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c08779e4)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
```
**Symbols:**

```
c08779e4-c0877ab8: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000853e10)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_write
```
**Symbols:**

```
c000000000853e10-c000000000853f78: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b46ba)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffe0004b46ba-ffffffe0004b47a0: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156dea0)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff8156dea0-ffffffff8156df58: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c600)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff8155c600-ffffffff8155c6b2: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d6d0)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff8156d6d0-ffffffff8156d788: pci_user_write_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_user_write_config_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815877b0)
Location: drivers/pci/access.c:262
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff815877b0-ffffffff81587862: pci_user_write_config_word (STB_GLOBAL)
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
