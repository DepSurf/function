# Function: <code>debugfs_create_ulong</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131e5c0)
Location: fs/debugfs/file.c:286
Inline: False
```
**Symbols:**

```
ffffffff8131e5c0-ffffffff8131e5ed: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81353740)
Location: fs/debugfs/file.c:560
Inline: False
```
**Symbols:**

```
ffffffff81353740-ffffffff8135376d: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813699f0)
Location: fs/debugfs/file.c:557
Inline: False
```
**Symbols:**

```
ffffffff813699f0-ffffffff81369a1d: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e060)
Location: fs/debugfs/file.c:557
Inline: False
```
**Symbols:**

```
ffffffff8137e060-ffffffff8137e086: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a2cd0)
Location: fs/debugfs/file.c:599
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813a2cd0-ffffffff813a2cf6: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d20b0)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813d20b0-ffffffff813d20d6: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ec7b0)
Location: fs/debugfs/file.c:622
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff813ec7b0-ffffffff813ec7d6: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814189e0)
Location: fs/debugfs/file.c:617
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814189e0-ffffffff81418a06: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814328a0)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814328a0-ffffffff814328c6: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81483100)
Location: fs/debugfs/file.c:595
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_supplies
```
**Symbols:**

```
ffffffff81483100-ffffffff8148314e: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0790)
Location: fs/debugfs/file.c:595
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/power/energy_model.c:em_debug_create_pd
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_supplies
  - drivers/opp/debugfs.c:opp_debug_create_supplies
```
**Symbols:**

```
ffffffff814a0790-ffffffff814a07de: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6860)
Location: fs/debugfs/file.c:595
Inline: False
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814a6860-ffffffff814a68ae: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fec90)
Location: fs/debugfs/file.c:590
Inline: False
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff814fec90-ffffffff814fecde: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158fbc0)
Location: fs/debugfs/file.c:590
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8158fbc0-ffffffff8158fc3d: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636ec0)
Location: fs/debugfs/file.c:606
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81636ec0-ffffffff81636f3d: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166f330)
Location: fs/debugfs/file.c:606
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8166f330-ffffffff8166f3ad: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a9da0)
Location: fs/debugfs/file.c:698
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - kernel/dma/pool.c:dma_atomic_pool_init
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff816a9da0-ffffffff816a9e1d: debugfs_create_ulong (STB_GLOBAL)
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
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010517db0)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffff800010517db0-ffff800010517e10: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d25fc)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c06d25fc-c06d2648: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000660e90)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
c000000000660e90-c000000000660ebc: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe000381332)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffe000381332-ffffffe00038138c: debugfs_create_ulong (STB_GLOBAL)
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
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142ae80)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8142ae80-ffffffff8142aea6: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141b900)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8141b900-ffffffff8141b926: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81427020)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81427020-ffffffff81427046: debugfs_create_ulong (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_create_ulong(const char *name, umode_t mode, struct dentry *parent, long unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143dee0)
Location: fs/debugfs/file.c:620
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8143dee0-ffffffff8143df06: debugfs_create_ulong (STB_GLOBAL)
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
