# Function: <code>debugfs_create_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131e560)
Location: fs/debugfs/file.c:191
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
```
**Symbols:**

```
ffffffff8131e560-ffffffff8131e58d: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813536e0)
Location: fs/debugfs/file.c:464
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
```
**Symbols:**

```
ffffffff813536e0-ffffffff8135370d: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81369990)
Location: fs/debugfs/file.c:461
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
```
**Symbols:**

```
ffffffff81369990-ffffffff813699bd: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e000)
Location: fs/debugfs/file.c:461
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
```
**Symbols:**

```
ffffffff8137e000-ffffffff8137e026: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a2c70)
Location: fs/debugfs/file.c:503
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/clk/clk.c:clk_debug_create_one
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813a2c70-ffffffff813a2c96: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d2050)
Location: fs/debugfs/file.c:524
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813d2050-ffffffff813d2076: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec750)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813ec750-ffffffff813ec776: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81418980)
Location: fs/debugfs/file.c:523
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81418980-ffffffff814189a6: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81432840)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81432840-ffffffff81432866: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81483290)
Location: fs/debugfs/file.c:510
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_bw
  - drivers/opp/debugfs.c:opp_debug_create_bw
```
**Symbols:**

```
ffffffff81483290-ffffffff814832de: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0920)
Location: fs/debugfs/file.c:510
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_bw
  - drivers/opp/debugfs.c:opp_debug_create_bw
```
**Symbols:**

```
ffffffff814a0920-ffffffff814a096e: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6900)
Location: fs/debugfs/file.c:510
Inline: False
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814a6900-ffffffff814a694e: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814febf0)
Location: fs/debugfs/file.c:514
Inline: False
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - kernel/sched/debug.c:sched_init_debug
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814febf0-ffffffff814fec3e: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158fac0)
Location: fs/debugfs/file.c:514
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/hte/hte.c:hte_register_chip
```
**Symbols:**

```
ffffffff8158fac0-ffffffff8158fb3d: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636da0)
Location: fs/debugfs/file.c:530
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/hte/hte.c:hte_register_chip
```
**Symbols:**

```
ffffffff81636da0-ffffffff81636e1d: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166f210)
Location: fs/debugfs/file.c:530
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/hte/hte.c:hte_register_chip
```
**Symbols:**

```
ffffffff8166f210-ffffffff8166f28d: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a9c80)
Location: fs/debugfs/file.c:622
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - kernel/sched/build_utility.c:sched_init_debug
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/hte/hte.c:hte_register_chip
```
**Symbols:**

```
ffffffff816a9c80-ffffffff816a9cfd: debugfs_create_u32 (STB_GLOBAL)
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
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010517cf0)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffff800010517cf0-ffff800010517d50: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d256c)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
  - sound/soc/soc-core.c:snd_soc_instantiate_card
  - sound/soc/soc-pcm.c:dpcm_add_paths
```
**Symbols:**

```
c06d256c-c06d25ac: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660e30)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_init_proc
  - arch/powerpc/platforms/pseries/dtl.c:__machine_initcall_pseries_dtl_init
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c000000000660e30-c000000000660e5c: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe00038127e)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffe00038127e-ffffffe0003812d8: debugfs_create_u32 (STB_GLOBAL)
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
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142ae20)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8142ae20-ffffffff8142ae46: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141b8a0)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8141b8a0-ffffffff8141b8c6: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81426fc0)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81426fc0-ffffffff81426fe6: debugfs_create_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_u32(const char *name, umode_t mode, struct dentry *parent, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143de80)
Location: fs/debugfs/file.c:526
Inline: False
Direct callers:
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:rdev_init_debugfs
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8143de80-ffffffff8143dea6: debugfs_create_u32 (STB_GLOBAL)
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
