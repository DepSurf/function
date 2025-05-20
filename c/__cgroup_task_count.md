# Function: <code>__cgroup_task_count</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811550f9)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81155090-ffffffff811550d8: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160d29)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81160cc0-ffffffff81160d08: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172379)
Location: kernel/cgroup/cgroup.c:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81172310-ffffffff81172358: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f019)
Location: kernel/cgroup/cgroup.c:592
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff8116efb0-ffffffff8116eff8: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116fc49)
Location: kernel/cgroup/cgroup.c:592
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff8116fbe0-ffffffff8116fc28: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81196009)
Location: kernel/cgroup/cgroup.c:623
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81195fa0-ffffffff81195fe8: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c5f09)
Location: kernel/cgroup/cgroup.c:624
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff811c5e90-ffffffff811c5ee7: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812089a9)
Location: kernel/cgroup/cgroup.c:629
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81208920-ffffffff81208977: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121e0c9)
Location: kernel/cgroup/cgroup.c:628
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff8121e040-ffffffff8121e097: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81235d29)
Location: kernel/cgroup/cgroup.c:608
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff81235ca0-ffffffff81235cf7: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d1ff4)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffff8000101d1f50-ffff8000101d1fa4: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0414ef8)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
c0414e90-c0414ed8: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023cb24)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
c00000000023ca80-c00000000023cae4: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014b9ae)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffe00014b944-ffffffe00014b988: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159349)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff811592e0-ffffffff81159328: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c659)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff8114c5f0-ffffffff8114c638: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157119)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff811570b0-ffffffff811570f8: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_task_count(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116413a)
Location: kernel/cgroup/cgroup.c:602
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_task_count
Direct callers:
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
**Symbols:**

```
ffffffff811640d0-ffffffff81164118: __cgroup_task_count (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
