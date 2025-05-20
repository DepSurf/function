# Function: <code>edac_device_handle_ce</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff8175d8d0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff8175d8d0-ffffffff8175d98d: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff817cf940)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff817cf940-ffffffff817cf9fd: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff81818e97-ffffffff81818f00: edac_device_handle_ce.cold.13 (STB_LOCAL)
ffffffff818186f0-ffffffff81818759: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff81844737-ffffffff818447a0: edac_device_handle_ce.cold.13 (STB_LOCAL)
ffffffff81843f90-ffffffff81843ff9: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff818874fa-ffffffff81887568: edac_device_handle_ce.cold (STB_LOCAL)
ffffffff81886d60-ffffffff81886dcb: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff818b94ba-ffffffff818b9528: edac_device_handle_ce.cold (STB_LOCAL)
ffffffff818b8d20-ffffffff818b8d8b: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffff800010b10cd8)
Location: drivers/edac/edac_device.c:558
Inline: False
Direct callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_ecc_irq
```
**Symbols:**

```
ffff800010b10cd8-ffff800010b10ddc: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (c0bef14c)
Location: drivers/edac/edac_device.c:558
Inline: False
Direct callers:
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
```
**Symbols:**

```
c0bef14c-c0bef25c: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (c000000000c04a70)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
c000000000c04a70-c000000000c04bb0: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffe0006fdcd6)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffe0006fdcd6-ffffffe0006fdda6: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff8185f33a-ffffffff8185f3a8: edac_device_handle_ce.cold (STB_LOCAL)
ffffffff8185eba0-ffffffff8185ec0b: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff8182690a-ffffffff81826978: edac_device_handle_ce.cold (STB_LOCAL)
ffffffff81826170-ffffffff818261db: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff818ae96a-ffffffff818ae9d8: edac_device_handle_ce.cold (STB_LOCAL)
ffffffff818ae1d0-ffffffff818ae23b: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ce(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:558
Inline: False
```
**Symbols:**

```
ffffffff818cabfa-ffffffff818cac68: edac_device_handle_ce.cold (STB_LOCAL)
ffffffff818ca460-ffffffff818ca4cb: edac_device_handle_ce (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
