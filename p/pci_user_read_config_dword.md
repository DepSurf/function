# Function: <code>pci_user_read_config_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142ed70)
Location: drivers/pci/access.c:273
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_pci22_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8142ed70-ffffffff8142ee44: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8147a350)
Location: drivers/pci/access.c:241
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8147a350-ffffffff8147a424: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149b7d0)
Location: drivers/pci/access.c:253
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8149b7d0-ffffffff8149b8a4: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4f60)
Location: drivers/pci/access.c:261
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814a4f60-ffffffff814a5038: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3d50)
Location: drivers/pci/access.c:261
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814e3d50-ffffffff814e3e31: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513b60)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81513b60-ffffffff81513c43: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528ea0)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81528ea0-ffffffff81528f83: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815584f0)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff815584f0-ffffffff815585de: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81579b00)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81579b00-ffffffff81579bee: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161eb40)
Location: drivers/pci/access.c:256
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff8161eb40-ffffffff8161ec2e: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81645370)
Location: drivers/pci/access.c:256
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81645370-ffffffff8164545e: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627c70)
Location: drivers/pci/access.c:256
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81627c70-ffffffff81627d5e: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697570)
Location: drivers/pci/access.c:256
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81697570-ffffffff8169765e: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8340)
Location: drivers/pci/access.c:261
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_direct_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff817b8340-ffffffff817b8437: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d2cb0)
Location: drivers/pci/access.c:261
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff818d2cb0-ffffffff818d2da7: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81915cb0)
Location: drivers/pci/access.c:261
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81915cb0-ffffffff81915da7: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195dc20)
Location: drivers/pci/access.c:261
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8195dc20-ffffffff8195dd17: pci_user_read_config_dword (STB_GLOBAL)
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
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106daf68)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
```
**Symbols:**

```
ffff8000106daf68-ffff8000106db0b8: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877818)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
```
**Symbols:**

```
c0877818-c087792c: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0000000008540f0)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
```
**Symbols:**

```
c0000000008540f0-c000000000854290: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b4886)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffe0004b4886-ffffffe0004b497c: pci_user_read_config_dword (STB_GLOBAL)
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
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156e020)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8156e020-ffffffff8156e10e: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c780)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff8155c780-ffffffff8155c864: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d850)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff8156d850-ffffffff8156d93e: pci_user_read_config_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_user_read_config_dword(struct pci_dev *dev, int pos, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587620)
Location: drivers/pci/access.c:260
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_user_config_read
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
```
**Symbols:**

```
ffffffff81587620-ffffffff81587705: pci_user_read_config_dword (STB_GLOBAL)
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
