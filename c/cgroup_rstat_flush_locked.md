# Function: <code>cgroup_rstat_flush_locked</code>

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
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81143bf0)
Location: kernel/cgroup/rstat.c:149
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff81143bf0-ffffffff81143e64: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114f700)
Location: kernel/cgroup/rstat.c:149
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff8114f700-ffffffff8114f974: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115b600)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff8115b600-ffffffff8115b88e: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81167220)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff81167220-ffffffff811674ae: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178ac0)
Location: kernel/cgroup/rstat.c:142
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
```
**Symbols:**

```
ffffffff81178ac0-ffffffff81178cb3: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175710)
Location: kernel/cgroup/rstat.c:141
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
```
**Symbols:**

```
ffffffff81175710-ffffffff81175903: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811761c0)
Location: kernel/cgroup/rstat.c:148
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
```
**Symbols:**

```
ffffffff811761c0-ffffffff8117646c: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119d790)
Location: kernel/cgroup/rstat.c:148
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
```
**Symbols:**

```
ffffffff8119d790-ffffffff8119db89: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811cda00)
Location: kernel/cgroup/rstat.c:145
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
```
**Symbols:**

```
ffffffff811cda00-ffffffff811cde31: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81211300)
Location: kernel/cgroup/rstat.c:174
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
```
**Symbols:**

```
ffffffff81211300-ffffffff8121175c: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81226d00)
Location: kernel/cgroup/rstat.c:174
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff81226d00-ffffffff81227150: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123e980)
Location: kernel/cgroup/rstat.c:226
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff8123e980-ffffffff8123ef56: cgroup_rstat_flush_locked (STB_LOCAL)
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
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d9638)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffff8000101d9638-ffff8000101d994c: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041bf24)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
c041bf24-c041c374: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c0000000002466f0)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
c0000000002466f0-c000000000246ab8: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe000152072)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffe000152072-ffffffe000152308: cgroup_rstat_flush_locked (STB_LOCAL)
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
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115f840)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff8115f840-ffffffff8115face: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152ad0)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff81152ad0-ffffffff81152d58: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115d610)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff8115d610-ffffffff8115d89e: cgroup_rstat_flush_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_rstat_flush_locked(struct cgroup *cgrp, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116a850)
Location: kernel/cgroup/rstat.c:152
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
**Symbols:**

```
ffffffff8116a850-ffffffff8116aace: cgroup_rstat_flush_locked (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool may_sleep</code>
</li>
</ul>
</details>
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
