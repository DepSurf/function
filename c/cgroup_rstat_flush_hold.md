# Function: <code>cgroup_rstat_flush_hold</code>

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
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81143f00)
Location: kernel/cgroup/rstat.c:232
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81143f00-ffffffff81143f2e: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114fa10)
Location: kernel/cgroup/rstat.c:232
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8114fa10-ffffffff8114fa3e: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115b920)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8115b920-ffffffff8115b950: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81167540)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81167540-ffffffff81167570: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178f8e)
Location: kernel/cgroup/rstat.c:225
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81178d50-ffffffff81178d82: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175c9e)
Location: kernel/cgroup/rstat.c:224
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81175a60-ffffffff81175a92: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8117681e)
Location: kernel/cgroup/rstat.c:231
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff811765d0-ffffffff81176602: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119e09e)
Location: kernel/cgroup/rstat.c:231
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8119ddf0-ffffffff8119de22: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811ce436)
Location: kernel/cgroup/rstat.c:237
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff811ce0c0-ffffffff811ce0fb: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81211c30)
Location: kernel/cgroup/rstat.c:267
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81211830-ffffffff8121186b: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81227590)
Location: kernel/cgroup/rstat.c:251
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff812271b0-ffffffff812271e4: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123f3a0)
Location: kernel/cgroup/rstat.c:290
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8123efc0-ffffffff8123eff4: cgroup_rstat_flush_hold (STB_GLOBAL)
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
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d9ab0)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffff8000101d9ab0-ffff8000101d9b50: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041c414)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
c041c414-c041c44c: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c000000000246bf0)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
c000000000246bf0-c000000000246c48: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe0001523e8)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffe0001523e8-ffffffe00015242c: cgroup_rstat_flush_hold (STB_GLOBAL)
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
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115fb60)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8115fb60-ffffffff8115fb90: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152de0)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81152de0-ffffffff81152e10: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115d930)
Location: kernel/cgroup/rstat.c:235
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8115d930-ffffffff8115d960: cgroup_rstat_flush_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cgroup_rstat_flush_hold(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116ad7e)
Location: kernel/cgroup/rstat.c:235
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff8116ab80-ffffffff8116abab: cgroup_rstat_flush_hold (STB_GLOBAL)
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
