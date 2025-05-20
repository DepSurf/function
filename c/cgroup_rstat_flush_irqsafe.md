# Function: <code>cgroup_rstat_flush_irqsafe</code>

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
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81143ec0)
Location: kernel/cgroup/rstat.c:214
Inline: False
```
**Symbols:**

```
ffffffff81143ec0-ffffffff81143efc: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114f9d0)
Location: kernel/cgroup/rstat.c:214
Inline: False
```
**Symbols:**

```
ffffffff8114f9d0-ffffffff8114fa0c: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115b8e0)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffff8115b8e0-ffffffff8115b91e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81167500)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffff81167500-ffffffff8116753e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178d10)
Location: kernel/cgroup/rstat.c:207
Inline: False
```
**Symbols:**

```
ffffffff81178d10-ffffffff81178d4e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175a20)
Location: kernel/cgroup/rstat.c:206
Inline: False
```
**Symbols:**

```
ffffffff81175a20-ffffffff81175a5e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81176590)
Location: kernel/cgroup/rstat.c:213
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
```
**Symbols:**

```
ffffffff81176590-ffffffff811765ce: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119ddb0)
Location: kernel/cgroup/rstat.c:213
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
**Symbols:**

```
ffffffff8119ddb0-ffffffff8119ddee: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811ce070)
Location: kernel/cgroup/rstat.c:219
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
**Symbols:**

```
ffffffff811ce070-ffffffff811ce0b6: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff812117d0)
Location: kernel/cgroup/rstat.c:249
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
**Symbols:**

```
ffffffff812117d0-ffffffff81211816: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
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
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d99f8)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffff8000101d99f8-ffff8000101d9aac: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041c3cc)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
c041c3cc-c041c414: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c000000000246b70)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
c000000000246b70-c000000000246bec: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe000152394)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffe000152394-ffffffe0001523e8: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
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
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115fb20)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffff8115fb20-ffffffff8115fb5e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152da0)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffff81152da0-ffffffff81152dde: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115d8f0)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffff8115d8f0-ffffffff8115d92e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_rstat_flush_irqsafe(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116ab40)
Location: kernel/cgroup/rstat.c:217
Inline: False
```
**Symbols:**

```
ffffffff8116ab40-ffffffff8116ab7e: cgroup_rstat_flush_irqsafe (STB_GLOBAL)
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
