# Function: <code>cgroup_rstat_flush</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81143e70)
Location: kernel/cgroup/rstat.c:199
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff81143e70-ffffffff81143eb3: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114f980)
Location: kernel/cgroup/rstat.c:199
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff8114f980-ffffffff8114f9c3: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115b890)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff8115b890-ffffffff8115b8d5: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811674b0)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff811674b0-ffffffff811674f5: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178e35)
Location: kernel/cgroup/rstat.c:192
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff81178cc0-ffffffff81178d07: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175b4d)
Location: kernel/cgroup/rstat.c:191
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff811759d0-ffffffff81175a17: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811766c3)
Location: kernel/cgroup/rstat.c:198
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memory_stat_format
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff81176540-ffffffff81176587: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119df0e)
Location: kernel/cgroup/rstat.c:198
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff8119dd60-ffffffff8119dda7: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811ce1f5)
Location: kernel/cgroup/rstat.c:204
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff811ce020-ffffffff811ce067: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8121199e)
Location: kernel/cgroup/rstat.c:234
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff81211770-ffffffff812117b7: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81227160)
Location: kernel/cgroup/rstat.c:233
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff81227160-ffffffff812271a0: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123ef70)
Location: kernel/cgroup/rstat.c:272
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:flush_memcg_stats_dwork
  - block/blk-cgroup.c:blkcg_print_stat
```
**Symbols:**

```
ffffffff8123ef70-ffffffff8123efb0: cgroup_rstat_flush (STB_GLOBAL)
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
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d9950)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffff8000101d9950-ffff8000101d99f4: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041c374)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
c041c374-c041c3cc: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c000000000246ac0)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
c000000000246ac0-c000000000246b70: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe000152308)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffe000152308-ffffffe000152394: cgroup_rstat_flush (STB_GLOBAL)
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
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115fad0)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff8115fad0-ffffffff8115fb15: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152d60)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff81152d60-ffffffff81152d9f: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115d8a0)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff8115d8a0-ffffffff8115d8e5: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_rstat_flush(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116ab00)
Location: kernel/cgroup/rstat.c:202
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
**Symbols:**

```
ffffffff8116ab00-ffffffff8116ab37: cgroup_rstat_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
