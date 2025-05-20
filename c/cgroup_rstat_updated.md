# Function: <code>cgroup_rstat_updated</code>

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
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81143af0)
Location: kernel/cgroup/rstat.c:24
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff81143af0-ffffffff81143bef: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114f600)
Location: kernel/cgroup/rstat.c:24
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff8114f600-ffffffff8114f6ff: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115b540)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff8115b540-ffffffff8115b5fe: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81167160)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff81167160-ffffffff8116721d: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178890)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - block/blk-core.c:blkcg_bio_issue_check
```
**Symbols:**

```
ffffffff81178890-ffffffff81178942: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175910)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff81175910-ffffffff811759c2: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81176470)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff81176470-ffffffff81176538: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119db90)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff8119db90-ffffffff8119dd56: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811cde40)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff811cde40-ffffffff811ce018: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff812110f0)
Location: kernel/cgroup/rstat.c:29
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff812110f0-ffffffff812112c8: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81226af0)
Location: kernel/cgroup/rstat.c:29
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff81226af0-ffffffff81226cc8: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123e760)
Location: kernel/cgroup/rstat.c:29
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
**Symbols:**

```
ffffffff8123e760-ffffffff8123e94d: cgroup_rstat_updated (STB_GLOBAL)
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
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d94c8)
Location: kernel/cgroup/rstat.c:25
Inline: False
```
**Symbols:**

```
ffff8000101d94c8-ffff8000101d95f8: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041be68)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
c041be68-c041bf24: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c0000000002465d0)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
c0000000002465d0-c0000000002466e8: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe000151fb0)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffe000151fb0-ffffffe000152072: cgroup_rstat_updated (STB_GLOBAL)
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
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115f780)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff8115f780-ffffffff8115f83d: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152a10)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff81152a10-ffffffff81152acd: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115d550)
Location: kernel/cgroup/rstat.c:25
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
**Symbols:**

```
ffffffff8115d550-ffffffff8115d60d: cgroup_rstat_updated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_rstat_updated(struct cgroup *cgrp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116a790)
Location: kernel/cgroup/rstat.c:25
Inline: False
```
**Symbols:**

```
ffffffff8116a790-ffffffff8116a84d: cgroup_rstat_updated (STB_GLOBAL)
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
