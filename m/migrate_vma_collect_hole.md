# Function: <code>migrate_vma_collect_hole</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81248dc0)
Location: mm/migrate.c:2146
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81248dc0-ffffffff81248e1a: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126c880)
Location: mm/migrate.c:2158
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff8126c880-ffffffff8126c8da: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281190)
Location: mm/migrate.c:2138
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81281190-ffffffff812811ea: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812acca0)
Location: mm/migrate.c:2156
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812acca0-ffffffff812accfa: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e4544)
Location: mm/migrate.c:2163
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812e1d50-ffffffff812e1da3: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ecbf0)
Location: mm/migrate.c:2313
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812ecbf0-ffffffff812ecc92: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f4190)
Location: mm/migrate.c:2297
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812f4190-ffffffff812f4231: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133ebe0)
Location: mm/migrate.c:2226
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff8133ebe0-ffffffff8133ec81: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff813b6260)
Location: mm/migrate_device.c:34
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff813b6260-ffffffff813b631f: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff81437aa0)
Location: mm/migrate_device.c:35
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81437aa0-ffffffff81437b5c: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8146d760)
Location: mm/migrate_device.c:35
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff8146d760-ffffffff8146d81c: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8149cac0)
Location: mm/migrate_device.c:35
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff8149cac0-ffffffff8149cb7c: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000430dc0)
Location: mm/migrate.c:2156
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
c000000000430dc0-c000000000430e38: migrate_vma_collect_hole (STB_LOCAL)
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5280)
Location: mm/migrate.c:2156
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812a5280-ffffffff812a52da: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81296d50)
Location: mm/migrate.c:2156
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81296d50-ffffffff81296daa: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3090)
Location: mm/migrate.c:2156
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812a3090-ffffffff812a30ea: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b3320)
Location: mm/migrate.c:2156
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff812b3320-ffffffff812b337a: migrate_vma_collect_hole (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int depth</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, end, walk</code> ➡️ <code>start, end, depth, walk</code>
</li>
</ul>
</details>
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
