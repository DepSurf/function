# Function: <code>tlb_table_flush</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209768)
Location: mm/memory.c:365
Inline: True
Inline callers:
  - mm/memory.c:tlb_remove_table
```
**Symbols:**

```
ffffffff812096f0-ffffffff81209722: tlb_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8122a5dd)
Location: mm/memory.c:379
Inline: True
Inline callers:
  - mm/memory.c:tlb_remove_table
  - mm/memory.c:tlb_flush_mmu_free
Direct callers:
  - mm/memory.c:tlb_remove_table
  - mm/memory.c:tlb_flush_mmu_free
```
**Symbols:**

```
ffffffff81229230-ffffffff8122925d: tlb_table_flush.part.92 (STB_LOCAL)
ffffffff8122a590-ffffffff8122a5a8: tlb_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124cb70)
Location: mm/mmu_gather.c:196
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_flush_mmu_free
```
**Symbols:**

```
ffffffff8124cb70-ffffffff8124cc86: tlb_table_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125ee60)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8125ee60-ffffffff8125ef71: tlb_table_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126d670)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff8126d670-ffffffff8126d781: tlb_table_flush (STB_LOCAL)
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
In mm/mmu_gather.c (ffffffff8129de52)
Location: mm/mmu_gather.c:196
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff812a91d2)
Location: mm/mmu_gather.c:196
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff812ae642)
Location: mm/mmu_gather.c:196
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff812efde2)
Location: mm/mmu_gather.c:196
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff813532ec)
Location: mm/mmu_gather.c:209
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff813cd5ac)
Location: mm/mmu_gather.c:246
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/mmu_gather.c (ffffffff81401f0c)
Location: mm/mmu_gather.c:246
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e55c)
Location: mm/mmu_gather.c:247
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304a90)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffff800010304a90-ffff800010304ae4: tlb_table_flush (STB_LOCAL)
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
In mm/mmu_gather.c (c0000000003d192c)
Location: mm/mmu_gather.c:146
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
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
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81265cc0)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81265cc0-ffffffff81265dd1: tlb_table_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812580e0)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff812580e0-ffffffff812581f1: tlb_table_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263a60)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81263a60-ffffffff81263b71: tlb_table_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tlb_table_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81273420)
Location: mm/mmu_gather.c:146
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
```
**Symbols:**

```
ffffffff81273420-ffffffff81273531: tlb_table_flush (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
