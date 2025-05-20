# Function: <code>collect_procs</code>

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
In mm/memory-failure.c (ffffffff81202837)
Location: mm/memory-failure.c:479
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
In mm/memory-failure.c (ffffffff81226eee)
Location: mm/memory-failure.c:475
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
In mm/memory-failure.c (ffffffff812394b5)
Location: mm/memory-failure.c:475
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
In mm/memory-failure.c (ffffffff81244aa9)
Location: mm/memory-failure.c:478
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
In mm/memory-failure.c (ffffffff81264999)
Location: mm/memory-failure.c:478
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81288c60)
Location: mm/memory-failure.c:509
Inline: False
```
**Symbols:**

```
ffffffff81288c60-ffffffff81288fb8: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8129dbb0)
Location: mm/memory-failure.c:511
Inline: False
```
**Symbols:**

```
ffffffff8129dbb0-ffffffff8129df0c: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b8d20)
Location: mm/memory-failure.c:508
Inline: False
```
**Symbols:**

```
ffffffff812b8d20-ffffffff812b90b4: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812cac10)
Location: mm/memory-failure.c:512
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812cac10-ffffffff812cafa4: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81300efb)
Location: mm/memory-failure.c:516
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8130dd06)
Location: mm/memory-failure.c:541
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81313360)
Location: mm/memory-failure.c:545
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81313360-ffffffff81313670: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135fe20)
Location: mm/memory-failure.c:557
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff8135fe20-ffffffff8136010d: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff813db05c)
Location: mm/memory-failure.c:554
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff813dab30-ffffffff813daf95: collect_procs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff81461558)
Location: mm/memory-failure.c:616
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff81460f50-ffffffff814613c8: collect_procs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81497d30)
Location: mm/memory-failure.c:711
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff81497d30-ffffffff8149801c: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void collect_procs(struct folio *folio, struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c7570)
Location: mm/memory-failure.c:713
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff814c7570-ffffffff814c76a9: collect_procs (STB_LOCAL)
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
In mm/memory-failure.c (ffff80001036ead4)
Location: mm/memory-failure.c:512
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
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045f120)
Location: mm/memory-failure.c:512
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
c00000000045f120-c00000000045f660: collect_procs (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c31f0)
Location: mm/memory-failure.c:512
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c31f0-ffffffff812c3584: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b4230)
Location: mm/memory-failure.c:512
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812b4230-ffffffff812b45c4: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c1000)
Location: mm/memory-failure.c:512
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c1000-ffffffff812c1394: collect_procs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void collect_procs(struct page *page, struct list_head *tokill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812d1ac0)
Location: mm/memory-failure.c:512
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812d1ac0-ffffffff812d1e52: collect_procs (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, tokill, force_early</code> ➡️ <code>folio, page, tokill, force_early</code>
</li>
</ul>
</details>
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
