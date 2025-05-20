# Function: <code>collect_procs_anon</code>

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
In mm/memory-failure.c (ffffffff8120287c)
Location: mm/memory-failure.c:405
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
In mm/memory-failure.c (ffffffff81226f40)
Location: mm/memory-failure.c:401
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
In mm/memory-failure.c (ffffffff81239505)
Location: mm/memory-failure.c:401
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
In mm/memory-failure.c (ffffffff81244af9)
Location: mm/memory-failure.c:404
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
In mm/memory-failure.c (ffffffff812649e9)
Location: mm/memory-failure.c:404
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81288df7)
Location: mm/memory-failure.c:435
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8129dd47)
Location: mm/memory-failure.c:437
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b8ed3)
Location: mm/memory-failure.c:434
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812cadc3)
Location: mm/memory-failure.c:438
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void collect_procs_anon(struct page *page, struct list_head *to_kill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81300a60)
Location: mm/memory-failure.c:445
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81300a60-ffffffff81300c70: collect_procs_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collect_procs_anon(struct page *page, struct list_head *to_kill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8130cc00)
Location: mm/memory-failure.c:469
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8130cc00-ffffffff8130ce10: collect_procs_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813133a5)
Location: mm/memory-failure.c:473
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135fe65)
Location: mm/memory-failure.c:485
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813dab6e)
Location: mm/memory-failure.c:481
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81460f8e)
Location: mm/memory-failure.c:513
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void collect_procs_anon(struct page *page, struct list_head *to_kill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81497a90)
Location: mm/memory-failure.c:602
Inline: False
```
**Symbols:**

```
ffffffff81497a90-ffffffff81497d1e: collect_procs_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void collect_procs_anon(struct folio *folio, struct page *page, struct list_head *to_kill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c71b0)
Location: mm/memory-failure.c:598
Inline: False
```
**Symbols:**

```
ffffffff814c71b0-ffffffff814c7393: collect_procs_anon (STB_LOCAL)
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
In mm/memory-failure.c (ffff80001036eb18)
Location: mm/memory-failure.c:438
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045f370)
Location: mm/memory-failure.c:438
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c33a3)
Location: mm/memory-failure.c:438
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b43e3)
Location: mm/memory-failure.c:438
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c11b3)
Location: mm/memory-failure.c:438
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812d1c72)
Location: mm/memory-failure.c:438
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, to_kill, force_early</code> ➡️ <code>folio, page, to_kill, force_early</code>
</li>
</ul>
</details>
</li>
</ul>
