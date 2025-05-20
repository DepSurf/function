# Function: <code>sanitize_format</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815fd670)
Location: drivers/cdrom/cdrom.c:1561
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff815fd670-ffffffff815fd6e4: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165fed3)
Location: drivers/cdrom/cdrom.c:1561
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff8165d540-ffffffff8165d5bb: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168dcc3)
Location: drivers/cdrom/cdrom.c:1561
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff8168b330-ffffffff8168b3ab: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a4da2)
Location: drivers/cdrom/cdrom.c:1559
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
```
**Symbols:**

```
ffffffff816a23f0-ffffffff816a246a: sanitize_format.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8171010a)
Location: drivers/cdrom/cdrom.c:1559
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
```
**Symbols:**

```
ffffffff8170d6d0-ffffffff8170d74a: sanitize_format.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174d3f8)
Location: drivers/cdrom/cdrom.c:1556
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff8174a530-ffffffff8174a5ae: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81771628)
Location: drivers/cdrom/cdrom.c:1556
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff8176e6a0-ffffffff8176e71e: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817af9f8)
Location: drivers/cdrom/cdrom.c:1557
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff817ac4e0-ffffffff817ac567: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817dfd01)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff817dc7a0-ffffffff817dc827: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ae7bf)
Location: drivers/cdrom/cdrom.c:1567
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff818aaa90-ffffffff818aab19: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bd54f)
Location: drivers/cdrom/cdrom.c:1550
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff818b97b0-ffffffff818b9839: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818a019f)
Location: drivers/cdrom/cdrom.c:1550
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff8189cd00-ffffffff8189cd8b: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff819349af)
Location: drivers/cdrom/cdrom.c:1550
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff81931140-ffffffff819311cb: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a8c86f)
Location: drivers/cdrom/cdrom.c:1551
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff81a880a0-ffffffff81a8813c: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0d75f)
Location: drivers/cdrom/cdrom.c:1551
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff81c091b0-ffffffff81c0924c: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c75bdf)
Location: drivers/cdrom/cdrom.c:1534
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff81c6fed0-ffffffff81c6ff6c: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d2a5df)
Location: drivers/cdrom/cdrom.c:1534
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:cdrom_read_tocentry
  - drivers/cdrom/cdrom.c:cdrom_multisession
```
**Symbols:**

```
ffffffff81d24780-ffffffff81d2481c: sanitize_format (STB_LOCAL)
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
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0c7d0)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffff800010a09ab8-ffff800010a09b88: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae4584)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
c0ae1648-c0ae16f4: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac3d94)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
c000000000abf210-c000000000abf2cc: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe000633cfe)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffe0006308fc-ffffffe000630990: sanitize_format (STB_LOCAL)
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
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817980e1)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff81794b80-ffffffff81794c07: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81789db1)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff81786850-ffffffff817868d7: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d4b81)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff817d1620-ffffffff817d16a7: sanitize_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sanitize_format(union cdrom_addr *addr, u_char *curr, u_char requested);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817eee21)
Location: drivers/cdrom/cdrom.c:1564
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_get_last_written
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
```
**Symbols:**

```
ffffffff817eb8c0-ffffffff817eb947: sanitize_format (STB_LOCAL)
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
