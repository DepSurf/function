# Function: <code>kill_procs</code>

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
In mm/memory-failure.c (ffffffff81202b84)
Location: mm/memory-failure.c:325
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/memory-failure.c (ffffffff812271de)
Location: mm/memory-failure.c:323
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/memory-failure.c (ffffffff812397b0)
Location: mm/memory-failure.c:323
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81244ca6)
Location: mm/memory-failure.c:326
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81264b96)
Location: mm/memory-failure.c:326
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:359
Inline: False
```
**Symbols:**

```
ffffffff812882b0-ffffffff81288329: kill_procs (STB_LOCAL)
ffffffff8128a83e-ffffffff8128a94c: kill_procs.cold.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:360
Inline: False
```
**Symbols:**

```
ffffffff8129d200-ffffffff8129d279: kill_procs (STB_LOCAL)
ffffffff8129f79e-ffffffff8129f8b3: kill_procs.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:357
Inline: False
```
**Symbols:**

```
ffffffff812b8300-ffffffff812b8387: kill_procs (STB_LOCAL)
ffffffff812ba975-ffffffff812baa9a: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:361
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812ca1e0-ffffffff812ca267: kill_procs (STB_LOCAL)
ffffffff812cc855-ffffffff812cc976: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:357
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff813001c0-ffffffff81300260: kill_procs (STB_LOCAL)
ffffffff81302b33-ffffffff81302c4c: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:381
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8130c470-ffffffff8130c50f: kill_procs (STB_LOCAL)
ffffffff81be9e77-ffffffff81be9f87: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:385
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81312bd0-ffffffff81312c70: kill_procs (STB_LOCAL)
ffffffff81bdbea3-ffffffff81bdbfa3: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:397
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff8135e660-ffffffff8135e6f7: kill_procs (STB_LOCAL)
ffffffff81cc2e77-ffffffff81cc2efc: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:393
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff813d8e40-ffffffff813d8ee8: kill_procs (STB_LOCAL)
ffffffff81e7553e-ffffffff81e755c3: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145e900)
Location: mm/memory-failure.c:424
Inline: False
Direct callers:
  - mm/memory-failure.c:unmap_and_kill
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff8145e900-ffffffff8145ea61: kill_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81494750)
Location: mm/memory-failure.c:514
Inline: False
Direct callers:
  - mm/memory-failure.c:unmap_and_kill
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff81494750-ffffffff814948b1: kill_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c4060)
Location: mm/memory-failure.c:510
Inline: False
Direct callers:
  - mm/memory-failure.c:unmap_and_kill
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff814c4060-ffffffff814c41c1: kill_procs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036ec44)
Location: mm/memory-failure.c:361
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045df50)
Location: mm/memory-failure.c:361
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
c00000000045df50-c00000000045e1b0: kill_procs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:361
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c27c0-ffffffff812c2847: kill_procs (STB_LOCAL)
ffffffff812c4e35-ffffffff812c4f56: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:361
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812b3810-ffffffff812b3897: kill_procs (STB_LOCAL)
ffffffff812b5e75-ffffffff812b5f96: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:361
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c05d0-ffffffff812c0657: kill_procs (STB_LOCAL)
ffffffff812c2c45-ffffffff812c2d66: kill_procs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void kill_procs(struct list_head *to_kill, int forcekill, bool fail, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:361
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812d1070-ffffffff812d10f7: kill_procs (STB_LOCAL)
ffffffff812d36e5-ffffffff812d3806: kill_procs.cold (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
