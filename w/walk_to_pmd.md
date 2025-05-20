# Function: <code>walk_to_pmd</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292785)
Location: mm/memory.c:1421
Inline: True
Inline callers:
  - mm/memory.c:__get_locked_pte
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
In mm/memory.c (ffffffff8129d0e5)
Location: mm/memory.c:1595
Inline: True
Inline callers:
  - mm/memory.c:__get_locked_pte
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
In mm/memory.c (ffffffff812a27d5)
Location: mm/memory.c:1613
Inline: True
Inline callers:
  - mm/memory.c:__get_locked_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pmd_t *walk_to_pmd(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1708
Inline: False
Direct callers:
  - mm/memory.c:__get_locked_pte
```
**Symbols:**

```
ffffffff812e5bf0-ffffffff812e5d4b: walk_to_pmd (STB_LOCAL)
ffffffff81cbc601-ffffffff81cbc61a: walk_to_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pmd_t *walk_to_pmd(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1802
Inline: False
Direct callers:
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
```
**Symbols:**

```
ffffffff81344ec0-ffffffff81345032: walk_to_pmd (STB_LOCAL)
ffffffff81e6e039-ffffffff81e6e052: walk_to_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pmd_t *walk_to_pmd(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1773
Inline: False
Direct callers:
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
```
**Symbols:**

```
ffffffff813bd100-ffffffff813bd272: walk_to_pmd (STB_LOCAL)
ffffffff8206403b-ffffffff82064054: walk_to_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pmd_t *walk_to_pmd(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1789
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:__get_locked_pte
```
**Symbols:**

```
ffffffff813f1e50-ffffffff813f1fc6: walk_to_pmd (STB_LOCAL)
ffffffff820e3727-ffffffff820e3740: walk_to_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pmd_t *walk_to_pmd(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1822
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:__get_locked_pte
```
**Symbols:**

```
ffffffff8141cad0-ffffffff8141cc46: walk_to_pmd (STB_LOCAL)
ffffffff821c0170-ffffffff821c0189: walk_to_pmd.cold (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
