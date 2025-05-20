# Function: <code>debugfs_create_x32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131e650)
Location: fs/debugfs/file.c:364
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/clk/clk.c:clk_debug_create_one
```
**Symbols:**

```
ffffffff8131e650-ffffffff8131e67d: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813537d0)
Location: fs/debugfs/file.c:642
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/clk/clk.c:clk_debug_create_one
```
**Symbols:**

```
ffffffff813537d0-ffffffff813537fd: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81369a80)
Location: fs/debugfs/file.c:639
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
```
**Symbols:**

```
ffffffff81369a80-ffffffff81369aad: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e0f0)
Location: fs/debugfs/file.c:639
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
```
**Symbols:**

```
ffffffff8137e0f0-ffffffff8137e116: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a2d60)
Location: fs/debugfs/file.c:681
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
```
**Symbols:**

```
ffffffff813a2d60-ffffffff813a2d86: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d2140)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff813d2140-ffffffff813d2166: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec840)
Location: fs/debugfs/file.c:704
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff813ec840-ffffffff813ec866: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81418a70)
Location: fs/debugfs/file.c:699
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff81418a70-ffffffff81418a96: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81432930)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff81432930-ffffffff81432956: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81483380)
Location: fs/debugfs/file.c:677
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff81483380-ffffffff814833ce: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0a10)
Location: fs/debugfs/file.c:677
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814a0a10-ffffffff814a0a5e: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a58a0)
Location: fs/debugfs/file.c:677
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814a58a0-ffffffff814a58ee: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814feba0)
Location: fs/debugfs/file.c:671
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814feba0-ffffffff814febee: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158fa40)
Location: fs/debugfs/file.c:671
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8158fa40-ffffffff8158fabd: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636d10)
Location: fs/debugfs/file.c:687
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff81636d10-ffffffff81636d8d: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166f180)
Location: fs/debugfs/file.c:687
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8166f180-ffffffff8166f1fd: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a9bf0)
Location: fs/debugfs/file.c:779
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
```
**Symbols:**

```
ffffffff816a9bf0-ffffffff816a9c6d: debugfs_create_x32 (STB_GLOBAL)
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
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010517ed8)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffff800010517ed8-ffff800010517f38: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d26dc)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
c06d26dc-c06d272c: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660f20)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
c000000000660f20-c000000000660f4c: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe000381440)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffe000381440-ffffffe00038149a: debugfs_create_x32 (STB_GLOBAL)
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
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142af10)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8142af10-ffffffff8142af36: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141b990)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
```
**Symbols:**

```
ffffffff8141b990-ffffffff8141b9b6: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814270b0)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff814270b0-ffffffff814270d6: debugfs_create_x32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_x32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143df70)
Location: fs/debugfs/file.c:702
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/mmc/core/debugfs.c:mmc_add_card_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
  - drivers/mmc/core/debugfs.c:mmc_add_host_debugfs
```
**Symbols:**

```
ffffffff8143df70-ffffffff8143df96: debugfs_create_x32 (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct dentry *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
