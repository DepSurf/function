# Function: <code>cdrom_mode_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815fe190)
Location: drivers/cdrom/cdrom.c:1994
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
```
**Symbols:**

```
ffffffff815fe190-ffffffff815fe1cd: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165e0e0)
Location: drivers/cdrom/cdrom.c:1994
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff8165e0e0-ffffffff8165e11d: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168bed0)
Location: drivers/cdrom/cdrom.c:1994
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff8168bed0-ffffffff8168bf0d: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a0fb0)
Location: drivers/cdrom/cdrom.c:1992
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff816a0fb0-ffffffff816a0fe8: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170c1e0)
Location: drivers/cdrom/cdrom.c:1992
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff8170c1e0-ffffffff8170c21d: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174b560)
Location: drivers/cdrom/cdrom.c:1989
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff8174b560-ffffffff8174b5a0: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8176f780)
Location: drivers/cdrom/cdrom.c:1989
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff8176f780-ffffffff8176f7c0: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ad610)
Location: drivers/cdrom/cdrom.c:1990
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff817ad610-ffffffff817ad650: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817dd8f0)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff817dd8f0-ffffffff817dd930: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818af5e9)
Location: drivers/cdrom/cdrom.c:2000
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
```
**Symbols:**

```
ffffffff818ac730-ffffffff818ac770: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818be369)
Location: drivers/cdrom/cdrom.c:1983
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
```
**Symbols:**

```
ffffffff818bb370-ffffffff818bb3b0: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818a0e19)
Location: drivers/cdrom/cdrom.c:1983
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
```
**Symbols:**

```
ffffffff8189e3e0-ffffffff8189e424: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81935669)
Location: drivers/cdrom/cdrom.c:1983
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
```
**Symbols:**

```
ffffffff819316d0-ffffffff81931714: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a8ce56)
Location: drivers/cdrom/cdrom.c:1985
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff81a88820-ffffffff81a8886f: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0e294)
Location: drivers/cdrom/cdrom.c:1985
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff81c09630-ffffffff81c0967f: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c70350)
Location: drivers/cdrom/cdrom.c:1968
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff81c70350-ffffffff81c7039f: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d24c00)
Location: drivers/cdrom/cdrom.c:1968
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff81d24c00-ffffffff81d24c4f: cdrom_mode_sense (STB_GLOBAL)
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
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0ae98)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffff800010a0ae98-ffff800010a0af10: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae2ac4)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
c0ae2ac4-c0ae2b20: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac0b00)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
c000000000ac0b00-c000000000ac0b78: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe0006319e8)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffe0006319e8-ffffffe000631a6e: cdrom_mode_sense (STB_GLOBAL)
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
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81795cd0)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff81795cd0-ffffffff81795d10: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817879a0)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff817879a0-ffffffff817879e0: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d2770)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff817d2770-ffffffff817d27b0: cdrom_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdrom_mode_sense(struct cdrom_device_info *cdi, struct packet_command *cgc, int page_code, int page_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817eca10)
Location: drivers/cdrom/cdrom.c:1997
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
```
**Symbols:**

```
ffffffff817eca10-ffffffff817eca50: cdrom_mode_sense (STB_GLOBAL)
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
