# Function: <code>cgroup_task_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81118b33)
Location: kernel/cgroup.c:3736
Inline: True
Inline callers:
  - kernel/cgroup.c:pidlist_array_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811207b2)
Location: kernel/cgroup.c:3925
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81128c9f)
Location: kernel/cgroup.c:3936
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a0a0)
Location: kernel/cgroup/cgroup-v1.c:338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff8112a0a0-ffffffff8112a104: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81136ea0)
Location: kernel/cgroup/cgroup-v1.c:343
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81136ea0-ffffffff81136f07: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81145680)
Location: kernel/cgroup/cgroup-v1.c:343
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81145680-ffffffff811456e7: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81151240)
Location: kernel/cgroup/cgroup-v1.c:346
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81151240-ffffffff811512a7: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811550e0)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff811550e0-ffffffff8115514b: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160d10)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81160d10-ffffffff81160d7b: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172360)
Location: kernel/cgroup/cgroup.c:612
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81172360-ffffffff811723ce: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f000)
Location: kernel/cgroup/cgroup.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8116f000-ffffffff8116f06e: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116fc30)
Location: kernel/cgroup/cgroup.c:609
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8116fc30-ffffffff8116fc9e: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81195ff0)
Location: kernel/cgroup/cgroup.c:640
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81195ff0-ffffffff8119605e: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c5ef0)
Location: kernel/cgroup/cgroup.c:641
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff811c5ef0-ffffffff811c5f59: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81208990)
Location: kernel/cgroup/cgroup.c:646
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81208990-ffffffff812089f9: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121e0b0)
Location: kernel/cgroup/cgroup.c:645
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8121e0b0-ffffffff8121e119: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81235d10)
Location: kernel/cgroup/cgroup.c:625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81235d10-ffffffff81235d79: cgroup_task_count (STB_GLOBAL)
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
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d1fa8)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffff8000101d1fa8-ffff8000101d2078: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0414ed8)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
c0414ed8-c0414f54: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023caf0)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
c00000000023caf0-c00000000023cbe0: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014b988)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffe00014b988-ffffffe00014ba24: cgroup_task_count (STB_GLOBAL)
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
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159330)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81159330-ffffffff8115939b: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c640)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8114c640-ffffffff8114c6a5: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157100)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81157100-ffffffff8115716b: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164120)
Location: kernel/cgroup/cgroup.c:619
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81164120-ffffffff81164186: cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
