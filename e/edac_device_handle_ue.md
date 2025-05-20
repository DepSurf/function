# Function: <code>edac_device_handle_ue</code>

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
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff8175da80)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff8175da80-ffffffff8175db85: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff817cfaf0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff817cfaf0-ffffffff817cfbf5: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff81818f00-ffffffff81818f93: edac_device_handle_ue.cold.14 (STB_LOCAL)
ffffffff81818850-ffffffff818188e0: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff818447a0-ffffffff81844833: edac_device_handle_ue.cold.14 (STB_LOCAL)
ffffffff818440f0-ffffffff81844180: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff81887568-ffffffff81887600: edac_device_handle_ue.cold (STB_LOCAL)
ffffffff81886ed0-ffffffff81886f5e: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff818b9528-ffffffff818b95c0: edac_device_handle_ue.cold (STB_LOCAL)
ffffffff818b8e90-ffffffff818b8f1e: edac_device_handle_ue (STB_GLOBAL)
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
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffff800010b10ec8)
Location: drivers/edac/edac_device.c:600
Inline: False
Direct callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_ecc_irq
```
**Symbols:**

```
ffff800010b10ec8-ffff800010b11008: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (c0bef350)
Location: drivers/edac/edac_device.c:600
Inline: False
Direct callers:
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
```
**Symbols:**

```
c0bef350-c0bef490: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (c000000000c04d00)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
c000000000c04d00-c000000000c04ea4: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffe0006fde78)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffe0006fde78-ffffffe0006fdf80: edac_device_handle_ue (STB_GLOBAL)
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
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff8185f3a8-ffffffff8185f440: edac_device_handle_ue.cold (STB_LOCAL)
ffffffff8185ed10-ffffffff8185ed9e: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff81826978-ffffffff81826a10: edac_device_handle_ue.cold (STB_LOCAL)
ffffffff818262e0-ffffffff8182636e: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff818ae9d8-ffffffff818aea70: edac_device_handle_ue.cold (STB_LOCAL)
ffffffff818ae340-ffffffff818ae3ce: edac_device_handle_ue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void edac_device_handle_ue(struct edac_device_ctl_info *edac_dev, int inst_nr, int block_nr, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:600
Inline: False
```
**Symbols:**

```
ffffffff818cac68-ffffffff818cad00: edac_device_handle_ue.cold (STB_LOCAL)
ffffffff818ca5d0-ffffffff818ca65e: edac_device_handle_ue (STB_GLOBAL)
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
