# Function: <code>collect_procs_file</code>

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
In mm/memory-failure.c (ffffffff81202c86)
Location: mm/memory-failure.c:441
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
In mm/memory-failure.c (ffffffff8122730f)
Location: mm/memory-failure.c:437
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
In mm/memory-failure.c (ffffffff812398d0)
Location: mm/memory-failure.c:437
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
In mm/memory-failure.c (ffffffff81244c3e)
Location: mm/memory-failure.c:440
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
In mm/memory-failure.c (ffffffff81264b2e)
Location: mm/memory-failure.c:440
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
In mm/memory-failure.c (ffffffff81288cd6)
Location: mm/memory-failure.c:471
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
In mm/memory-failure.c (ffffffff8129dc26)
Location: mm/memory-failure.c:473
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
In mm/memory-failure.c (ffffffff812b8d96)
Location: mm/memory-failure.c:470
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
In mm/memory-failure.c (ffffffff812cac86)
Location: mm/memory-failure.c:474
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
void collect_procs_file(struct page *page, struct list_head *to_kill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81300c70)
Location: mm/memory-failure.c:481
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81300c70-ffffffff81300e66: collect_procs_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collect_procs_file(struct page *page, struct list_head *to_kill, int force_early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8130ce10)
Location: mm/memory-failure.c:505
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8130ce10-ffffffff8130d007: collect_procs_file (STB_LOCAL)
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
In mm/memory-failure.c (ffffffff813134d0)
Location: mm/memory-failure.c:509
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
In mm/memory-failure.c (ffffffff8135ff90)
Location: mm/memory-failure.c:521
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
In mm/memory-failure.c (ffffffff813dad3d)
Location: mm/memory-failure.c:518
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
In mm/memory-failure.c (ffffffff8146115f)
Location: mm/memory-failure.c:551
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81497de9)
Location: mm/memory-failure.c:640
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff814c73b0)
Location: mm/memory-failure.c:635
Inline: True
```
**Symbols:**

```
ffffffff814c73b0-ffffffff814c7557: collect_procs_file.isra.0 (STB_LOCAL)
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
In mm/memory-failure.c (ffff80001036ed20)
Location: mm/memory-failure.c:474
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
In mm/memory-failure.c (c00000000045f1c8)
Location: mm/memory-failure.c:474
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
In mm/memory-failure.c (ffffffff812c3266)
Location: mm/memory-failure.c:474
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
In mm/memory-failure.c (ffffffff812b42a6)
Location: mm/memory-failure.c:474
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
In mm/memory-failure.c (ffffffff812c1076)
Location: mm/memory-failure.c:474
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
In mm/memory-failure.c (ffffffff812d1b36)
Location: mm/memory-failure.c:474
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
</ul>
