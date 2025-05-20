# Function: <code>cpudl_heapify_up</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ce090)
Location: kernel/sched/cpudeadline.c:76
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ce090-ffffffff810ce12b: cpudl_heapify_up.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ca9e0)
Location: kernel/sched/cpudeadline.c:76
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ca9e0-ffffffff810caa7d: cpudl_heapify_up.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810d2190)
Location: kernel/sched/cpudeadline.c:76
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810d2190-ffffffff810d222d: cpudl_heapify_up.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810da260)
Location: kernel/sched/cpudeadline.c:73
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810da260-ffffffff810da2fc: cpudl_heapify_up.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810e3db0)
Location: kernel/sched/cpudeadline.c:73
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810e3db0-ffffffff810e3e4c: cpudl_heapify_up.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ea9a0)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ea9a0-ffffffff810eaa3c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f6370)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810f6370-ffffffff810f640c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ffdb0)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ffdb0-ffffffff810ffe55: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810fe880)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810fe880-ffffffff810fe925: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff81100b70)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff81100b70-ffffffff81100c15: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff8111cce0)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff8111cce0-ffffffff8111cd85: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112dce0)
Location: kernel/sched/cpudeadline.c:68
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_heapify
```
**Symbols:**

```
ffffffff8112dce0-ffffffff8112ddb9: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81157b50)
Location: kernel/sched/cpudeadline.c:68
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_heapify
```
**Symbols:**

```
ffffffff81157b50-ffffffff81157c29: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81167c10)
Location: kernel/sched/cpudeadline.c:68
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_heapify
```
**Symbols:**

```
ffffffff81167c10-ffffffff81167ce9: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174a10)
Location: kernel/sched/cpudeadline.c:68
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_heapify
```
**Symbols:**

```
ffffffff81174a10-ffffffff81174ae9: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffff80001015a178)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffff80001015a178-ffff80001015a24c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c03a6ea8)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
c03a6ea8-c03a6fb4: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c0000000001ae3e0)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
c0000000001ae3e0-c0000000001ae4d4: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpudl_heapify_up(struct cpudl *cp, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffe0000ffb56)
Location: kernel/sched/cpudeadline.c:69
Inline: False
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffe0000ffb56-ffffffe0000ffbfe: cpudl_heapify_up (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ef770)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ef770-ffffffff810ef80c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810df7e0)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810df7e0-ffffffff810df87c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ec8a0)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810ec8a0-ffffffff810ec93c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f78e0)
Location: kernel/sched/cpudeadline.c:69
Inline: True
Direct callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
**Symbols:**

```
ffffffff810f78e0-ffffffff810f797c: cpudl_heapify_up.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
