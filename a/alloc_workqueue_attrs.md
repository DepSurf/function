# Function: <code>alloc_workqueue_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b530)
Location: kernel/workqueue.c:3013
Inline: False
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
```
**Symbols:**

```
ffffffff8109b530-ffffffff8109b590: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109eb20)
Location: kernel/workqueue.c:3113
Inline: False
Direct callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
```
**Symbols:**

```
ffffffff8109eb20-ffffffff8109eb86: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a39d0)
Location: kernel/workqueue.c:3139
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810a39d0-ffffffff810a3a5d: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0b30)
Location: kernel/workqueue.c:3138
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810a0b30-ffffffff810a0bd7: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a73b0)
Location: kernel/workqueue.c:3152
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810a73b0-ffffffff810a7457: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3226
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810b028f-ffffffff810b029b: alloc_workqueue_attrs.cold.46 (STB_LOCAL)
ffffffff810adf50-ffffffff810adfef: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3249
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810b93cf-ffffffff810b93db: alloc_workqueue_attrs.cold.47 (STB_LOCAL)
ffffffff810b7060-ffffffff810b7114: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3348
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810ba620-ffffffff810ba6a6: alloc_workqueue_attrs (STB_LOCAL)
ffffffff810bef89-ffffffff810bef95: alloc_workqueue_attrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810c5523-ffffffff810c552f: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810c3170-ffffffff810c31f6: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3354
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff810cd0ce-ffffffff810cd0da: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810cabf0-ffffffff810cac7f: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3360
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff81bdbf2f-ffffffff81bdbf3b: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810c5d20-ffffffff810c5daf: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3361
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffff81bce04c-ffffffff81bce058: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810c7660-ffffffff810c76ef: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3400
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffff81ca5253-ffffffff81ca525f: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810da3c0-ffffffff810da44f: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3383
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81e54b89-ffffffff81e54b95: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810f3ae0-ffffffff810f3b71: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81115cb0)
Location: kernel/workqueue.c:3390
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81115cb0-ffffffff81115dae: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81122a10)
Location: kernel/workqueue.c:3706
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81122a10-ffffffff81122b0e: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112c9e0)
Location: kernel/workqueue.c:3728
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_affinity_strict_store
  - kernel/workqueue.c:wq_affn_scope_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8112c9e0-ffffffff8112cada: alloc_workqueue_attrs (STB_GLOBAL)
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
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010120f38)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffff800010120f38-ffff800010120f80: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0374e84)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
c0374e84-c0374ec8: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016a420)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
c00000000016a420-c00000000016a494: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9eb4)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/padata.c:padata_setup_cpumasks
```
**Symbols:**

```
ffffffe0000d9eb4-ffffffe0000d9ef2: alloc_workqueue_attrs (STB_GLOBAL)
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
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810bf893-ffffffff810bf89f: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810bd4e0-ffffffff810bd566: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810ae0b3-ffffffff810ae0bf: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810abd10-ffffffff810abd96: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810bedf3-ffffffff810bedff: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810bca40-ffffffff810bcac6: alloc_workqueue_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct workqueue_attrs *alloc_workqueue_attrs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3357
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810c715e-ffffffff810c716a: alloc_workqueue_attrs.cold (STB_LOCAL)
ffffffff810c4dc0-ffffffff810c4e46: alloc_workqueue_attrs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
