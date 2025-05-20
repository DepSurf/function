# Function: <code>pmd_devmap_trans_unstable</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1640)
Location: mm/memory.c:3074
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff811f1640-ffffffff811f16bf: pmd_devmap_trans_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208330)
Location: mm/memory.c:3243
Inline: True
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81208330-ffffffff812083ea: pmd_devmap_trans_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81229310)
Location: mm/memory.c:3288
Inline: True
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81229310-ffffffff812293a9: pmd_devmap_trans_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123c910)
Location: mm/memory.c:3048
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff8123c910-ffffffff8123c9a9: pmd_devmap_trans_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124e100)
Location: mm/memory.c:3111
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff8124e100-ffffffff8124e199: pmd_devmap_trans_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125c670)
Location: mm/memory.c:3136
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff8125c670-ffffffff8125c709: pmd_devmap_trans_unstable (STB_LOCAL)
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
In mm/memory.c (ffffffff81292222)
Location: mm/memory.c:3502
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
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
In mm/memory.c (ffffffff8129cad2)
Location: mm/memory.c:3661
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125f9e0)
Location: include/linux/pgtable.h:1339
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff812a21e6)
Location: include/linux/pgtable.h:1339
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129c350)
Location: include/linux/pgtable.h:1358
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff812e3556)
Location: include/linux/pgtable.h:1358
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f34ed)
Location: include/linux/pgtable.h:1420
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff813448e6)
Location: include/linux/pgtable.h:1420
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135d83d)
Location: include/linux/pgtable.h:1443
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/memory.c (ffffffff813bcae6)
Location: include/linux/pgtable.h:1443
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/memory.c (ffff8000102f9d24)
Location: mm/memory.c:3136
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c3de0)
Location: mm/memory.c:3136
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3136
Inline: True
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
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254cc0)
Location: mm/memory.c:3136
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81254cc0-ffffffff81254d59: pmd_devmap_trans_unstable (STB_LOCAL)
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
In mm/memory.c (ffffffff8124d419)
Location: mm/memory.c:3136
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252a60)
Location: mm/memory.c:3136
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81252a60-ffffffff81252af9: pmd_devmap_trans_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pmd_devmap_trans_unstable(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262440)
Location: mm/memory.c:3136
Inline: True
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
**Symbols:**

```
ffffffff81262440-ffffffff812624d9: pmd_devmap_trans_unstable (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
