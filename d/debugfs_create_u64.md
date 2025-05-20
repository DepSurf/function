# Function: <code>debugfs_create_u64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131e590)
Location: fs/debugfs/file.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - drivers/iommu/amd_iommu.c:amd_iommu_stats_add
```
**Symbols:**

```
ffffffff8131e590-ffffffff8131e5bd: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81353710)
Location: fs/debugfs/file.c:511
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff81353710-ffffffff8135373d: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813699c0)
Location: fs/debugfs/file.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff813699c0-ffffffff813699ed: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e030)
Location: fs/debugfs/file.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff8137e030-ffffffff8137e056: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a2ca0)
Location: fs/debugfs/file.c:550
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff813a2ca0-ffffffff813a2cc6: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d2080)
Location: fs/debugfs/file.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff813d2080-ffffffff813d20a6: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec780)
Location: fs/debugfs/file.c:573
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff813ec780-ffffffff813ec7a6: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814189b0)
Location: fs/debugfs/file.c:569
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff814189b0-ffffffff814189d6: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81432870)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff81432870-ffffffff81432896: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814832e0)
Location: fs/debugfs/file.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff814832e0-ffffffff8148332e: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0970)
Location: fs/debugfs/file.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff814a0970-ffffffff814a09be: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6950)
Location: fs/debugfs/file.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff814a6950-ffffffff814a699e: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fec40)
Location: fs/debugfs/file.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff814fec40-ffffffff814fec8e: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158fb40)
Location: fs/debugfs/file.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff8158fb40-ffffffff8158fbbd: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636e30)
Location: fs/debugfs/file.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
```
**Symbols:**

```
ffffffff81636e30-ffffffff81636ead: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166f2a0)
Location: fs/debugfs/file.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
```
**Symbols:**

```
ffffffff8166f2a0-ffffffff8166f31d: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a9d10)
Location: fs/debugfs/file.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
  - mm/zswap.c:zswap_debugfs_init
```
**Symbols:**

```
ffffffff816a9d10-ffffffff816a9d8d: debugfs_create_u64 (STB_GLOBAL)
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
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010517d50)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffff800010517d50-ffff800010517db0: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d25ac)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
c06d25ac-c06d25fc: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660e60)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
c000000000660e60-c000000000660e8c: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe0003812d8)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffe0003812d8-ffffffe000381332: debugfs_create_u64 (STB_GLOBAL)
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
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142ae50)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff8142ae50-ffffffff8142ae76: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141b8d0)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff8141b8d0-ffffffff8141b8f6: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81426ff0)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff81426ff0-ffffffff81427016: debugfs_create_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_u64(const char *name, umode_t mode, struct dentry *parent, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143deb0)
Location: fs/debugfs/file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:nmi_warning_debugfs
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/frontswap.c:init_frontswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
  - mm/cleancache.c:init_cleancache
```
**Symbols:**

```
ffffffff8143deb0-ffffffff8143ded6: debugfs_create_u64 (STB_GLOBAL)
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
