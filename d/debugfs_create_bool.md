# Function: <code>debugfs_create_bool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131e710)
Location: fs/debugfs/file.c:537
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff8131e710-ffffffff8131e73d: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81353890)
Location: fs/debugfs/file.c:834
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff81353890-ffffffff813538bd: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81369b40)
Location: fs/debugfs/file.c:831
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff81369b40-ffffffff81369b6d: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e1b0)
Location: fs/debugfs/file.c:831
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff8137e1b0-ffffffff8137e1d6: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a2e20)
Location: fs/debugfs/file.c:873
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813a2e20-ffffffff813a2e46: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d2200)
Location: fs/debugfs/file.c:888
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813d2200-ffffffff813d2226: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec900)
Location: fs/debugfs/file.c:890
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff813ec900-ffffffff813ec926: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81418b30)
Location: fs/debugfs/file.c:884
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81418b30-ffffffff81418b56: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814329f0)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814329f0-ffffffff81432a16: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814830b0)
Location: fs/debugfs/file.c:860
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814830b0-ffffffff814830fe: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0740)
Location: fs/debugfs/file.c:860
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814a0740-ffffffff814a078e: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6810)
Location: fs/debugfs/file.c:859
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dbgfs_register
```
**Symbols:**

```
ffffffff814a6810-ffffffff814a685e: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fe970)
Location: fs/debugfs/file.c:844
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
```
**Symbols:**

```
ffffffff814fe970-ffffffff814fe9be: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158f740)
Location: fs/debugfs/file.c:844
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_debug
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
```
**Symbols:**

```
ffffffff8158f740-ffffffff8158f7bd: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636ad0)
Location: fs/debugfs/file.c:860
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_debug
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
```
**Symbols:**

```
ffffffff81636ad0-ffffffff81636b4d: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166ef40)
Location: fs/debugfs/file.c:860
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dbgfs_register
```
**Symbols:**

```
ffffffff8166ef40-ffffffff8166efbd: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a9920)
Location: fs/debugfs/file.c:952
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff816a9920-ffffffff816a999d: debugfs_create_bool (STB_GLOBAL)
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
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010518060)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - arch/arm64/kernel/debug-monitors.c:create_debug_debugfs_entry
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffff800010518060-ffff8000105180c0: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d280c)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c06d280c-c06d2858: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660fe0)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - arch/powerpc/mm/book3s64/pgtable.c:pgtable_debugfs_setup
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c000000000660fe0-c00000000066100c: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe0003815a8)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffe0003815a8-ffffffe000381602: debugfs_create_bool (STB_GLOBAL)
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
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142afd0)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8142afd0-ffffffff8142aff6: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141ba50)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8141ba50-ffffffff8141ba76: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81427170)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81427170-ffffffff81427196: debugfs_create_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_bool(const char *name, umode_t mode, struct dentry *parent, bool *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143e030)
Location: fs/debugfs/file.c:887
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_init_debug
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8143e030-ffffffff8143e056: debugfs_create_bool (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct dentry *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
