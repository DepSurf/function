# Function: <code>pci_user_read_config_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e730)
Location: drivers/pci/access.c:272
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_pci22_wait
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8142e730-ffffffff8142e805: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479cf0)
Location: drivers/pci/access.c:240
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81479cf0-ffffffff81479dc5: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149b180)
Location: drivers/pci/access.c:252
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8149b180-ffffffff8149b255: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a5330)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814a5330-ffffffff814a5409: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e4160)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814e4160-ffffffff814e4242: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513740)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81513740-ffffffff81513824: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815292c0)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff815292c0-ffffffff815293a4: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815580a0)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff815580a0-ffffffff8155818f: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815796b0)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff815796b0-ffffffff8157979f: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e6e0)
Location: drivers/pci/access.c:255
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_bar_restore
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff8161e6e0-ffffffff8161e7cf: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644f10)
Location: drivers/pci/access.c:255
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_bar_restore
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81644f10-ffffffff81644fff: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816280d0)
Location: drivers/pci/access.c:255
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff816280d0-ffffffff816281bf: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816979d0)
Location: drivers/pci/access.c:255
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff816979d0-ffffffff81697abf: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8240)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_direct_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff817b8240-ffffffff817b833a: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2ba0)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff818d2ba0-ffffffff818d2c9a: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915ba0)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81915ba0-ffffffff81915c9a: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195db10)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8195db10-ffffffff8195dc0a: pci_user_read_config_word (STB_GLOBAL)
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
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106db0b8)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
```
**Symbols:**

```
ffff8000106db0b8-ffff8000106db204: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877704)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
```
**Symbols:**

```
c0877704-c0877818: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000853790)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
```
**Symbols:**

```
c000000000853790-c000000000853930: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b435c)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffe0004b435c-ffffffe0004b4452: pci_user_read_config_word (STB_GLOBAL)
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
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156dbd0)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8156dbd0-ffffffff8156dcbf: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c340)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff8155c340-ffffffff8155c425: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d400)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff8156d400-ffffffff8156d4ef: pci_user_read_config_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_user_read_config_word(struct pci_dev *dev, int pos, u16 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587530)
Location: drivers/pci/access.c:259
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81587530-ffffffff81587616: pci_user_read_config_word (STB_GLOBAL)
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
